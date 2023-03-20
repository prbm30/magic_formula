# Magic Formula B3

![Screenshot from 2023-03-20 08-53-54](https://user-images.githubusercontent.com/115738292/226344990-019e5ff1-e7b0-4bf5-8678-6b34e2f64010.png)

<p>
Essa aplicação realiza web scraping de um banco de dados da bolsa brasileira para analisar todas as empresas, tratando os dados com Pandas, aplicando a "Magic Formula" e criando uma tabela com o resultado. Por final essa tabela é convertida em HTML, estilizada, e enviada por email com mais algumas informações.


A "Magic Formula" é uma técnica introduzida pelo investidor Joel Greenblatt que consiste na criação de um ranking com as melhores empresas da bolsa de acordo com dois critérios, sendo um de valor (EV/EBIT) e outro de rentabilidade (ROIC). O ranking final é a soma de suas pontuações em cada critério.

Esta aplicação foi feita com Jupyter Notebook, utilizando as bibliotecas Pandas (dados), Selenium (web scraping), Yahoo Finance (cotações) e smtplib (email).
  
Para enviar o email é preciso utililizar uma "senha de app" do gmail, que você precisa criar para sua conta, conforme o tutorial a seguir:
https://support.google.com/mail/answer/185833
</p>

## Requirements

```sh
pip install -r requirements.txt
```
