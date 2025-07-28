# machine-learning-pyspark-churn
# Classificação de Churn com PySpark

Este projeto tem como objetivo construir modelos de machine learning utilizando PySpark para prever se um cliente irá cancelar ou não um serviço (churn).

## Etapas abordadas:
- Carregamento e tratamento de dados com Spark SQL
- Criação de dummies para variáveis categóricas
- Transformações com VectorAssembler
- Construção e avaliação de modelos:
  - Regressão logística
  - Árvore de decisão
  - Random Forest
- Avaliação com MulticlassClassificationEvaluator
- Otimização com ParamGridBuilder e CrossValidator
- Seleção e aplicação do modelo final

## Tecnologias utilizadas
- Apache Spark / PySpark
- Python
- Databricks

## Execução
Recomenda-se o uso do ambiente Databricks ou um cluster local com PySpark configurado.
