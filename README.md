# IMDb Movie Scraper

Este é um script Python desenvolvido como parte do curso de Backend Python da EBAC. O script é projetado para extrair informações sobre os filmes mais populares no IMDb, incluindo título, ano de lançamento, classificação e sinopse.

## Requisitos

Certifique-se de ter os seguintes pacotes instalados antes de executar o script:

```bash
pip install requests
pip install beautifulsoup4
```

## Como Usar

1. Clone o repositório para o seu ambiente local:

```bash
git clone https://github.com/tjthiagocosta/python-imdb-movies.git
cd python-imdb-movies
```

2. Execute o script Python:

```bash
python script.py
```

O script buscará automaticamente os 100 filmes mais populares no IMDb e extrairá informações relevantes, armazenando os dados em um arquivo CSV chamado `movies.csv`.

## Configuração

O número de threads pode ser ajustado alterando a constante MAX_THREADS por padrão esse número é 20.

```python
MAX_THREADS = n_threads
```

Substitua `n_threads` pelo número desejado.

## Notas Importantes

- O script utiliza threads para acelerar o processo de scraping, por padrão 20 threads simultâneas. Isso pode ser ajustado conforme necessário.
- Certifique-se de estar em conformidade com as políticas do site ao realizar scraping.

## Contribuições

Contribuições são bem-vindas! Sinta-se à vontade para abrir problemas ou enviar pull requests para melhorar o script.

---

**Aviso:** Este script é apenas para fins educacionais e de aprendizado. O uso indevido do script para scraping pode violar os Termos de Serviço de alguns sites. Certifique-se de entender e cumprir os Termos de Serviço do site que você está segmentando.