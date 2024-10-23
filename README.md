# Projeto de Previsão de Resultados do Futebol Brasileiro - Serie A 2024

Este projeto utiliza técnicas de **web scraping** e manipulação de dados para criar uma base de dados própria do futebol brasileiro, com o objetivo de prever resultados futuros das partidas.

## Sumário

- [Descrição do Projeto](#descrição-do-projeto)
- [Tecnologias Utilizadas](#tecnologias-utilizadas)
- [Metodologia](#metodologia)
  - [Web Scraping](#web-scraping)
  - [Manipulação de Dados](#manipulação-de-dados)
  - [Previsão de Resultados](#previsão-de-resultados)
- [Fatores Considerados](#fatores-considerados)
- [Exclusões](#exclusões)
- [Como Executar o Projeto](#como-executar-o-projeto)
- [Licença](#licença)

## Descrição do Projeto

Este projeto visa prever a quantidade de gols que um time fará em uma partida, utilizando apenas as médias de gols feitos e sofridos, sem recorrer a modelos complexos como regressões lineares ou logísticas. 

## Tecnologias Utilizadas

- Python
- Bibliotecas de web scraping (ex: BeautifulSoup, Scrapy)
- Bibliotecas de manipulação de dados (ex: Pandas, NumPy)

## Metodologia

### Web Scraping

Realiza a extração de dados relevantes de sites de futebol, coletando informações sobre partidas, times e estatísticas.

### Manipulação de Dados

Os dados extraídos são tratados e organizados em uma base de dados estruturada, que permite fácil acesso e análise.

### Previsão de Resultados

A previsão dos resultados é baseada em médias de gols, considerando as seguintes variáveis:

- Gols feitos
- Gols sofridos

## Fatores Considerados

- **Fator Grandeza**: Os 20 times foram classificados em três grupos com base em seus títulos nacionais:
  - Pequeno
  - Médio
  - Grande
  
- **Posição Atual**: A posição do time no campeonato é levada em consideração para a análise.

- **Últimos 5 Jogos**: O desempenho nos últimos cinco jogos do Brasileirão também é avaliado.

## Exclusões

Optou-se por não incluir o fator de participação em outras competições, pois sua influência pode ser variável e não necessariamente indicativa dos resultados futuros.

## Como Executar o Projeto

Para executar o projeto, acesse o link abaixo

https://colab.research.google.com/drive/1ejh-lpuUArWKkyKR019AX_9TVEpIAx6e?usp=sharing
