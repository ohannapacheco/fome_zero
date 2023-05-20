# 1. Problema de negócio

A empresa Fome Zero é uma marketplace de restaurantes. Ou seja, seu core business é facilitar o encontro e negociações de clientes e restaurantes. Os restaurantes fazem o cadastro dentro da plataforma da Fome Zero, que disponibiliza informações como endereço, tipo de culinária servida, se possui reservas, se faz entregas e também uma nota de avaliação dos serviços e produtos do restaurante, dentre outras informações.

O CEO da empresa foi recém contratado e precisa entender melhor o negócio para conseguir tomar as melhores decisões estratégicas e alavancar ainda mais a Fome Zero. Para isso, ele precisa que seja feita uma análise nos dados da empresa e que sejam gerados dashboards, a partir dessas análises, com gráficos e tabelas que exibam as métricas da empresa da melhor forma possível

# 2. Premissas assumidas para análise

1. A análise foi realizada com dados disponíveis na plataforma do Kaggle. O link para acesso aos dados: https://www.kaggle.com/datasets/akashram/zomato-restaurants-autoupdated-dataset?resource=download&select=zomato.csv 
2. Marketplace foi o modelo de negócio assumido.
3. As quatro principais visões de negócio foram: Visão geral, visão países, visão cidades e visão tipos culinários.

# 3. Estratégia da solução

O painel estratégico foi desenvolvido utilizando as métricas que refletem as 3 principais visões do modelo de negócio da empresa:

1. Visão Geral
2. Visão Países
3. Visão Cidades
4. Visão Tipos Culinários

Cada visão é representada pelo seguinte conjunto de métricas:

### Visão Geral
  I. Número de restaurantes cadastrados.

  II. Número de países cadastrados.

  III. Número de cidades cadastradas.

  IV. Número de avaliações feitas.

  V. Número de tipos culinários oferecidos.

### Visão Países
  I. Quantidade de restaurantes registrados por país.

  II. Quantidade de cidades registradas por país.

  III. Média de avaliações feitas por país.

  VI. Média de preço do prato para duas pessoas por país.

### Visão Cidades
  I. Top 10 cidades com mais restaurantes.

  II. Top 7 cidades com mais restaurantes que tenham média de avaliação acima de 4.

  III. Top 7 cidades com mais restaurantes que tenham média de avaliação abaixo de 2,5.
  
  IV. Top 10 cidades com mais tipo culinários distintos em restaurantes.

Visão Tipos Culinários
  I. Top 10 restaurante com melhores avaliações médias.

  II. Melhores restaurantes dos principais tipos culinários.

  III. Top 10 melhores tipos culinários.

  IV. Top 10 piores tipos culinários.

# 4. Top 3 insights de dados
1. Dos 15 países cadastrados, a Austrália é o país com maior quantidade de avaliações registradas e com preço médio do prato para duas pessoas mais caro.
2. Birmingham, na Inglaterra, é a cidade com mais tipos culinários distintos.
3. O tipo culinário de menor avaliação média (1,9/5) é Tex-Mex.

# 5. O produto final do projeto
Painel online hospedado em um Cloud e disponível para acesso em qualquer dispositivo conectado à internet.
O painel pode ser acessado através deste link:  https://ohannapacheco-fome-zero.streamlit.app/ 

# 6. Conclusão
O objetivo desse projeto foi criar um conjunto de gráficos e tabelas que exibam as métricas da empresa da melhor forma possível para o CEO.

