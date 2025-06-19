# Projeto 4 - Álgebra Linear Numérica

Professor: Bernardo Freitas Paulo da Costa

## Sobre o projeto

Este trabalho tem como objetivo estudar propriedades estatísticas de **matrizes gaussianas** por meio de simulações numéricas e visualizações gráficas em Python. Exploramos distribuições das normas, produtos internos e a “quase ortogonalidade” das colunas de matrizes aleatórias cujos elementos seguem uma distribuição normal padrão $\mathcal{N}(0,1)$. A resolução completa de todas as questões está no arquivo `main.ipynb`

## Questões

### Questão 1 — Matrizes Gaussianas
**Uma matriz gaussiana tem todas as entradas $A_{ij}$ independentes e distribuídas segundo uma normal padrão, ou seja, $A_{ij} \sim \mathcal{N} (0, 1)$**
<br>
<br>
a) **Distribuição de normas.** Faça um histograma da norma-$2$ das colunas de uma matriz gaussiana $A$, $ m \times n $. Use vários valores de $m$, e comente o que você observa.
<br>
<br>
b) **Produtos internos.** Agora, fixe $m = 100$ e faça o histograma do produto interno $ \left< A_i, A_j \right>$ entre colunas de uma matriz gaussiana $A$. Exclua os casos $i = j$, e use $n = 100$, $200$, $500$ e $1000$. O que acontece? Qual parece ser a distribuição para $n \rightarrow \infty$?
<br>
<br>
c) **A distribuição do máximo.** Queremos ver quão “não ortogonal” é a matriz $A$. Para isso, vamos estudar o máximo de $\dfrac{|\left<A_i, A_j \right>|}{\|A_i\|\|A_j\|}$ entre colunas distintas de uma matriz gaussiana $A$. Para isto, gere $K = 1000$ matrizes gaussianas $A_k$ de ordem $100 \times 300$, calcule o máximo indicado acima, e faça um histograma dos $K$ valores obtidos.
<br>
<br>
d) **Complexidade computacional.** Qual a complexidade de calcular o máximo acima? Qual valor de $K$ você acha que seria bom para ter uma boa estimativa do máximo esperado?
<br>
<br>
e) **A distribuição do máximo, parte 2.** Escolha valores de $K$ correspondentes e faça histogramas e comente os resultados para os seguintes pares de $(m, n)$: $(100, 100)$, $(100, 300)$ $(200, 200)$, $(200, 600)$, $(500, 500)$, $(500, 1500)$, $(1000, 1000)$, $(1000, 3000)$.

## Integrantes

Roger Vinícius Pereira Augusto
Matrícula: 241708020
<br>
Vinício Vasconcelos Muniz Deusdará
Matrícula: 231708029