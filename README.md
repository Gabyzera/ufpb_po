# Projeto Branch and Bound

Este é o projeto final da disciplina de Pesquisa Operacional minisrada na Universidade Federal da Paraíba, ele implementa o algoritmo de Branch and Bound para resolver problemas de programação linear inteira. O objetivo é maximizar uma função objetivo sujeita a um conjunto de restrições.

## O que é Branch and Bound?

Branch and Bound é um algoritmo de otimização que resolve problemas de programação inteira. Ele divide o problema em subproblemas (branching) e calcula limites para esses subproblemas (bounding). Se um limite indica que um subproblema não pode produzir uma solução melhor do que a melhor solução conhecida, o subproblema é descartado. O processo continua até que todas as possibilidades sejam exploradas ou descartadas.

## Requisitos

Este projeto utiliza a biblioteca `python-mip` para modelagem e resolução dos problemas de otimização.

## Como Rodar o Projeto
   
1. Clone o repositório ou baixe os arquivos para o seu computador local.
2. Use o Google Collab se não tem o Python ou a biblioteca `python-mip` instalada.
   ou
3. Certifique-se de que você tenha Python e a biblioteca `python-mip` e `cdblib` instalados na sua máquina. 
   
O algoritmo processará o problema e retornará a melhor solução encontrada e o valor da função objetivo.

## Participantes

Beatriz Vitorio Melo Silva
Gabrielly SIlva Batista