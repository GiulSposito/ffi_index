# ffi_index
Relação dos Fundos de Investimentos Imobiliários raspados (scrapped) do site FIIs ([https://fiis.com.br/])

## Origem
Dados dos FIIs estão públicos foram obtidos através da página [https://fiis.com.br/lupa-de-fiis/]

## Arquivos
Dois arquivos estão disponíveis em formato CSV
+ **col_dict.csv**: contendo o dicionário das colunas
+ **fii_index.csv**: contendo as informações sobre os FIIs

## Observações
+ Última atualização: 18/03/2020
+ O formato CSV está utilizando 
 + Primeira linha como header
 + "," (vírgula) como separador de coluna
 + "." (ponto) como separador decimal
 + Strings sem " ou ' (áspas ou apóstrofe) 
 + Datas no formato AAAA-MM-DD
 + Há acentos e o formato é UTF-8