# Dashboard Netflix

## Escopo do Projeto

O projeto tem como objetivo analisar dados do catálogo da Netflix e responder três perguntas principais:

1. Quanto tempo um título demora entre seu lançamento e sua entrada na Netflix?
2. Como a duração média dos filmes varia ao longo dos anos?
3. Qual a proporção de séries com apenas uma temporada em comparação com séries que possuem duas ou mais temporadas?

## Design e Usabilidade

O dashboard foi organizado de forma simples, com os gráficos distribuídos em uma única tela para facilitar a leitura e a comparação das informações.

Foram utilizados gráficos de linha para analisar mudanças ao longo do tempo e gráfico de rosca para comparar a proporção entre séries com uma temporada e séries com duas ou mais temporadas.

## Padrão Visual

O dashboard utiliza cores inspiradas na identidade visual da Netflix, com fundo escuro, vermelho para destaque e branco e cinza para textos e informações secundárias.

## Processo de ETL

Os dados foram importados do arquivo CSV para o Excel utilizando o Power Query.

Durante o tratamento dos dados foram realizadas algumas transformações, como:

- criação do ano de entrada na Netflix a partir da coluna de data;
- cálculo do tempo entre o lançamento e a entrada na Netflix;
- conversão da duração dos filmes para minutos;
- separação das séries entre uma temporada e duas ou mais temporadas.

Depois do tratamento, os dados foram utilizados em tabelas dinâmicas para criação dos gráficos.

## Fonte de Dados

Foi utilizado o arquivo `netflix_titles.csv`, contendo informações sobre filmes e séries do catálogo da Netflix. EXTRAIDO DO KAGGLE

## Ferramentas Utilizadas

- Microsoft Excel
- Power Query
- Tabelas Dinâmicas
- GitHub

## Dashboard

O dashboard foi desenvolvido no Microsoft Excel e está disponível no arquivo `dashboard.xlsx`.
