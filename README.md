## 💡 Regressão • ML Pipeline Completo • Hiperparâmetros • Validação Cruzada
# 📊 Objetivo

Criar um modelo de regressão para prever o preço de automóveis com base em atributos como motor, consumo, ano, estilo etc.

# 📁 Pipeline
1. Coleta e limpeza de dados

10918 linhas → 10209 após remoção de duplicatas

Tratamento de categorias

Conversão de tipos

Exploratory Data Analysis preliminar
---
2. Modelagem

Foram testadas:

XGBRegressor (sklearn API)

XGBoost nativo com DMatrix

GridSearchCV para hiperparâmetros

Validação cruzada (k=5)

Early stopping
---
3. Melhores resultados

RMSE final: ~2912

Melhor configuração:

max_depth=3

colsample_bytree=0.6

subsample=1

learning_rate=0.3
---
4. Interpretabilidade

Feature importance

Gráficos de valores reais vs previstos
---
5. Uso do modelo

Modelo salvo com joblib

Exemplo de inferência com novos automóveis

---
