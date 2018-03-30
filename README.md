# Miguezeiros - Projeto 1
Repositório do grupo **'Miguezeiros'**, composto por @lucaswatanuki, @filipesbernardo e @rmzanco para a disciplina **Sistemas Operacioinais**.

## Objetivo :dart:
Este projeto tem como finalidade a criação de um programa que utilize múltiplas threads para procurar um determinado valor em uma matriz M x N (com M linhas e N colunas) e a análise do desempenho desse programa com 2, 4, 8 e 16 threads.

O projeto, obrigatoriamente, deverá utilizar:

* Sistema operacional Linux;
* Biblioteca POSIX Threads.

## Descrição do problema a ser resolvido :memo:
Considere uma matriz M x N (M linhas, N colunas) que **contém valores em ponto flutuante, positivos ou negativos**. O programa deverá utilizar múltiplos threads para encontrar um determinado valor nessa matriz.

O programa deverá considerar os seguintes fatos:

1. A matriz contém números reais, aleatórios, não ordenados;
1. A matriz pode ter valores repetidos. Nesse caso, todas as posições em que o elemento ocorrer devem ser apontadas na saída do programa;
1. Pode ser que o elemento não conste da matriz.