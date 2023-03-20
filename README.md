# Magic Formula B3

<p>
Essa aplicação realiza web scraping de um banco de dados da bolsa brasileira para analisar todas as empresas, tratando os dados com Pandas, aplicando a "Magic Formula" e criando uma tabela com o resultado. Por final essa tabela é convertida em HTML, estilizada, e enviada por email com mais algumas informações.


A "Magic Formula" é uma técnica introduzida pelo investidor Joel Greenblatt que consiste na criação de um ranking com as melhores empresas da bolsa de acordo com dois critérios, sendo um de valor (EV/EBIT) e outro de rentabilidade (ROIC). O ranking final é a soma de suas pontuações em cada critério.

Esta aplicação foi feita com Jupyter Notebook, utilizando as bibliotecas Pandas (dados), Selenium (web scraping), Yahoo Finance (cotações) e smtplib (email).
</p>
## Requirements

```sh
pip install -r requirements.txt
```
