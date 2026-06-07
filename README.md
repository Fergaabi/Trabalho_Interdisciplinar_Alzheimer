# Trabalho Interdisciplinar - KNN para Diagnóstico de Alzheimer

## Integrantes

* Nome Completo - RA
* Nome Completo - RA
* Nome Completo - RA

## Objetivo

Este projeto tem como objetivo implementar o algoritmo K-Nearest Neighbors (KNN) para classificação de pacientes com possível diagnóstico da Doença de Alzheimer, utilizando tanto uma implementação manual quanto uma implementação com biblioteca especializada.

## Estrutura do Projeto

### alzheimer_dataset.csv

Dataset original utilizado no trabalho.

### alzheimer_dataset_preparado.csv

Dataset após o pré-processamento inicial, com remoção de atributos não relevantes para a classificação.

### analise_exploratoria.ipynb

Notebook contendo:

* Leitura dos dados
* Análise exploratória
* Verificação de valores nulos
* Estatísticas descritivas
* Preparação inicial dos dados

### knn_manual.ipynb

Notebook contendo:

* Implementação manual do algoritmo KNN
* Cálculo da Distância Euclidiana
* Busca dos vizinhos mais próximos
* Processo de votação das classes
* Avaliação da acurácia

### knn_sklearn.ipynb

Notebook contendo:

* Implementação do KNN utilizando a biblioteca scikit-learn
* Avaliação da acurácia
* Testes com diferentes valores de K

## Dataset

O conjunto de dados contém informações de 2149 pacientes e possui atributos demográficos, clínicos, cognitivos e comportamentais relacionados à Doença de Alzheimer.

Variável alvo:

* Diagnosis

  * 0 = Não possui Alzheimer
  * 1 = Possui Alzheimer

## Resultados

### Implementação Manual

* Acurácia: 53,95%

### Implementação com Scikit-Learn

* Acurácia: 53,95%

### Testes com diferentes valores de K

| K  | Acurácia |
| -- | -------- |
| 1  | 54,42%   |
| 3  | 55,81%   |
| 5  | 53,95%   |
| 7  | 55,35%   |
| 9  | 58,60%   |
| 11 | 56,28%   |

Melhor resultado obtido:

* K = 9
* Acurácia = 58,60%

## Tecnologias Utilizadas

* Python
* Pandas
* Scikit-Learn
* Jupyter Notebook
