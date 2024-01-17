# Classificador de Sentimentos com Análise de Resenhas do IMDb

***Classificador de sentimentos***
*by [Yago Pacheco](https://www.linkedin.com/in/yago-pacheco-de-aquino-958881183/)*

---

## Introdução
Este projeto tem como objetivo criar um modelo de aprendizado de máquina para analisar resenhas do IMDb e classificá-las como sentimentos positivos ou negativos. Utilizando uma base de dados do IMDb, o código realiza transformações nos dados, vetoriza as resenhas e cria um modelo base para comparação. O processo inclui a exploração dos dados através de uma nuvem de palavras, técnicas de processamento de linguagem natural (NLTK) para análise e tratamento dos dados, e a aplicação de dois algoritmos para predição: `Ngram` e `TF-IDF`.

## Funcionalidades

### Pré-processamento de Dados
- Transformação dos rótulos em números para análise do modelo.
- Vetorização e criação de uma matriz esparsa para preparação dos dados.

### Exploração de Dados
- Criação de uma nuvem de palavras para visualização das palavras mais frequentes.
- Análise e criação de um gráfico de Pareto para identificar as palavras mais relevantes.

### Tratamento de Dados com NLTK
- Remoção de pontuações, acentos, transformação de palavras para minúsculo e redução de palavras ao radical utilizando `RSLPS`.

### Algoritmos de Predição
- Utilização de dois tipos de algoritmos para a predição: `Ngram` e `TF-IDF`.
