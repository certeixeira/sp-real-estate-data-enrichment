# Projeto de Extração e Enriquecimento de Dados Imobiliários de São Paulo

Este projeto extrai e processa dados detalhados sobre transações imobiliárias na cidade de São Paulo em 2023, utilizando uma planilha disponibilizada pela Prefeitura. Os dados incluem informações como identificação do imóvel, valores financeiros, características físicas e mais.

## Funcionalidades

- **Extração de Dados**: Utiliza a biblioteca Pandas para ler e combinar múltiplas abas de uma planilha Excel.
- **Limpeza e Processamento**: Realiza ajustes nos dados, como formatação de CEPs e renomeação de colunas.
- **Enriquecimento de Dados**: Conecta-se a uma API para obter informações adicionais com base nos CEPs.
- **Análise e Mapeamento**: Inclui exemplos de análise, como mapeamento de zonas da cidade com base nos CEPs.
- **Exportação de Dados**: Salva os dados processados em um arquivo CSV para análises futuras.

## Uso

1. **Pré-requisitos**: Instale as bibliotecas necessárias usando `pip install pandas requests tqdm openpyxl`.

## Resultado

Deixei o dataset resultante desse projeto disponível para download no [Kaggle](https://www.kaggle.com/datasets/balkry/2023-so-paulo-real-estate-transactions-data/data)

## Contribuições

Contribuições são bem-vindas! Sinta-se à vontade para melhorar o código, adicionar novas funcionalidades ou relatar problemas através de pull requests e issues.

