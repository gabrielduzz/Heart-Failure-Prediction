# Previsão de Insuficiência Cardíaca com LSTM

Este repositório contém um projeto de análise de dados e aprendizagem profunda focado na saúde cardiovascular. O objetivo é processar dados clínicos de pacientes para prever eventos de insuficiência cardíaca utilizando Redes Neurais Recorrentes (RNN).

## 🚀 Sobre o Projeto

O projeto utiliza um conjunto de dados clínicos, incluindo idade, anemia, diabetes, pressão arterial, entre outros, para treinar um modelo capaz de identificar padrões de risco. A escolha da arquitetura **LSTM** permite explorar correlações complexas entre as variáveis de entrada.

## 🛠️ Funcionalidades e Etapas

- **Análise Exploratória de Dados:** Visualização de correlações e distribuição das características clínicas.
- **Pré-processamento:** Tratamento de dados, normalização e divisão entre conjuntos de treino e teste.
- **Arquitetura Deep Learning:** Implementação de uma rede neural com camadas LSTM para captura de padrões não lineares.
- **Avaliação de Métricas:** Monitorização de precisão (accuracy) e perda (loss) durante o treino.

## 📂 Estrutura do Repositório

- `Heart_Failure_Prediction_With_LSTM.ipynb`: Notebook Jupyter com todo o pipeline de desenvolvimento.
- `heart.csv`: Dataset contendo os registos clínicos utilizados.

## 💻 Tecnologias Utilizadas

- **Linguagem:** Python
- **Bibliotecas:** - Pandas e NumPy (Manipulação de dados)
  - Matplotlib e Seaborn (Visualização)
  - TensorFlow/Keras (Criação do modelo LSTM)
  - Scikit-learn (Métricas e pré-processamento)
