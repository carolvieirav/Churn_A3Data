# Churn_A3Data

# 📉 Análise e Estratégia de Redução de Churn em Telecom

Este repositório contém a solução desenvolvida para o **Desafio Técnico de Ciência de Dados da A3Data**. O objetivo do projeto é analisar uma base de clientes de uma empresa de telecomunicações, entender os motores do cancelamento (churn) e propor estratégias acionáveis de retenção.

## 🎯 O Problema de Negócio
A empresa de telecomunicações enfrenta um cenário de churn elevado. Uma uma vez que estamos falando de um produto
com custo elevado de setup (instalação), a empresa gostaria de uma estratégia para reduzir esse churn.

## 🧠 Abordagem e Metodologia
Em vez de focar apenas em métricas estatísticas isoladas, este projeto adota uma abordagem orientada a impacto:
1. **Análise Exploratória Rápida (EDA):** Uso de segmentação baseada em árvores de decisão para encontrar os "bolsões de churn" de forma objetiva.
2. **Priorização por Receita em Risco:** Cruzamento da taxa de churn com a receita mensal recorrente dos segmentos para priorizar os esforços de retenção.
3. **Geração de Hipóteses (Ações):** Formulação de ações preventivas tratadas como hipóteses de negócio (Testes A/B), mitigando o viés de confundir correlação com causalidade nos dados observacionais.

## 📁 Estrutura do Repositório
* `01_EDA_churn.ipynb`: Notebook principal contendo a Análise Exploratória de Dados, limpeza, segmentação e conclusões lógicas.
* `Customer-Churn.csv`: Base de dados original utilizada na análise.
* `Churn_A3Data.pptx`: Arquivo com a apresentação executiva dos resultados.
