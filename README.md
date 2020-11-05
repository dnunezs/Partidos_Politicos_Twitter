# Evolución de Vox en Twitter

## Contexto
En el año 2018 salta el escándalo de _Cambridge Analytica_ por el uso de información de millones de usuarios de Facebook para crear anuncios políticos personalizados para las presidenciales de EE. UU. en 2016. Posteriores investigaciones demuestran que esta empresa había creado una maquinaria para manipular las decisiones de los votantes. Usaba desde prostitutas o sobornos para tentar a los rivales políticos para después grabarlos, hasta la creación de miles de cuentas en redes sociales y la difusión de fakes news en ellas.

Lo interesante de _Cambridge Analytica_ es que hay algo mucho más grande detrás de esta empresa. A pesar de que la empresa la tuvieron que cerrar por el escándalo, sus integrantes han seguido haciendo la misma labor. Entre ellos tenemos a Steve Bannon, vicepresidente de _Cambridge Analytica_, asesor de la campaña de Trump en 2016 y director de _Breitbart_. Bannon ha declarado en numerosas entrevistas su deseo de crear un movimiento político populista de derechas, creó la agrupación _The Movement_ con la idea de unir a todos los partidos populistas de derechas. Ha tenido relación o ha asesorado a partidos de extremaderecha como el Frente nacional francés, Alternativo por Alemania, Liga norte en Italia o a Vox en España.
Es por ello, por lo que se decide indagar en las redes sociales de Vox, empezando por Twitter, ya que es una de las más fácil de manipular artificialmente sin pagar anuncios.

## Descripción
Para este primer análisis de las redes sociales de Vox vamos a usar el histórico de nuevos seguidores y seguidos. Estos datos no los podemos tomar directamente de la red social ya que solo puedes ver esos datos en tiempo real. La información se toma de Social Blade, web que proporciona información de numerosas redes sociales. En ella tenemos el histórico desde 2017. Se utilizar web scraping para tomar los datos de la página y hacer un data set con ellos.

## Ficheros

- **Scrap_Vox_Twitter.ipynb** Contiene el scraping de los datos y la transformación en dataset.

- **Plot_Vox_Twitter.ipynb** Contiene dos gráficos que ayudan al análisis de los datos.

- **Vox_Twitter.csv** Base con los datos extraídos

