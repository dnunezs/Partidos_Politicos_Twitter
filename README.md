# Análisis de la evolución de los partidos políticos en Twitter
Queremos analizar los datos de la evolución de los seguidores y seguidos de los principales partidos politicos en España, concretamente PSOE, PP, Vox y Podemos.
Los datos no los podemos tomar directamente de la red social ya que solo puedes ver esos datos en tiempo real, pero podemos usar Web Scaping para obtener toda la información.
El scraping lo hacemos en la web [Social Blade](https://socialblade.com/), ya que proporciona información y métricas de usuarios de numerosas redes sociales, entre ellas Twitter. En ella tenemos el histórico desde 2017(2016 en el caso de PSOE) y mediante web scraping tomamos los datos de la página para hacer un dataset y analizarlo.

## Ficheros

- [**Web Scraping.ipynb**](https://github.com/dnunezs/Partidos_Politicos_Twitter/blob/main/Web%20Scraping.ipynb) Contiene el scraping de los datos y la transformación en dataset.

- [**Análisis y gráficos.ipynb**](https://github.com/dnunezs/Partidos_Politicos_Twitter/blob/main/An%C3%A1lisis%20y%20gr%C3%A1ficos.ipynb) Análisis y gráficos del dataset obtenido de la evolución de los seguidores y seguidos de los partidos políticos en España.

- [**Dataset.csv**](https://github.com/dnunezs/Partidos_Politicos_Twitter/blob/main/Dataset.csv) El dataset contiene los datos semanales de los nuevos seguidores y nuevos seguidos de las cuentas oficiales de Twitter de los cuatro principales partios españoles(@psoe, @populares, @vox_es, @podemos) desde junio de 2016 hata octubre de 2020. 
El dataset está compuesto por 9 variables: 
  - Semana: hace referencia a la fecha de los datos de las otras variables. 
  - Seguidores_partido (hay una por cada partido): número de nuevos seguidores que ha conseguido el partido esa semana. 
  - Seguidos_partido (hay una por cada partido): número de cuentas nuevas que sigue al partido en Twitter. Este puede ser negativo en caso de dejar de seguir cuentas. 

## Data set
El data set ha sido publicado en [Zanodo](https://zenodo.org/record/4247917#.X6VGJGhKhjG) bajo una licencia de Creative Commons Attribution 4.0 International con DOI 10.5281/zenodo.4247917
