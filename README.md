# Sales_prediction_pharmacy_chain

#### Made by Tiago Araujo

# Descrição

O objetivo deste projeto é prever as vendas de várias lojas diferentes usando algoritmos de Machine Learning para Regressão Linear.

# 1. Problema de negócio

Uma cadeia de farmácias quer modernizar as drogarias da rede, implementando a possibilidade de tele-entrega em 100% delas. No entanto, o custo da operação é elevado e o maior desafio é saber se as lojas terão receita suficiente para realizar a reforma e ainda dar lucro.

# 2. Estratégia de solução

**Etapa 01. Descrição e limpeza dos dados:**

Os dados são da plataforma Kaggle e podem ser classificados em características das lojas, informações sobre competidores e dados sobre eventos sazonais (como promoções e feriados).
Link: https://www.kaggle.com/c/rossmann-store-sales

Objetivo: ganhar entendimento dos dados e preparar dataset para análises mais profundas.

Processo: mudança do nome e tipo de variáveis; preenchimento de dados faltantes; complilado de características de variáveis numéricas e categóricas


**Etapa 02. Feature Engineering:**

Objetivo: aumentar informações sobre os dados e facilitar a interpretação para os modelos.
Processo: transformações de variáveis temporais, indicando o tempo desde algum evento específico, e renomeio de variáveis categóricas para facilitar a interpretação na fase de EDA

**Etapa 03. Filtragem de dados:**

Objetivo: concentrar a análise dos dados que realmente importam para entender o fenômeno
Processo: seleção de dados somente quando há lojas abertas e vendas; retirada de features sem importância

**Etapa 04. Análise Exploratória:**

Objetivo: ganhar entendimento intuitivo dos dados
Processo: realizar análises uni, bi e multi variadas, entendendo a relação entre elas por meio de tabelas e gráficos

**Etapa 05. Preparação dos dados para treinamento de modelos:**

Objetivo: deixar os dados em formato compatível com o treinamento de modelos
Processo: uso de reescala, enconding e transformações de natureza (dados temporais).

**Etapa 06. Seleção de features:**

Objetivo: selecionar, com a ajuda do algoritmo Boruta, as features mais importantes para o modelo
Processo: separação de dados em treino e teste seguindo lógica temporal; uso do algoritmo Boruta e dos insights da EDA para selecionar features.

**Etapa 07. Treinamento e teste de modelos:**

Objetivo: usar vários algoritmos de regressão e avaliar os que melhor performam
Processo: aplicação dos dados de treino e teste e avaliação da performance, de acordo com as métricas de MAE, MAPE e RSME

**Etapa 08. Fine Tuning:**

Objetivo: otimizar os parâmentros do modelo para melhor a performance do modelo escolhido
Processo: uso do algoritmo random search para otimizar os parâmentros

**Etapa 09. Avaliação de performance de negócio:**

Objetivo: traduzir as métricas do modelo para a performance de negócio, servindo de base para a tomada de decisões
Processo: uso da variação de MAE como uma espécie de "intervalo de confiança" para criar cenários de negócio (pessimista, realista e otimista)




# 3. Avaliação dos modelos

# 4. Resultado de Negócio

# 5. Conclusão

# 6. Próximos passos
