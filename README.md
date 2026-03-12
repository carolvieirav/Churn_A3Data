# Estratégia de Redução de Churn em Telecom

Este repositório contém o plano estratégico desenvolvido para o **Desafio Técnico de Ciência de Dados da A3Data**. O objetivo central é identificar os motores do cancelamento e propor alavancas acionáveis para reter clientes de alto valor e otimizar o ROI de aquisição.

---

## O Problema de Negócio

A empresa enfrenta um cenário de **churn elevado (26,5%)** , o que é particularmente crítico para produtos com alto custo de instalação (*setup*). A evasão de clientes gera uma perda de receita recorrente mensal (MRR) estimada em **R$ 139.131,00**.

**Pergunta Central:** Como identificar os segmentos de maior risco e quais intervenções têm maior impacto na retenção? 

---

## Metodologia e Solução

O projeto adota uma abordagem orientada a impacto, estruturada em quatro pilares:

1. **Análise de Escala:** Quantificação do prejuízo financeiro e perfil de ticket médio (ARPU).


2. **Análise de Sobrevivência:** Identificação da janela crítica de 12 meses, onde **25,6% dos clientes em contratos mensais cancelam o serviço**.


3. **Feature Importance (SHAP + XGBoost):** Uso de Machine Learning (modelo com **ROC-AUC de 0,84**) para isolar os drivers que realmente explicam o churn.


4. **Alavancas de Intervenção:** Proposta de ações preventivas tratadas como hipóteses de negócio para testes A/B.


## Estrutura do Repositório

| Arquivo | Descrição |
| --- | --- |
| `eda_churn.ipynb` | Notebook com a análise exploratória completa e modelagem de importância de variáveis. |
| `Customer-Churn.xlsx` | Base de dados utilizada (7.043 clientes e 21 atributos).|
| `Churn_Apresentacao_A3Data.pdf` | Deck executivo com a síntese dos achados e estratégia sugerida .|

---

## Autora

**Ana Carolina Vieira** [LinkedIn](https://www.google.com/search?q=https://www.linkedin.com/in/carolvieirav)

---
