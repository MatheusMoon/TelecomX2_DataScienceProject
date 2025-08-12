# 📊 Projeto de Classificação — Telecom Churn

[![Python](https://img.shields.io/badge/Python-3.10+-blue.svg)](https://www.python.org/)
[![Jupyter Notebook](https://img.shields.io/badge/Jupyter-Notebook-orange.svg)](https://jupyter.org/)
[![Pandas](https://img.shields.io/badge/Pandas-1.x-lightblue.svg)](https://pandas.pydata.org/)
[![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-1.x-yellow.svg)](https://scikit-learn.org/)
[![Imbalanced-Learn](https://img.shields.io/badge/Imbalanced--Learn-SMOTE-red.svg)](https://imbalanced-learn.org/stable/)
[![License](https://img.shields.io/badge/license-MIT-green.svg)](LICENSE)

## 📌 Descrição
Este projeto tem como objetivo prever o **churn de clientes** em uma operadora de telecomunicações, utilizando técnicas de **Machine Learning**.  
O trabalho foi desenvolvido em **Jupyter Notebook** e utiliza bibliotecas do ecossistema Python para análise exploratória, pré-processamento e modelagem.

## 🛠️ Tecnologias Utilizadas
- **Python 3.10+**
- **Pandas** — Manipulação e análise de dados
- **NumPy** — Operações numéricas
- **Matplotlib** — Visualização de dados
- **Scikit-learn** — Treinamento e avaliação de modelos
- **Imbalanced-learn (SMOTE)** — Balanceamento de classes

## 📂 Estrutura do Projeto
├── telecom-x-parte2-br.ipynb # Notebook com todo o fluxo de análise e modelagem
├── data/ # (Opcional) Pasta para armazenar datasets
└── README.md # Documentação do projeto

markdown
Copiar
Editar

## 🚀 Funcionalidades
- 📊 **Análise exploratória de dados (EDA)**
- 🧹 **Tratamento de dados e normalização**
- ⚖️ **Balanceamento de classes com SMOTE**
- 🤖 **Treinamento de modelos (Random Forest e Regressão Logística)**
- 📈 **Avaliação de métricas de desempenho**  
  - Acurácia  
  - Precisão  
  - Recall  
  - F1-Score  
  - Matriz de confusão

## 📦 Como Executar
1. Clone este repositório:
   ```bash
   git clone https://github.com/usuario/projeto-telecom-churn.git
Acesse a pasta do projeto:

bash
Copiar
Editar
cd projeto-telecom-churn
Crie um ambiente virtual e instale as dependências:

bash
Copiar
Editar
python -m venv venv
source venv/bin/activate   # Linux/Mac
venv\Scripts\activate      # Windows
pip install -r requirements.txt
Abra o Jupyter Notebook:

bash
Copiar
Editar
jupyter notebook
