# Projeto-Praso---ML: Previsão de Inadimplência (Praso & CIn-UFPE)

Projeto desenvolvido para a disciplina **CIN0144 - Aprendizado de Máquina e Ciência de Dados** do Centro de Informática da UFPE (CIn - UFPE).

## 🎯 Objetivo
Previsão de inadimplência de varejistas clientes da startup **Praso**, auxiliando na concessão instantânea de crédito e otimização do ciclo de caixa dos pequenos empreendedores.

O projeto avalia dois cenários de concessão:
1. **Modelo de Aplicação (Novos Clientes / Cold Start)**: Previsão com base em dados prévios de cadastro, Receita Federal, birô de crédito (Serasa) e presença digital (iFood e Google Maps).
2. **Modelo Comportamental (Clientes Recorrentes)**: Refinamento de score incorporando o histórico agregado de pedidos, pontualidade de pagamentos e tickets médios.

## 🤖 Algoritmos de Aprendizado de Máquina
Conforme especificação do projeto, serão implementados, tunados e comparados 4 algoritmos:
1. **Regressão Logística** (Baseline linear/probabilístico interpretável)
2. **K-Nearest Neighbors (KNN)** (Modelo baseado em distância)
3. **Random Forest** (Ensemble por Bagging de árvores de decisão)
4. **XGBoost** (Gradient Boosting state-of-the-art para dados tabulares)

## 📁 Estrutura de Notebooks de EDA
- `EDA_Clientes.ipynb`: Análise Exploratória e Diagnóstico do conjunto de dados cadastrais/aplicação (`credito_aplicacao_clientes_final.csv`).
- `EDA_Pedidos.ipynb`: Análise Exploratória e Diagnóstico do conjunto comportamental de transações e pagamentos (`credito_comportamental_pedidos_final.csv`).
