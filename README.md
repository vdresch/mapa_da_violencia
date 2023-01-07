# Mapa da Violência - Porto Alegre

Mapa interativo e gratuito com os indicadores de violência para os bairros da cidade de Porto Alegre.

# Fonte dos dados

## Dados de violência:

Fonte: Secretaria da Segurança Pública do Estado do Rio Grande do Sul

Link: https://ssp.rs.gov.br/dados-abertos

## Demarcação dos bairros:

Fonte: Prefeitura de Porto Alegre

Link: http://observapoa.com.br/default.php?reg=259&p_secao=46


# Metodologia

## Processamento dos bairros

Devido à localidade da ocorrência ser preenchida de forma por extenso pela vítima no momento do boletim, há uma grande variação nos nomes dos bairros. Para resolver tal problema, é seguida uma série de regras, presentar no arquivo ```processamento.ipynb```, com o objetivo de padronizar os bairros com uma nomenclatura uniforme. Nos momentos em que isso não é possível, o registro de ocorrência é descartado.