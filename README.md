# Regressão Linear – House Prices
Este projeto tem como objetivo consolidar os conhecimentos adquiridos em regressão linear aplicada a dados reais, utilizando a base House Prices, disponibilizada pelo Kaggle.

# Objetivo 
Construir um modelo de regressão capaz de prever o valor de venda de imóveis, identificando os principais fatores que influenciam o preço e avaliando o desempenho do modelo por meio de métricas estatísticas.

# Etapas do Projeto
- Análise exploratória dos dados (EDA)
- Tratamento de valores ausentes
- Separação de variáveis numéricas e categóricas
- Pré-processamento com:
- StandardScaler para variáveis numéricas
- OneHotEncoder para variáveis categóricas
- Construção de pipeline com ColumnTransformer
- Treinamento do modelo utilizando Regressão Lasso (regularização L1)
- Ajuste de hiperparâmetros com GridSearchCV
- Avaliação do modelo utilizando R²
- Comparação com modelo baseline (DummyRegressor)

# Resultados
O modelo final apresentou desempenho superior ao baseline, demonstrando capacidade de capturar padrões relevantes nos dados.
A utilização da regularização L1 (Lasso) contribuiu para a redução de overfitting e para a seleção automática das variáveis mais relevantes, tornando o modelo mais interpretável.

# Tecnologias Utilizadas
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib / Seaborn