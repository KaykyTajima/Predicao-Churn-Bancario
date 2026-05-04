# 🏦 Projeto de Previsão de Churn Bancário

Este repositório contém uma solução de *Machine Learning* desenvolvida para o desafio de previsão de *churn* (evasão) de clientes em uma instituição financeira. O objetivo central é identificar, com antecedência, clientes com alta probabilidade de cancelar serviços, permitindo ações proativas de retenção.

## 📈 Contexto do Negócio
A retenção de clientes é um dos pilares estratégicos de instituições bancárias. Adquirir um novo cliente pode ser de **5 a 25 vezes mais caro** do que reter um cliente existente. Este projeto visa transformar dados brutos em inteligência para reduzir a evasão e otimizar estratégias de marketing direcionadas.

## 🛠 Tecnologias Utilizadas
O projeto foi desenvolvido em **Python**, utilizando o ecossistema de *Data Science*:
* **Manipulação de Dados:** `pandas`, `numpy`
* **Visualização:** `matplotlib`, `seaborn`
* **Machine Learning:** `scikit-learn` (Pipelines, ColumnTransformer, GridSearchCV)
* **Modelagem:** `Random Forest`, `KNN`, `SVC` ,`Regressão Logistica `
* **Ambiente:** Jupyter Notebook

## 🚀 Metodologia
O fluxo de trabalho foi estruturado seguindo as melhores práticas de Engenharia de Dados e *Machine Learning*:

1. **Análise Exploratória (EDA):** Investigação de padrões de comportamento entre clientes que permaneceram versus os que saíram.
2. **Pré-processamento:** Implementação de `Pipelines` para garantir a reprodutibilidade, incluindo tratamento de variáveis categóricas e numéricas com `ColumnTransformer`.
3. **Engenharia de Features:** Seleção e transformação de variáveis com maior poder preditivo.
4. **Modelagem e Validação:** Treinamento de diversos modelos com foco em métricas adequadas para dados desbalanceados (Precision-Recall, F1-Score).
5. **Ajuste de Hiperparâmetros:** Uso de `GridSearchCV` para otimização dos modelos.
