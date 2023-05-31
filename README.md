# Soybean
##### Collect data from twitter posts 

# Installation

Tested in Python v3.9.16

How to setup the project?

```sh
"Crie um arquivo .env na raiz do repositório
com as sequintes envs (informações da sua conta do twitter)":
twitter_email= ''
twitter_username= ''
twitter_passwd= ''
*** coloque suas informações dentro das aspas simples
```
```sh
python -m venv .venv
```
```sh
source .venv/bin/activate
```
```sh
pip install -r requeriments.txt
```
```sh
rode o script "main_selenium.py"
```
```sh
O arquivo main_selenium.py faz o trabalho da coleta de informações do twitter e gera um json ("scrapper_soybean_twitter")
Com isso usamos o arquivo treat_json.ipynb para realizar o tratamento do texto extraído
Com os dados tratados, usamos o treat_json para inserir os dados no banco Azure
