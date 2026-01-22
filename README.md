# Santander Dev Week 2023 - ETL com Python

Este projeto implementa um fluxo ETL (Extract, Transform, Load) utilizando Python e Pandas.

Devido à indisponibilidade da API oficial do evento, os dados foram extraídos a partir de um arquivo CSV local.

## Arquivos do Projeto
- SDW2023_full.csv: base de dados de entrada
- ETL_SDW2023.ipynb: notebook com o processo ETL
- SDW2023_out.csv: arquivo final com mensagens geradas

## Etapas do ETL
- **Extract:** leitura dos dados a partir do arquivo CSV
- **Transform:** geração de mensagens personalizadas sobre investimentos
- **Load:** gravação do resultado em um novo arquivo CSV

## Como executar
1. Abra o notebook no Google Colab
2. Faça upload do arquivo SDW2023_full.csv
3. Execute as células em ordem
4. O arquivo SDW2023_out.csv será gerado
