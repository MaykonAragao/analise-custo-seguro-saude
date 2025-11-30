# 🩺 Análise Preditiva de Custos de Seguro de Saúde

![Status](https://img.shields.io/badge/status-conclu%C3%ADdo-brightgreen)

## 📄 Descrição do Projeto

Este projeto tem como objetivo construir um modelo de Machine Learning para prever os custos de seguro de saúde para indivíduos com base em um conjunto de características. A análise utiliza a Regressão Linear para identificar os fatores que mais influenciam nos custos e criar um modelo preditivo.

## 📊 Dataset

O dataset utilizado foi o "Insurance Forecast by using Linear Regression", obtido na plataforma Kaggle. Ele pode ser encontrado neste [link](https://www.kaggle.com/datasets/mirichoi0218/insurance).

O arquivo `insurance.csv` contém as seguintes colunas:
*   `age`: Idade do beneficiário.
*   `sex`: Gênero do beneficiário.
*   `bmi`: Índice de Massa Corporal (IMC).
*   `children`: Número de filhos/dependentes.
*   `smoker`: Se o beneficiário é fumante ou não.
*   `region`: Região geográfica nos EUA.
*   `charges`: Custos médicos individuais faturados pelo seguro (variável alvo).

## 🛠️ Ferramentas Utilizadas

*   **Linguagem:** Python 3
*   **Bibliotecas:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn
*   **Ambiente:** Jupyter Notebook

## 📈 Principais Descobertas

A análise e o modelo de Regressão Linear revelaram os seguintes insights:

*   🚭 **Fator Mais Importante:** A característica **`smoker_yes`** tem o maior coeficiente positivo (**9558**), confirmando que ser fumante é o principal fator que eleva o custo.
*   🎂 **Outros Fatores Relevantes:** A **idade (`age`)** e o **IMC (`bmi`)** também são muito significativos, com coeficientes de **3615** e **2036**, respectivamente.
*   📊 **Performance do Modelo:** O modelo final alcançou um **R² de 0.78** no conjunto de teste, indicando que ele consegue explicar 78% da variabilidade dos custos.

## 🚀 Como Executar

1.  Clone este repositório.
2.  Certifique-se de ter as bibliotecas listadas acima instaladas.
3.  Abra o arquivo `analise_exploratoria_seguro.ipynb` em um ambiente Jupyter.
