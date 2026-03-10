# Telecom-x-Desafio-Alura

## Sobre o Projeto

Projeto de análise de dados focado em entender a evasão de clientes (Churn) de uma empresa de telecomunicações. O objetivo é identificar padrões entre os clientes que cancelam o serviço e gerar insights que possam ajudar a reduzir essa taxa.

## Dados

Os dados foram obtidos de um arquivo JSON disponível publicamente no GitHub, contendo informações sobre clientes, contratos, cobranças e serviços.

- **Fonte**: [TelecomX_Data.json](https://raw.githubusercontent.com/ingridcristh/challenge2-data-science/refs/heads/main/TelecomX_Data.json)

## O que foi feito

- Extração dos dados via API
- Limpeza e tratamento de valores ausentes e tipos incorretos
- Análise exploratória com gráficos e estatísticas
- Geração de insights e recomendações para reduzir a evasão

## Ferramentas utilizadas

- Python
- Google Colab
- Pandas
- Matplotlib
- Seaborn

## Principais descobertas

- Cerca de 26% dos clientes cancelaram o serviço
- Clientes com contrato mensal cancelam muito mais
- Clientes novos têm mais chance de sair
- Quem paga mais caro tende a cancelar mais
- Gênero não influencia na evasão

## Como rodar

1. Abra o arquivo `.ipynb` no Google Colab
2. Execute todas as células na ordem (Ambiente de execução → Executar tudo)
3. O CSV tratado será gerado automaticamente
