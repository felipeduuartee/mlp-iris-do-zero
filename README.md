# MLP do zero para classificação do Iris

Trabalho de Visão Computacional que depura e amplia uma implementação de perceptron multicamadas construída apenas com NumPy.

## Autores

- Felipe Duarte Silva — GRR20231957
- Paulo Henrique Jankosz — GRR20220627

## Conteúdo

- `MLP_Iris_do_zero.ipynb`: notebook completo e executado;
- `relatorio/relatorio_mlp_iris.pdf`: relatório em formato de artigo;
- `relatorio/relatorio_mlp_iris.tex`: fonte LaTeX;
- `resultados/`: gráficos produzidos pelos experimentos.

## Principais resultados

- acurácia média em dez divisões estratificadas: **96,67% ± 4,16%**;
- F1 macro médio: **96,68% ± 4,12%**;
- verificação numérica do backpropagation com erro relativo máximo de aproximadamente `1,21e-9`;
- demonstração controlada de overfitting com conjunto de treino reduzido.

## Execução

Abra `MLP_Iris_do_zero.ipynb` no Jupyter ou no Google Colab e execute as células em ordem. As dependências estão listadas em `requirements.txt`.
