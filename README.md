# Hístorico de seguidores y seguidos de Vox en Twitter

## Contexto
En el año 2018 salta el escándalo de Cambridge Analytica por el uso de información de millones de usuarios de Facebook para crear anuncios políticos personalizados para las presidenciales de EEUU en 2016. Posteriores investigaciones demuestran que esta empresa había creado una maquinaria para manipular las decisiones de los votantes. Usaba desde prostitutas o sobornos para tentar a los rivales politicos para despues grabarlos, hasta la creación de miles de cuentas en redes sociales y la difusión de fakes news en ellas.

Lo interesante de Cambridge Analytica es que hay algo mucho mas grande detras de esta empresa. A pesar de que la empresa la tuvieron que cerrar por el escandalo, sus integrante han seguido haciendo la misma labor. Entre ellos tenemos a Steve Bannon, vicepresidente de Cambridge Analytica, asesor de la campaña de Trump en 2016 y director de Breitbart. Bannon ha declarado en numerosas entrevistas su deseo de crear un movimiento político populista de derechas, creó la agrupación The movement con la idea de unir a todos los partidos populistas de derechas. Ha tenido relación o ha asesorado a partidos de extremaderecha como el Frente nacional francés, Alternativo por Alemania, Liga norte en Italia o a Vox en España.
Es por ello que se decide indagar en las redes sociales de Vox, empezando por Twitter, ya que es una de las mas facil de manipular artifialmente sin pagar anuncios.

## Descripción
Para este primer analisis de las redes sociales de Vox vamos a usar el historico de nuevos seguidores y seguidos. Estos datos no los podemos tomar directamente de la red social ya que solo puedes ver esos datos en tiempo real. La información se toma de Social Blade, web que proporciona información de numerosas redes sociales. En ella tenemos el historico desde 2017. Se utilizar web scarping para tomar los datos de la página y hacer un data set con ellos.

## Fichero
**Scrap_Vox_Twitter.ipynb** Contiene el scraping de los datos y la tranformación en dataset.
**Plot_Vox_Twitter.ipynb** Contiene dos gráficos que ayudan al analisis de los datos
**Vox_Twitter.csv** Base con los datos extraidos
