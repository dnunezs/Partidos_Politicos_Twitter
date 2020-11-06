# Evolución de los partidos políticos en Twitter

## Contexto
En el año 2018 salta el escándalo de [Cambridge Analytica](https://www.infobae.com/america/tecno/2018/03/20/7-datos-para-entender-el-escandalo-de-facebook-y-cambridge-analytica/) por el uso de información de millones de usuarios de Facebook para crear anuncios políticos personalizados para las presidenciales de EE. UU. en 2016. Posteriores investigaciones demuestran que esta empresa había creado una maquinaria para manipular las decisiones de los votantes. [Usaba desde prostitutas o sobornos](https://www.infobae.com/america/eeuu/2018/03/19/sobornos-mujeres-y-noticias-falsas-el-ceo-de-cambridge-analytica-confeso-en-una-camara-oculta-los-metodos-que-salpican-a-facebook/) para tentar a los rivales políticos para después grabarlos, hasta la [creación de cuentas falsas](https://www.lavanguardia.com/internacional/elecciones-eeuu-2020/20201015/484092856293/twitter-cierra-cuentas-de-falsos-votantes-negros-de-trump.html) en redes sociales y la difusión de fakes news en ellas.

Lo interesante de _Cambridge Analytica_ es que hay algo mucho más grande detrás de esta empresa. A pesar de que la empresa la tuvieron que cerrar por el escándalo, sus integrantes han seguido haciendo la misma labor. Entre ellos tenemos a Steve Bannon, vicepresidente de _Cambridge Analytica_, asesor de la campaña de Trump en 2016 y director de _Breitbart_. Bannon ha declarado en [entrevistas]((https://www.eltiempo.com/mundo/eeuu-y-canada/entrevista-con-steve-bannon-sobre-el-populismo-y-el-gobierno-de-donald-trump-294662)) su deseo de crear un movimiento político populista de derechas, creó la agrupación _The Movement_ con la idea de unir a todos los partidos populistas de derechas. Ha tenido relación o ha asesorado a partidos de extremaderecha como el Frente nacional francés, Alternativo por Alemania, Liga norte en Italia o a [Vox en España](https://www.voxespana.es/noticias/bannon-el-artifice-de-la-victoria-de-trump-apuesta-por-vox-para-espana-20180410).
Es por ello, por lo que se decide indagar en las redes sociales de Vox, empezando por Twitter, ya que es una de las más fácil de manipular artificialmente sin pagar anuncios.

## Descripción
Para este primer análisis de las redes sociales de Vox vamos a usar el histórico de nuevos seguidores y seguidos. También usaremos los de los otros tres prinipales partidos españoles (PSOE, PP y Podemos) para poder comparar.
Estos datos no los podemos tomar directamente de la red social ya que solo puedes ver esos datos en tiempo real. La información se toma de [Social Blade](https://socialblade.com/), web que proporciona información de numerosas redes sociales. En ella tenemos el histórico desde 2017 (2016 en el caso de PSOE). Se utilizar web scraping para tomar los datos de la página y hacer un data set con ellos.

## Ficheros

- [**Scrap_Partidos_Politicos_Twitter.ipynb**](https://github.com/dnunezs/Partidos_Politicos_Twitter/blob/main/Scrap_Partidos_Politicos_Twitter.ipynb) Contiene el scraping de los datos y la transformación en dataset.

- [**Plot_Partidos_Politicos_Twitter.ipynb**](https://github.com/dnunezs/Partidos_Politicos_Twitter/blob/main/Plot_Partidos_Politicos_Twitter.ipynb) Contiene gráficos que ayudan a un análisis preliminar de los datos.

- [**Partidos_Politicos_Twitter.csv**](https://github.com/dnunezs/Partidos_Politicos_Twitter/blob/main/Partidos_Politicos_Twitter.csv) El data set contiene los datos semanales de los nuevos seguidores y nuevos seguidos de las cuentas oficial de Twitter de los cuatro partios (@vox_es, @podemos, @populares, @psoe) desde junio de 2016 hata octubre de 2020. En el momento del Scraping, la base tiene 228 filas.
El data set está compuesto por nueve variables: 
  - Semana que hace referencia a la fecha de los datos de las otras variables. 
  - Seguidores_partido (hay una por cada partido), que son el número de nuevos seguidores que ha conseguido el partido esa semana. 
  - Seguidos_partido (hay una por cada partido), que indica el número de cuentas nuevas que sigue al partido en Twitter. Este puede ser negativo en caso de dejar de seguir cuentas. 

## Autoría
El trabajo se ha realizado individualmente por Daniel Núñez
