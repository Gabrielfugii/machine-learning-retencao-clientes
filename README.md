# Previsão de Rotatividade e Segmentação de Clientes (Model Fitness)

Este projeto utiliza técnicas de Machine Learning para analisar o histórico de uso, engajamento e características demográficas dos clientes de uma rede de academias. O objetivo central é prever a probabilidade de cancelamento (churn) no curto prazo e segmentar a base de clientes para orientar estratégias de retenção proativas e orientadas a dados.

## Tecnologias e Bibliotecas Utilizadas
- **Linguagem:** Python
- **Manipulação e Visualização:** Pandas, Matplotlib, Seaborn
- **Machine Learning (Scikit-learn):** Regressão Logística, Random Forest, K-Means, StandardScaler
- **Estatística:** SciPy (Agrupamento hierárquico)

## Funcionalidades e Etapas da Análise
- **Análise Exploratória de Dados (EDA):** Diagnóstico inicial mapeando as distribuições estatísticas, integridade da base e correlação de variáveis com a taxa de cancelamento.
- **Aprendizado Supervisionado (Previsão):** Construção e avaliação de modelos de classificação para identificar o risco de churn de cada usuário.
- **Aprendizado Não Supervisionado (Clusterização):** Aplicação de algoritmo K-Means e dendrogramas para isolar variáveis e segmentar os clientes em nichos comportamentais.
- Geração de recomendações estratégicas acionáveis para a equipe de marketing.
