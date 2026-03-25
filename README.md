<!-- Capa animada superior -->
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=2F2F2F&height=120&section=header" alt="Capa animada superior" width="1000" />
</p> 

# Análise e Previsão de Evasão de Clientes (Churn)

Este projeto simula um cenário real de negócio em uma empresa de telecomunicações que enfrenta alto índice de evasão de clientes (churn), impactando diretamente sua receita.

A análise foi dividida em duas etapas complementares:

- Parte 01: Análise Exploratória de Dados (EDA)  
- Parte 02: Modelagem Preditiva com Machine Learning  

O objetivo é entender os fatores que levam ao cancelamento e prever quais clientes possuem maior risco de churn.


### Problema de Negócio

A empresa enfrenta dificuldades na retenção de clientes, impactando diretamente sua receita.  
É necessário identificar padrões de evasão e antecipar quais clientes possuem maior probabilidade de cancelamento.


### Objetivo
- Identificar fatores que influenciam o churn  
- Analisar comportamento dos clientes  
- Desenvolver modelos preditivos  
- Apoiar estratégias de retenção  


### Principais Insights
- Clientes com pouco tempo de contrato possuem maior risco de churn  
- Contratos mensais apresentam maior taxa de evasão  
- Valores mensais elevados aumentam a probabilidade de cancelamento  
- Clientes sem serviços adicionais tendem a cancelar mais  
- Métodos de pagamento manuais apresentam maior risco  


### Solução Desenvolvida
O projeto foi estruturado em duas etapas complementares:
- Tratamento e preparação dos dados (ETL)  
- Análise exploratória (EDA)  
- Modelagem preditiva com Machine Learning  
- Avaliação e interpretação dos modelos  


## Parte 01 - Análise Exploratória de Dados (EDA)

### Objetivo
Identificar padrões e fatores associados à evasão de clientes.

### Etapas Realizadas

- Importação e manipulação de dados via API  
- Aplicação do processo ETL  
- Tratamento de valores ausentes  
- Padronização de variáveis  
- Criação de métricas auxiliares  
- Análise exploratória e visualizações  

### Principais Análises

- Tempo de contrato × Evasão  
- Valor mensal × Evasão  
- Total gasto × Evasão  
- Tipo de contrato × Evasão  
- Serviços adicionais × Evasão  
- Método de pagamento × Evasão  

<br>

## Parte 02 - Modelagem Preditiva

### Objetivo
Prever quais clientes possuem maior probabilidade de churn.

### Etapas Realizadas

- Preparação dos dados para modelagem  
- One-Hot Encoding  
- Normalização de variáveis  
- Divisão treino/teste  
- Treinamento de modelos  

### Modelos Aplicados

- Regressão Logística  
- KNN (K-Nearest Neighbors)  
- Árvore de Decisão  
- Random Forest  

### Avaliação

- Accuracy  
- Precision  
- Recall (principal métrica de negócio)  
- F1-Score  
- Matriz de Confusão  

### Principais Fatores de Churn

- Tempo de contrato  
- Valor mensal  
- Total gasto  
- Tipo de contrato  
- Método de pagamento  
- Serviços adicionais  
- Suporte técnico  


### Impacto de Negócio

A análise permite:

- Antecipar cancelamentos  
- Criar estratégias de retenção  
- Reduzir perdas financeiras  
- Melhorar relacionamento com clientes  


### Conclusão

Clientes com contratos curtos, altos custos mensais e menor engajamento apresentam maior risco de evasão.
O uso de modelos preditivos permite identificar esses clientes antecipadamente e agir de forma estratégica.
Este projeto demonstra um pipeline completo de dados, desde a análise exploratória até a aplicação de modelos de Machine Learning voltados ao negócio.


### Tecnologias Utilizadas

- Python  
- Pandas  
- NumPy  
- Scikit-Learn  
- Matplotlib  
- Seaborn  
- Jupyter Notebook / Google Colab


### Acesse o Projeto

-  Google Colab Parte 01: https://colab.research.google.com/drive/12JeMfRMwMzKb8XBHdacxGDFqE4xx3Ywn  
-  Google Colab Parte 02: https://colab.research.google.com/drive/16nhSM7EcqxJFzLX26P4-Hso0U1PRZT-C

-  Repositório Parte 01: https://github.com/LarisSanto/TelecomX.git
-  Repositório Parte 02: https://github.com/LarisSanto/TelecomX_Part2.git  


<br>
<br>

<!-- Capa animada inferior -->
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=2F2F2F&height=120&section=footer" alt="Capa animada inferior" width="1000" />
</p>
