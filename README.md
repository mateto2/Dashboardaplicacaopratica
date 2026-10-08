## Escopo do Projeto

O projeto tem como objetivo analisar dados do catálogo da Netflix e desenvolver um dashboard capaz de responder três perguntas principais:

1. **Qual é a relação entre o ano de lançamento dos títulos e o ano em que eles foram adicionados à Netflix?**

A análise buscará identificar o intervalo entre o lançamento de filmes e séries e sua entrada no catálogo da plataforma, permitindo observar se os conteúdos são adicionados próximos ao seu lançamento ou anos depois, tendo como principal analíse se os streammings diminuiram o tempo que filmes e séries demoram para ficarem disponivel para serem assistidos de casa

2. **Como a duração média dos filmes varia ao longo dos anos?**

A análise calculará a duração média dos filmes para cada ano de lançamento, permitindo observar a evolução desse indicador ao longo do tempo e verificar se existe uma tendência de aumento, estabilidade ou diminuição na duração dos filmes mais recentes.

3. **Quantas séries possuem apenas uma temporada?**

A análise identificará a quantidade de séries com somente uma temporada e sua proporção em relação ao total de séries presentes no conjunto de dados. tendo uma noção de quantos projetos são cancelados no ínicio de sua história

O dashboard será desenvolvido com foco em apresentar essas informações de forma simples, visual e objetiva, utilizando indicadores e gráficos que facilitem a interpretação dos dados e a identificação de padrões no catálogo analisado.




## Descrição do processo de ETL
Durante o processo de ETL, o arquivo netflix_titles.csv será importado e preparado para a análise no dashboard.
Serão realizadas as seguintes etapas de tratamento:
- importar o arquivo CSV para o Excel;
- verificar valores ausentes nas colunas utilizadas no projeto;
- converter a coluna date_added para um formato de data;
- criar uma nova coluna com o ano de entrada do título na Netflix;
- utilizar a coluna release_year para comparar o ano de lançamento com o ano de entrada na plataforma;
- filtrar os registros do tipo Movie;
- remover o texto " min" da coluna duration e transformar a duração dos filmes em valor numérico;
- calcular a duração média dos filmes por ano de lançamento;
- filtrar os registros do tipo TV Show;
- identificar e contar as séries cuja duração corresponde a 1 Season;
- organizar os dados tratados em tabelas e tabelas dinâmicas para alimentar os gráficos e indicadores do dashboard.
