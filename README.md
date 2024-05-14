## Projeto de Antecipação de Churn em Telecomunicações

Este projeto visa a aplicação de técnicas avançadas de análise de dados e modelos preditivos para antecipar e mitigar a rotatividade de clientes em empresas de telecomunicações. A rotatividade de clientes, também conhecida como churn, é um desafio significativo em setores altamente competitivos, como telecomunicações, onde a retenção de clientes é essencial para o sucesso empresarial.

### Dataset
O dataset utilizado neste projeto foi obtido a partir do Kaggle e contém informações sobre os clientes de uma empresa de telecomunicações, incluindo serviços contratados e se o cliente cancelou o serviço (Churn).

### Objetivo
O objetivo principal deste projeto é desenvolver modelos de machine learning capazes de identificar os clientes com maior probabilidade de churn, permitindo que a empresa adote estratégias proativas de retenção e melhore a satisfação do cliente.

### Etapas do Projeto
- Exploração e Pré-processamento de Dados: Análise exploratória dos dados, tratamento de variáveis categóricas, balanceamento do dataset e escalonamento de features.

- Modelagem Preditiva: Implementação de três modelos de machine learning: K-nearest neighbors (KNN), Naive Bayes e Árvore de Decisão.

- Avaliação dos Modelos: Avaliação dos modelos com base em métricas como precisão, recall e f1-score, com foco especial no recall para a classe positiva (Churn).

- Escolha do Modelo: Seleção do modelo com melhor desempenho na previsão de churn, levando em consideração a sensibilidade (recall).

### Resultados
Após a implementação e avaliação dos modelos, o Naive Bayes foi escolhido como o modelo preferencial devido ao seu alto recall para identificação de churn.

### Próximos Passos
Os próximos passos incluem a integração do modelo selecionado em um sistema de gestão de clientes em tempo real, permitindo a identificação e ação rápida em clientes em risco de churn.
