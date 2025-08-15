# Exercícios de Estrutura de Dados em C#

Este repositório contém exercícios práticos da disciplina **Estrutura de Dados**, desenvolvidos em **C#** no Programiz Online Compiler, com foco em **manipulação de matrizes (arrays bidimensionais)**.

## 📚 Atividades

### **Atividade 1 – Acessar elementos da matriz**
Objetivo: acessar e exibir elementos específicos de uma matriz 3×4.

- Elemento na linha 1, coluna 3  
- Elemento na linha 2, coluna 1  
- Elemento na linha 3, coluna 4  

**Exemplo de código:**
```csharp
Console.WriteLine("Elemento na linha 1, coluna 3: " + matriz[0, 2]);
Console.WriteLine("Elemento na linha 2, coluna 1: " + matriz[1, 0]);
Console.WriteLine("Elemento na linha 3, coluna 4: " + matriz[2, 3]);

Atividade 2 – Manipulação de dados

Objetivo: alterar valores em posições específicas da matriz.

Alterar o valor da linha 2, coluna 1 para 12

Alterar o valor da linha 1, coluna 4 para 25

Alterar o valor da linha 3, coluna 2 para 55

Exemplo de código:

matriz[1, 0] = 12;
matriz[0, 3] = 25;
matriz[2, 1] = 55;

Atividade 3 – Soma de linhas

Objetivo: somar todos os itens de cada linha e determinar qual linha tem a maior soma.

Passos:

int maiorSoma = int.MinValue;
int linhaMaiorSoma = -1;

for (int i = 0; i < matriz.GetLength(0); i++)
{
    int somaLinha = 0;
    for (int j = 0; j < matriz.GetLength(1); j++)
    {
        somaLinha += matriz[i, j];
    }
    if (somaLinha > maiorSoma)
    {
        maiorSoma = somaLinha;
        linhaMaiorSoma = i + 1;
    }
}
Console.WriteLine($"A linha com maior soma é a linha {linhaMaiorSoma} com soma = {maiorSoma}");


Percorrer a matriz linha por linha.

Somar todos os elementos de cada linha.

Comparar para descobrir qual linha possui a maior soma.

Exemplo Real – Sistema de Vendas

Neste exemplo, uma matriz armazena as vendas semanais de 3 vendedores.
Cada linha representa um vendedor, e cada coluna representa uma semana do mês.

O programa:

Calcula o total de vendas de cada vendedor.

Informa qual vendedor teve o maior valor acumulado.

Saída esperada:

Total de vendas do Vendedor 1: R$ 7500
Total de vendas do Vendedor 2: R$ 8600
Total de vendas do Vendedor 3: R$ 9100

O vendedor com maior venda total foi o Vendedor 3 com R$ 9100 em vendas!
Como executar no Programiz

Acesse Programiz C# Compiler.

Cole o código desejado.

Clique em Run para executar.

🛠 Tecnologias utilizadas

Linguagem: C#

Ambiente: Programiz Online Compiler

Conceitos: Matrizes (arrays bidimensionais), loops aninhados, acesso e manipulação de dados.

✍ Autora: Luciane Rodrigues
📅 Ano: 2025
📌 Exercícios da disciplina Estrutura de Dados
