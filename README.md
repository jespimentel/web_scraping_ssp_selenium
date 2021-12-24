# Raspagem de dados da SPP e análise dos dados obtidos
## Polícia Civil de Piracicaba
## Período: de 2010 a 2021 (não foram computados os dados de Dezembro).

### scraping_SSP_com_selenium.ipynb
- O projeto faz uso do Python e do Selenium para obter os dados da produtividade da Polícia Civil de Piracicaba, percorrendo o site da SSP/SP (https://www.ssp.sp.gov.br/Estatistica/Pesquisa.aspx), pelos anos de 2010 a 2021 e delegacias de polícia do Município.
- Os dataframes gerados em cada página são adicionados a uma lista de resultados (append) e concatenados em um único dataframe (concat), que é gravado como arquivo ‘csv’, aqui disponibilizado.

### policia_civil_piracicaba.ipynb
- A análise dos dados ficou restrita aos flagrantes lavrados e inquéritos policiais instaurados, por ano e Delegacia, com uso de groupby. Os resultados foram plotados. 

### Obs.: 
Os dados reunidos no arquivo csv foram usados para gerar as visualizações em Flourush Studio:

https://public.flourish.studio/visualisation/8217108/

<div class="flourish-embed flourish-hierarchy" data-src="visualisation/8217108"><script src="https://public.flourish.studio/resources/embed.js"></script></div>

https://public.flourish.studio/visualisation/8217172/

<div class="flourish-embed flourish-hierarchy" data-src="visualisation/8217172"><script src="https://public.flourish.studio/resources/embed.js"></script></div>
