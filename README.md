# Portfólio de Projetos de Ciência de Dados

Bem-vindo ao meu portfólio de projetos de ciência de dados! Este repositório apresenta uma coleção de projetos que demonstram minhas habilidades em manipulação de dados, engenharia de features, modelagem preditiva, processamento de linguagem natural (PLN) e visualização de dados. Abaixo, você encontrará uma visão geral dos projetos realizados, destacando as técnicas e abordagens utilizadas, com foco em boas práticas de ciência de dados e machine learning.

# Visão Geral

Meus projetos abordam uma ampla gama de desafios de ciência de dados, incluindo classificação, regressão, séries temporais, detecção de fraudes e análise de sentimentos. As principais ferramentas e bibliotecas utilizadas incluem Pandas, NumPy, Scikit-learn, Seaborn, Matplotlib, NLTK e SentenceTransformers, com forte ênfase em pré-processamento de dados, engenharia de features e otimização de modelos. Cada projeto segue um pipeline estruturado, desde a análise exploratória até a geração de resultados para competições ou aplicações práticas.

# Projetos
## 1. Titanic - Machine Learning

Descrição: Previsão da sobrevivência de passageiros do Titanic com base em variáveis como classe, sexo, idade, número de familiares, tarifa e títulos extraídos dos nomes.
Técnicas e Abordagens:

* Limpeza de Dados: Preenchimento de valores ausentes (ex.: idade com mediana, porto de embarque com moda).
* Engenharia de Features: Criação de variáveis como Title (extraído dos nomes) e Family_Size (soma de SibSp e Parch).
* Codificação: Uso de OneHotEncoder para variáveis categóricas (ex.: Sex, Embarked, Title).
* Modelagem: Treinamento de modelos de Regressão Logística com ajuste de hiperparâmetros via GridSearchCV (parâmetros como C, penalty, solver).
* Avaliação: Uso de métricas como acurácia, precisão, recall, F1-score e matriz de confusão.
* Resultados: Geração de previsões para submissão no Kaggle, com alinhamento de colunas entre treino e teste usando pandas.get_dummies ou OneHotEncoder.
* Ferramentas: Pandas, Scikit-learn, Seaborn, Matplotlib.

## 2. House Prices - Advanced Regression Techniques

Descrição: Previsão do valor de venda de imóveis residenciais com base em características do imóvel e do terreno (Ames Housing dataset).
Técnicas e Abordagens:

* Tratamento de Dados Faltantes: Imputação de valores numéricos (ex.: média/mediana) e categóricos (ex.: moda ou categoria específica).
* Engenharia de Features: Criação de variáveis derivadas e exclusão de colunas redundantes ou pouco informativas.
* Codificação: Aplicação de LabelEncoder para variáveis categóricas, garantindo consistência entre treino e teste.
* Modelagem: Uso de Random Forest com ajuste de hiperparâmetros via GridSearchCV (ex.: n_estimators, max_depth).
* Avaliação: Análise de métricas como RMSE, acurácia e relatório de classificação.
* Resultados: Geração de arquivo de submissão para o Kaggle.
* Ferramentas: Pandas, Scikit-learn, Seaborn, Matplotlib.

## 3. Spaceship Titanic

Descrição: Previsão do status de transporte de passageiros em uma nave espacial, com base em variáveis como Cabin, Age e outras.
Técnicas e Abordagens:

* Análise Exploratória: Visualização de padrões e tratamento de valores ausentes.
* Engenharia de Features: Decomposição da coluna Cabin em deck, num e side, codificação de variáveis categóricas com OneHotEncoder ou LabelEncoder.
* Pré-processamento: Normalização de variáveis numéricas e preenchimento de valores nulos.
* Modelagem: Treinamento de Regressão Logística com otimização via GridSearchCV.
* Avaliação: Métricas como acurácia, precisão, recall, F1-score e matriz de confusão.
* Resultados: Arquivo de submissão para o Kaggle, com alinhamento de features entre treino e teste.
* Ferramentas: Pandas, Scikit-learn, Seaborn, Matplotlib.

## 4. Store Sales - Time Series Forecasting

Descrição: Previsão de vendas futuras para lojas com base em dados históricos, feriados e características das lojas.
Técnicas e Abordagens:

* Análise Exploratória: Visualização de sazonalidades e padrões com Seaborn e Matplotlib.
* Engenharia de Features: Criação de variáveis temporais (lags, ano, mês, dia, dia da semana) e integração de dados externos (feriados, transações).
* Pré-processamento: Codificação de variáveis categóricas e preenchimento de valores ausentes.
* Modelagem: Treinamento de Regressão Linear com validação cruzada.
* Avaliação: Métricas como RMSE e R².
* Resultados: Geração de previsões para submissão.
* Ferramentas: Pandas, Scikit-learn, Seaborn, Matplotlib.

