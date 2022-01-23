# Campeonato Brasileiro
Repositório com os códigos que criei, no processo de estudos da linguagem Python, para capturar os dados de jogos do Campeonato Brasileiro das séries A e B, disponíveis no site da CBF.

# Códigos
Foram desenvolvidos em **Python** e estão preparados para capturar os dados das temporadas finalizadas.

- **Jogos**: <a href="https://github.com/rdearruda/campeonatobrasileiro/blob/0c812319d3c3737f7f3f6b36935527544198adf1/codigo_python/Campeonato%20Brasileiro%20-%20CBF%20-%20Jogos.ipynb"> Campeonato Brasileiro - CBF - Jogos.ipynb</a>
- **Gols**: <a href="https://github.com/rdearruda/campeonatobrasileiro/blob/0c812319d3c3737f7f3f6b36935527544198adf1/codigo_python/Campeonato%20Brasileiro%20-%20CBF%20-%20Gols.ipynb"> Campeonato Brasileiro - CBF - Gols.ipynb</a>

# Dados
Os dados que são capturados pelos códigos foram armazenados em arquivos xlsx, dividios por temporadas.
A seguir os campos que estão contidos em cada arquivo

## Jogos

- **Jogos**: <a href="https://github.com/rdearruda/campeonatobrasileiro/tree/main/dados/jogos"> Dados dos Jogos </a>

|Campo|Descrição|
|----------|----------|
|Temporada|Ano da Temporada|
|Série|Indica se o jogo é da série A ou da B|
|Número do Jogo|Número do jogo|
|Rodada|Rodada do jogo|
|Turno|Indica se o jogo é do 1º ou 2º turno|
|Estádio|Estádio em que o jogo foi disputado|
|Cidade|Cidade em que o estádio está localizado|
|UF|Estado em que o estádio está localizado|
|Data|Data do jogo|
|Dia da Semana|Dia da semana em que ocorreu o jogo|
|Hora|Hora em que ocorreu o jogo|
|Mandante|Time mandante do jogo|
|UF Mandante|Estado do time mandante do jogo|
|Gol Mandante|Quantidade de gols que o mandante fez|
|Gol Visitante|Quantidade de gols que o visitante fez|
|Visitante|Time visitante do jogo|
|UF Visitante|Estado do time visitante do jogo|
|Gols no Jogo|Quantidade de gols do jogo (soma dos gols do mandante e visitante)|
|Resultado|Indica se quem venceu o jogo foi o mandante, visitante ou se ocorreu empate|
|Resultado Mandante|Indica se o mandante obteve uma vitória, empate ou derrota|
|Resultado Visitante|Indica se o visitante obteve uma vitória, empate ou derrota|
|Placar|Placar do jogo|
|Link do Jogo|Link em que os dados foram capturados|
|Data de Início da Consulta|Data e hora do início da consulta|
|Data de Fim da Consulta|Data e hora em que a consulta terminou|


## Gols

- **Gols**: <a href="https://github.com/rdearruda/campeonatobrasileiro/tree/main/dados/gols"> Dados dos Gols </a>

|Campo|Descrição|
|----------|----------|
|Temporada|Ano da Temporada|
|Série|Indica se o jogo é da série A ou da B|
|Número do Jogo|Número do jogo|
|Time|Time que fez o gol|
|Jogador|Jogador que fez o gol|
|Minuto|Minuto em que o gol ocorreu|
|Tempo|Indica se foi no 1º ou 2º tempo|
|De Quem|Indica se o gol foi do Mandante ou do Visitante|
|Data de Início da Consulta|Data e hora do início da consulta|
|Data de Fim da Consulta|Data e hora em que a consulta terminou|
