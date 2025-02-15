# ETL-BOVESPA


Séries historicas da BOVESPA

coleta de dados via txt disponibilizado na bovespa

analise layout dos txts, também disponibilizado no site da bovespa

desprezamos o header e lemos o registro de cotação

Filtramos um tipo de dado, ações 02 LOTE PADRAO

ajustes de campos numericos, data e inteiros

transformação em um script automatizado para ler todos os anos informados (cada arquivo gerado do bovespa se refere a um ano)

juntando todos os dados, de todos os anos informados, em um arquivo só
