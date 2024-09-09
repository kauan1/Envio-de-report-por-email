# Automação de Envio de Relatórios

Este projeto é uma ferramenta para automatizar o envio de relatórios por e-mail. Ele foi desenvolvido com o objetivo específico de criar e enviar relatórios de fechamento de mercado com base na coleta de cotações históricas do Ibovespa e Dólar.

## Descrição

Este projeto realiza as seguintes tarefas:

1. Coleta de cotações históricas do Ibovespa e Dólar.
2. Geração de um relatório de fechamento de mercado com base nas cotações coletadas.
3. Envio automático do relatório por e-mail.

## Tecnologias Utilizadas

- **Linguagem de Programação**: Python
- **Bibliotecas**:
  - `pandas` para manipulação e análise de dados, utilizada para processar e organizar os dados coletados.
  - `matplotlib` para criação de gráficos, utilizada para visualização dos dados no relatório.
  - `mplcyberpunk` para estilização dos gráficos, utilizada para criar visuais atraentes e modernos nos gráficos gerados.
  - `pywin32` para interação com o sistema operacional Windows, usada para automação de tarefas no Windows, como envio de e-mails.
  -  `yfinance` para coleta de dados financeiros históricos, utilizada para obter cotações do Ibovespa e Dólar.
