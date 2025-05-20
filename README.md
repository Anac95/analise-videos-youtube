# Análise de Vídeos do YouTube

Este projeto é uma análise exploratória e tratamento de dados de vídeos e comentários do YouTube, utilizando PySpark.

## Conteúdo

- `tratamento.ipynb`: Notebook com todas as etapas de leitura, limpeza, transformação e junção dos dados.
- Dados originais: arquivos CSV contendo estatísticas dos vídeos, comentários e dados de vídeos dos EUA.
- Dados tratados: arquivos no formato Parquet com dados limpos e enriquecidos.

## Objetivos

- Ler arquivos CSV e inferir esquemas.
- Tratar valores nulos e tipos dos dados.
- Criar novas colunas derivadas, como interação total e ano de publicação.
- Realizar junções entre os datasets.
- Salvar os dados tratados em formato Parquet para análises futuras.

## Tecnologias

- PySpark
- Apache Spark

## Como usar

1. Abra o notebook `tratamento.ipynb` no Jupyter Notebook ou Google Colab.
2. Execute as células sequencialmente para reproduzir a análise.
3. Ajuste os caminhos dos arquivos CSV caso necessário.

---

Projeto de estudo desenvolvido para aprimorar habilidades em análise de dados com PySpark.

