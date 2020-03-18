# ffi_index

Relação dos Fundos de Investimentos Imobiliários raspados (scrapped) do site FIIs ([https://fiis.com.br/])

## Origem

Dados dos FIIs estão públicos foram obtidos através da página [https://fiis.com.br/lupa-de-fiis/]

## Arquivos

Dois arquivos estão disponíveis em formato CSV
+ **col_dict.csv**: contendo o dicionário das colunas
+ **fii_index.csv**: contendo as informações sobre os FIIs

## Formato

O conteúdo do índice de FIIs (fii_index.csv)

|title               |data             |type      |
|:-------------------|:----------------|:---------|
|Ticker              |codneg           |character |
|Público Alvo        |iq               |factor    |
|Tipo de FII         |tipo             |factor    |
|Administrador       |adm              |character |
|Último Rend. (R$)   |urendrs          |numeric   |
|Último Rend. (%)    |urendpercent     |numeric   |
|Data Pagamento      |urenddatapag     |Date      |
|Data Base           |urenddatabase    |Date      |
|Rend. Méd. 12m (R$) |rendmed12rs      |numeric   |
|Rend. Méd. 12m (%)  |rendmed12percent |numeric   |
|Patrimônio/Cota     |ppc              |numeric   |
|Cotação/VP          |cvp              |numeric   |
|Nº negócios/mês     |nnegmed          |integer   |
|Partic. IFIX        |ifix             |numeric   |
|Número Cotistas     |ncotistas        |integer   |
|Patrimônio          |patrimonio       |numeric   |

O formato CSV está utilizando:

+ Primeira linha como header
+ "," (vírgula) como separador de coluna
+ "." (ponto) como separador decimal
+ Strings sem " ou ' (áspas ou apóstrofe) 
+ Datas no formato AAAA-MM-DD
+ Há acentos e o formato é UTF-8
