#  Monitoramento de Notícias

## Descrição
Este script em Python monitora as notícias mais recentes do Google News e envia as manchetes para um chat do Telegram. Utiliza a biblioteca `requests` para fazer requisições HTTP, `BeautifulSoup` para fazer parsing do HTML e `time` para controlar o intervalo entre as verificações.

## Pré-requisitos
- Python 3.x
- Bibliotecas:
  - `requests`
  - `beautifulsoup4`
  
Você pode instalar as bibliotecas necessárias usando pip:
```bash
pip install requests beautifulsoup4