# Raspador de Notícias de Telecomunicações

Este projeto é um **web scraper** que coleta as últimas notícias de telecomunicações de diferentes veículos, organiza os dados em um **DataFrame** e salva em um arquivo CSV.

## Objetivo
- Automatizar a coleta de notícias de telecom.
- Facilitar análises futuras dos títulos e links das matérias.
- Criar um arquivo organizado pronto para análise.

## Como usar
1. Clone o repositório:
   git clone https://github.com/seuusuario/raspador-telecom.git

2. Instale as bibliotecas necessárias:
   pip install -r requirements.txt

4. Execute o notebook ou script:
   python raspador_telecom.py

   O resultado será um arquivo noticias.csv com o título, link da notícia e nome do veículo que publicou.
   
## Bibliotecas utilizadas
- pandas
- requests
- BeautifulSoup4 (ou bs4)

