# ETL-Ibovespa


Séries historicas Ibovespa

coleta de dados via txt disponibilizado na bovespa

analise layout dos txts, também disponibilizado no site da bovespa

desprezamos o header e lemos o registro de cotação

Filtramos um tipo de dado, ações 02 LOTE PADRAO

ajustes de campos numericos, data e inteiros

transformação em um script automatizado para ler todos os anos informados (cada arquivo gerado do bovespa se refere a um ano)

juntando todos os dados, de todos os anos informados, em um arquivo só


link para download dos arquivos csv:
https://www.b3.com.br/pt_br/market-data-e-indices/servicos-de-dados/market-data/historico/mercado-a-vista/series-historicas/

layout:
https://www.b3.com.br/data/files/33/67/B9/50/D84057102C784E47AC094EA8/SeriesHistoricas_Layout.pdf
