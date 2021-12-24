# Raspagem de dados da SPP (Python e Selenium) e análise dos dados obtidos (Pandas)
## Polícia Civil de Piracicaba: de 2010 a 2021 (não foram computados os dados de Dezembro)

### scraping_SSP_com_selenium.ipynb
- O projeto faz uso do Python e do Selenium para obter os dados da produtividade da Polícia Civil de Piracicaba, percorrendo o site da SSP/SP (https://www.ssp.sp.gov.br/Estatistica/Pesquisa.aspx), pelos anos de 2010 a 2021 e delegacias de polícia do Município.
- Os dataframes gerados em cada página são adicionados a uma lista de resultados (append) e concatenados em um único dataframe (concat), que é gravado como arquivo ‘csv’, aqui disponibilizado.

### policia_civil_piracicaba.ipynb
- A análise dos dados ficou restrita aos flagrantes lavrados e inquéritos policiais instaurados, por ano e Delegacia, com uso de groupby. Os resultados foram plotados. 

### Obs.: 
Os dados reunidos no arquivo csv foram usados para gerar as visualizações em Flourish Studio:

https://public.flourish.studio/visualisation/8217108/


https://public.flourish.studio/visualisation/8217172/
