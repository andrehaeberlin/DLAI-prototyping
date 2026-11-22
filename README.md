# DLAI-prototyping

Protótipo de dashboard em Python e Streamlit para explorar avaliações de clientes, desenvolvido como exercício de prototipagem.

## Funcionalidades

- Carregar as avaliações de `customer_reviews.csv`.
- Limpar e padronizar o texto das avaliações da coluna `SUMMARY`.
- Filtrar avaliações por produto e visualizar a média de `SENTIMENT_SCORE` em um gráfico.

## Executar localmente

Na raiz do repositório, execute:

```bash
pip install -r requirements.txt
streamlit run streamlit_app.py
```

O aplicativo utiliza as pontuações de sentimento já presentes no CSV; não realiza inferência com um modelo generativo.
