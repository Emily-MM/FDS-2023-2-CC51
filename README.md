# FDS-2023-2-CC51
# Objetivo 

El objetivo de nuestro proyecto es analizar datos acerca de videos en tendencia de Youtube que provienen del país de México. La finalidad de este es utilizar la metodología CRISP-DM para poder analizar los datos y crear conocimiento.
Para lograr esto primero necesitamos pre-procesar y procesar los datos para garantizar su calidad. Segundo, necesitamos saber la distribución de los estados en donde los videos tienen mayor número de vistas, me gustas y no me gustas. Además, de saber los canales que cuentan con la mayor cantidad de videos tendencia.

# Integrantes
1.  Achin Angeles, Luciano Valentino (U202113624)
2.  Estrada Fernández, Sara Gabriela (U20211A109)
3.  Mendoza Manrique, Emily (U202122644)
4.  Tapia Pescoran, Andrea Katherina (U202120058)

## Descripcion del conjunto de datos

En el presente trabajo, se pidió realizar el análisis del conjunto de datos "Tendencias de las estadísticas de videos de YouTube" de Mexico de la organizacion Kaggle en el 2019.

Los datos completos nos muestran 44043 videos todos basados en Mexico pero de diferentes canales y categorías. Esta data contiene 19 campos como lo son:

1.  video_id: String
2.  trending_date: Datetime
3.  title:String
4.  channel_title: string
5.  publish_title: Datetime
6.  tags:String
7.  views: Int
8.  likes:Int
9.  dislikes: Int
10.  comment_count: Int
11.  thumbnail_link:String
12.  comments_disabled:Bool
13.  ratings_disabled:Bool
14.  video_error_or_removed:Bool
15.  description:String
16.  state:string
17.  lat:Int
18.  lon:Int
19.  geometry:String

## Conclusiones
Según las gráficas que hemos desarrollado podemos concluir que:

* Al analizar los datos por categoría encontramos que la categoría con más videos en tendencia es la categoría 24 de entretenimiento. Además, la categoría con la mayor cantidad de 'Me Gusta' es la categoría 10 de música y la categoría con la menor cantidad es la categoría 43 'shows'.Por último, la categoría con la mejor proporción de me gusta/no me gusta es la categoría 43 y la categoría con mejor proporción vistas/comentarios es la categoría 15.
* Si analizamos cómo ha cambiado el volumen de videos a lo largo de los años podemos ver que hubo un gran decremento de videos en tendencia entre el 2006 y el 2008, en donde hubo menos de 170 videos en tendencia.
* Al analizar los canales podemos ver que los canales que están mayormente en tendencia son Cracks y Badabun. Mientras que los canales que son tendencia con menos frecuencia son Los Perms RoberT J. Miller, Fox News Channel, Enigmatika Visión, odisseomx, Vik Moto TV, EVANHD, Las Tepidol, MUJER LUNA BELLA y Magnus Mefisto.
* Si analizamos por estados se sabe que el estado de Coahuila tiene la mayor cantidad de videos vistos con más de 600  millones. El estado Coahuila tiene la mayor cantidad de 'Me Gusta' con más de 30 millones. Por último, el estado que tiene la mayor cantidad de 'No Me Gusta' es Veracruz con más de 2 millones.
* Al analizar los títulos en los videos podemos afirmar que la mayoría de vídeos cuentan con títulos neutrales y sólo el 8,63% tiene títulos positivos.
* Utilizando el modelo de regresión logística podemos afirmar que en el caso de los likes y dislikes el modelo no puede predecir exactamente cuantos likes o dislikes va tener un video. Sin embargo, en el caso de los views el modelo si los puede predecir con más precisión.

## License
Kaggle. (2019, 3 junio). Trending YouTube video statistics. Recuperado el 15 de noviembre del 2023. https://www.kaggle.com/datasets/datasnaek/youtube-new 