##5. Credit Card Fraud Detection

Descrição: Detecção de transações fraudulentas em cartões de crédito para o desafio Recognizance'24 (Prastuti, IIT BHU).
Técnicas e Abordagens:

* Análise Exploratória: Visualização de padrões em transações fraudulentas e não fraudulentas.
* Pré-processamento: Tratamento de valores ausentes e normalização de variáveis.
* Modelagem: Treinamento de Regressão Logística com foco em dados desbalanceados.
* Avaliação: Métricas como precisão, recall, F1-score e matriz de confusão.
* Resultados: Modelo otimizado para identificar fraudes, contribuindo para segurança financeira.
* Ferramentas: Pandas, Scikit-learn, Seaborn, Matplotlib.

## 6. Sentiment Analysis on Movie Reviews

Descrição: Análise de sentimentos em resenhas de filmes do Rotten Tomatoes, com classificação em cinco categorias.
Técnicas e Abordagens:

* Pré-processamento de Texto: Remoção de stopwords, tokenização, normalização e vetorização com TF-IDF.
* Modelagem: Treinamento de SVM com ajuste de hiperparâmetros via GridSearchCV.
* Avaliação: Métricas como acurácia, precisão, recall e matriz de confusão.
* Resultados: Geração de arquivo de submissão com previsões.
* Ferramentas: Pandas, Scikit-learn, NLTK, Seaborn.

## 7. Uber Data Analysis

Descrição: Análise exploratória e previsão de demanda por corridas da Uber.
Técnicas e Abordagens:

* Análise Exploratória: Identificação de tendências, sazonalidades e correlações.
* Engenharia de Features: Criação de variáveis como tempo de viagem e distância.
* Modelagem: Treinamento de modelos de regressão com validação cruzada.
* Avaliação: Métricas como RMSE e R².
* Resultados: Visualizações e insights para otimização de demanda.
* Ferramentas: Pandas, Scikit-learn, Seaborn, Matplotlib.

## 8. Análise de Sentimento (Português)

Descrição: Classificação de emoções em frases em português usando técnicas de PLN.
Técnicas e Abordagens:

* Pré-processamento de Texto: Remoção de stopwords, pontuação, normalização e vetorização com TF-IDF.
* Modelagem: Treinamento de Naive Bayes com divisão de dados em treino/teste.
* Avaliação: Métricas como acurácia, precisão e recall.
* Resultados: Modelo capaz de identificar emoções em textos.
* Ferramentas: Pandas, Scikit-learn, NLTK.
  
### Ferramentas e Bibliotecas
* Linguagem: Python
* Bibliotecas: Manipulação de Dados: Pandas, NumPy
* Visualização: Seaborn, Matplotlib
* Machine Learning: Scikit-learn
* Processamento de Linguagem Natural: NLTK, SentenceTransformers
* Técnicas: Pré-processamento: Tratamento de valores ausentes, codificação (OneHotEncoder, LabelEncoder, TF-IDF), normalização.
* Engenharia de Features: Criação de variáveis derivadas, extração de componentes (ex.: Cabin em deck, num, side).
* Modelagem: Regressão Logística, Random Forest, SVM, Naive Bayes, Regressão Linear.
* Otimização: GridSearchCV para ajuste de hiperparâmetros.
* Avaliação: Acurácia, precisão, recall, F1-score, RMSE, R², matriz de confusão.
### Boas Práticas
* Consistência de Dados: Alinhamento de colunas entre treino e teste (ex.: uso de reindex ou OneHotEncoder com fit no treino e transform no teste).
* Depuração: Verificação de erros como ValueError (inconsistência de features), MemoryError (matrizes esparsas) e KeyError (acesso incorreto a colunas).
* Otimização de Memória: Uso de matrizes esparsas, max_features em TF-IDF e tipos de dados otimizados (ex.: float32).
* Validação: Uso de validação cruzada (cv=5) e métricas robustas para avaliar desempenho.
* Documentação: Código comentado e pipelines estruturados para reprodutibilidade.

## Como Executar
* Clone o repositório: git clone <URL_DO_REPOSITÓRIO>
* Instale as dependências: pip install -r requirements.txt
* Explore os notebooks ou scripts em Python para cada projeto, localizados nas respectivas pastas.
* Siga as instruções específicas de cada projeto (ex.: datasets necessários, disponíveis no Kaggle).

## Contato

Para dúvidas, sugestões ou colaborações, entre em contato via lucasvale1998.lv@gmail.com.

Este README reflete meu fluxo de trabalho e abordagem prática para resolver problemas de ciência de dados, com foco em organização, clareza e boas práticas. Agradeço pelo interesse no meu portfólio!

;)
