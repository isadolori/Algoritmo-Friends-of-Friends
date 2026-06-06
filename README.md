# Projeto Final: Teoria dos Grafos na Astrofísica - Algoritmo Friends-of-Friends

## Sobre o Projeto

Este projeto aplica a Teoria dos Grafos para identificar estruturas em larga escala no Universo (aglomerados de galáxias) utilizando o algoritmo Friends-of-Friends (FoF). A base de dados utilizada é o catálogo observacional real do SDSS (Sloan Digital Sky Survey).

O projeto realiza a construção de um grafo não direcionado, ponderado e com múltiplos componentes, executa um BFS para realizar as análises:
* Conectividade (Descoberta de múltiplos aglomerados e galáxias isoladas)
* Identificação de centros gravitacionais (Galáxia central) com base baseada no grau do vértice
* Caminhos Mínimos / Excentricidade (Raio do aglomerado calculado em saltos a partir do núcleo)

## Estrutura dos Arquivos
* main.ipynb : Notebook principal contendo a coleta de dados, modelagem do grafo, a execução dos algoritmos de busca, os resultados das análises e a plotagem dos graficos
* README.md : Esse arquivo

## Bibliotecas utilizadas
* numpy
* matplotlib
* astropy
* astroquery
* scipy

Se for necessário rodar esse comando no terminal para instalar as dependências:

```bash
pip install numpy matplotlib astropy astroquery scipy
```

## Como rodar 

1. Abrir o arquivo main.ipynb em um ambiente Jupyter ou Google Colab

2. Executar as células do notebook sequencialmente (ou clicar em Run All / Executar Tudo)

## Relatório do projeto

[Link para o Overleaf](https://docs.github.com)