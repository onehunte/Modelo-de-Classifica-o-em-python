# Classificação em Python

Este projeto realiza **classificação de textos utilizando machine learning**. Ele utiliza bibliotecas como `praw` (para extração de dados do Reddit), `scikit-learn` para o treinamento de modelos e `matplotlib` para visualização de resultados.

## 📋 Visão Geral

O notebook segue os seguintes passos:

1. **Instalação de dependências**:
   ```bash
   pip install praw config
   ```

2. **Coleta de dados**:
   - Utiliza o `praw` para buscar dados de postagens do Reddit.
   - Os textos são processados com expressões regulares.

3. **Pré-processamento**:
   - Limpeza dos textos.
   - Transformação em representações numéricas com `TfidfVectorizer`.

4. **Divisão dos dados**:
   - Separa os dados em treino e teste com `train_test_split`.

5. **Treinamento dos modelos**:
   - Modelos de classificação como Naive Bayes, Random Forest, SVM e KNN são treinados.

6. **Avaliação**:
   - Métricas como Acurácia, Matriz de Confusão e Relatórios de Classificação são exibidos.
   - Visualizações gráficas são utilizadas para comparar o desempenho.

## 📦 Bibliotecas Utilizadas

- `praw`
- `config`
- `pandas`
- `numpy`
- `scikit-learn`
- `matplotlib`
- `re`

## 📊 Resultados

Ao final, os modelos são comparados em relação à sua performance, com gráficos de barras exibindo acurácia, precisão e recall.

## 📁 Estrutura

- `Classificação_em_python.ipynb`: Notebook com todo o código e visualizações.
