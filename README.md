# Diplomatura en Ciencia de Datos, Aprendizaje Automático y sus Aplicaciones - 2024

## Aprendizaje No Supervisado

Este repositorio contiene el material de la materia Aprendizaje No Supervisado de la Diplomatura en Ciencia de Datos, Aprendizaje Automático y sus Aplicaciones de la Facultad de Matemática, Astronomía, Física y Computación de la Universidad Nacional de Córdoba.

### Equipo Docente

- Laura Alonso Alemany
- Georgina Flesia

### Clases

| Clase | Filmina | Notebook |
|-------|---------|----------|
| 1 | [Introducción a Análisis No Supervisado](./clases/filminas/clase1_intro.pdf) | |
| 1 | [Introducción al Clustering](./clases/filminas/clase1_intro_clustering.pdf) | [FIFA 2019 - Parte 1](./clases/notebooks/ntb_clustering_1_fifa2019_Colab.ipynb) |
| 2 | [Clustering - Parte 1](./clases/filminas/clase2_clustering.pdf) y [Clustering - Parte 2](./clases/filminas/clase2_clustering2.pdf) | [FIFA 2019 - Parte 2](./clases/notebooks/ntb_clustering_2_fifa2019_Colab.ipynb) |
| 3 | [Clustering - Evaluación](./clases/filminas/clase3_evaluacion_de_clustering.pdf) | [FIFA 2019 - Parte 2](./clases/notebooks/ntb_clustering_2_fifa2019_Colab.ipynb) |
| 3 | [Embeddings](./clases/filminas/clase3_embeddings.pdf) | [FIFA 2019 - Embeddings](./clases/notebooks/ntb_embeddings_fifa2019.ipynb) |
| 4 | [Aprendizaje Semi-Supervisado](./clases/filminas/clase4_aprendizaje_semisupervisado.pdf) | [Notebook](./clases/notebooks/ntb_semisup_y_self_learning_imagen.ipynb) |
| 4 | [Reglas de Asociación](./clases/filminas/clase4_reglas_de_asociacion.pdf) | |
| 4 | [Análisis de Redes Sociales](./clases/filminas/clase4_analisis_de_redes_sociales.pdf) | |
| 4 | [Sistemas de Recomendación](./clases/filminas/clase4_sistemas_de_recomendacion.pdf) | |

### Trabajo Práctico

#### Enunciado

Utilizar la base de jugadores “female_players.csv” disponible en [la página de Kaggle](https://www.kaggle.com/datasets/stefanoleone992/fifa-23-complete-player-dataset). Consideren que en comparación con la base vista en clase, esta base no tiene los mismos jugadores (ahora mujeres 2023) y no tiene exactamente el mismo formato (a los nombres de las variables se les agregó una keyword para identificar a qué tipo de habilidad corresponde).

Con la nueva base, realizar el siguiente análisis. Notar que es más completo pero análogo al que realizamos con los datos FIFA2019 en el cursado de la materia. Realice comentarios en cada parte (verbose=True ;))

1- Análisis exploratorio inicial de la base.
2- Evaluación visual e intuitiva de a dos variables numéricas por vez. Sugerencia: hagan los scatterplots de las combinaciones de dos variables que tengan algún sentido para ustedes, porque todas las combinaciones de variables son muchas y no van a poder analizarlas como merecen.
3- Pregunta: ¿Se realizó alguna normalización o escalado de la base? ¿Por qué?
4- Aplicación de clustering para encontrar grupos de jugadoras con habilidades equivalentes, por ejemplo, jugadoras que podrían intercambiarse en el caso de una lesión o cuando una jugadora está cansada. Para esto utilice como mínimo dos técnicas de clustering: por ejemplo k-medias, DBSCAN, mezcla de Gaussianas y/o alguna jerárquica. Justifiquen por qué eligen los diferentes hiper-parámetros que se puedan elegir según el método: número de clusters, medida de distancia, criterio de aglomeración… 
5- Análisis cualitativo de los clusters encontrados. ¿Qué hay en cada cluster? ¿Son efectivamente equivalentes las jugadoras de un cluster, es decir, podrían cumplir el mismo rol en un equipo? Si se trata de clusters heterogéneos, ¿por qué razón pueden haber sido agrupadas las jugadoras del cluster? ¿Qué motiva las diferencias en tamaño?
6- Uso de alguna transformación (proyección, Embedding) para visualizar los resultados y/o usarla como preprocesado para aplicar alguna técnica de clustering.

#### Resolución

La resolución del trabajo práctico se encuentra en el siguiente [notebook](./entregables/grupal.ipynb).