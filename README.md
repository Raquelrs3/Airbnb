# Projeto de Análise e Previsão Airbnb
![Rossmann_capa](https://user-images.githubusercontent.com/98356094/156845692-d2aaf2be-b4f1-43df-a7ee-2b9a719a5c80.jpeg)

Este é um projeto realizado com dados pessoais.


## 1. Problema de Negócio
Para melhor entendimento dos ganhos, percebi a necessidade de um acompanhamento real sobre as receitas e demandas na plataforma Airbnb, que não são disponíveis nos dashboards da plataforma, além de perceber que a lógica de visualização da receita muda ao longo do tempo.


## 2. Entendimento do Negócio
#### Motivação
Necessidade de um pipeline de dados e análises em tempo real

#### Causa Raiz do Problema
Acompanhamento da receita

#### Quem é o Stakeholder
Gestora do Airbnb

#### Formato da Solução
* Receitas mensais em R$, no próximo ano,
* Problema de predição,
* Time series, regressão...,
* Predições e análises acessadas via celular.
 
 
## 3. Metodologia de Desenvolvimento do Projeto
 O projeto foi desenvolvido através da técnica CRISP-DM
 * Versão END-TO_END da solução,
 * Velocidade na entrega de valor,
 * Mapeamento de todos os possíveis problems.


##### Passo 01 - Descrição dos dados: Conhecimento dos dados, tipos, métricas estatísticas para identificar outliers, analise das métricas estatísticas e ajustes em features do dataset (preenchimento de NA's).


##### Passo 02 - Feature Engineering: Desenvolvimento de mapa mental para analisar o fenômeno, as variáveis e os principais aspectos que impactam cada uma delas. 


##### Passo 03 - Filtragem dos dados: Filtragem das linhas e excluir as colunas que não são relevantes para o modelo ou não fazem parte do escopo do negócio. EX: Dias em que as lojas estavam fevhadas ou inoperantes.


##### Passo 04 - Análise Exploratória dos dados: Exploração dos dados para encontrar insights.


##### Passo 05 - Preparação dos dados: Preparação para as aplicações de modelos de machine learning.


##### Passo 06 - Seleção de Features: Seleção dos melhores atributos para treinar o modelo. Utilizamos o algoritmo Boruta para essa seleção.


##### Passo 07 - Modelagem de Machine Learning: Foram realizados testes e treinamentos de alguns modelos de machine learning, para possibilitar a comparação da performance e escolha do modelo ideal para o projeto. Foi utilizada a técnica de Cross Validation para garantir a performance real sobre os dados selecionados.


##### Passo 08 - Hyperparameter Fine Tunning: Análise pelo método Random Search, em cima do algoritmo escolhido XBoost, para escolha dos melhores valores de cada parâmetro do modelo.


##### Passo 09 - Tradução e interpretação de erros: Aqui entendemos a performance do modelo para comunicar ao CFO quanto em dinheiro o modelo retornará à empresa. Foram usadas as métricas: MAE (Mean Absolute Error), MAPE (Mean Absolute Percentage Error) e RMSE (Root Mean Squared Error).


##### Passo 10 - Deploy do modelo em produção: Publicação em um ambiente de nuvem. Foi escolhida a plataforma Heroku.


##### Passo 11 - Bot do Telegram: Aqui realizamos a criação do bot no Telegram, o qual possibilita a consulta das previsões em tempo real.


## 4. Entendendo os Dados



## 5. Principais Insights

**Hipótese 1**


**Hipótese 2**


**Hipótese 3**


## 6. Performance do Modelo


### Comparação da performance dos modelos



### Performance final do modelo escolhido após Hyperparameter Fine Tuning



## 7. Resultado Final



## - Conclusão
 
