# Proyecto de Análisis de Opiniones y Recomendaciones en Yelp y Google Maps

## Descripción del Proyecto

Este proyecto se centra en el análisis de opiniones y recomendaciones de usuarios en las plataformas Yelp y Google Maps, con el objetivo de proporcionar información valiosa para la toma de decisiones estratégicas en el ámbito empresarial. Se utilizarán técnicas de procesamiento de lenguaje natural y aprendizaje automático para analizar las opiniones de los usuarios, identificar tendencias y patrones, y generar recomendaciones personalizadas.

El Cliente es un conglomerado de empresas de restaurantes y empresas afines

El público del software es tanto turistas como Restaurantes y afines

Para los análisis como el entrenamiento del modelo, se consierará un periodo de 3 años, desde el 2017 al 2019, además, se considerarán las 5 ciudades más turístics y el 20% de los restaurantes mejor puntuados, ésto aplicando la ley de paretto.

## Objetivos del Proyecto

 Recopilación y depuración de datos: Se extraerán datos de las plataformas Yelp y Google Maps, se depurarán y se almacenarán en una base de datos para su posterior análisis.

- Análisis de sentimientos: Se analizarán las opiniones de los usuarios para identificar sentimientos positivos, negativos y neutros hacia los negocios y establecimientos analizados.
- Identificación de tendencias: Se utilizarán técnicas de análisis de datos para identificar tendencias y patrones en las opiniones de los usuarios, lo que permitirá a las empresas comprender mejor las necesidades y preferencias de sus clientes.
- Desarrollo de un sistema de recomendación: Se desarrollará un sistema de recomendación basado en las opiniones de los usuarios, que permitirá a los usuarios descubrir nuevos negocios y establecimientos en función de sus preferencias y experiencias pasadas.
- Predecir los rubros con más crecimiento o decaimiento en un periodo futuro.
- Identificar puntos clave para la instalación de nuevos locales.
- Creación de un sistema de recomendación de restaurantes según gustos u otra información.
- Agregar por lo menos 1 objetivo adicional luego de analizar los datos.

## Tecnologías Utilizadas

- Python: Se utilizará Python como lenguaje de programación principal, junto con las bibliotecas Pandas, NumPy y Scikit-learn para el análisis de datos y el desarrollo de modelos de aprendizaje automático.
- SQL: Se utilizará SQL para la gestión y manipulación de la base de datos que almacenará los datos recopilados de Yelp y Google Maps.
- Herramientas de visualización: Se utilizarán herramientas de visualización de datos como Matplotlib y Seaborn para crear visualizaciones informativas y fácilmente comprensibles.
- Otras tecnologías: Se utilizarán otras tecnologías según sea necesario para el desarrollo y despliegue del proyecto.

## Entregables

- Base de datos depurada y actualizada con datos de Yelp y Google Maps.
- Informes de análisis detallados que resuman las tendencias y patrones identificados en las opiniones de los usuarios.
- Sistema de recomendación funcional que proporcione recomendaciones personalizadas a los usuarios.
- Documentación detallada que describa el proceso de recopilación de datos, análisis realizado y funcionamiento del sistema de recomendación.

## Equipo de Trabajo

Este proyecto será desarrollado por un equipo multidisciplinario de expertos en análisis de datos, aprendizaje automático y desarrollo de software. El equipo trabajará en estrecha colaboración para garantizar la entrega de un producto de alta calidad que cumpla con los objetivos del proyecto.

<img src="images\Equipo.png" alt="Equipo de Trabajo" style="width:100%; max-width:800px;">

# Data Analytics

### Repositorio y Conjuntos de Datos

- El repositorio original del proyecto se encuentra disponible en [GitHub](https://github.com/soyHenry/PF_DS/blob/FULL-TIME/Proyectos/yelp-goople.md).

### Preprocesamiento de datos

- Se realiza la carga y limpieza de los conjuntos de datos utilizando Python y las siguientes librerías:

  - numpy
  - pandas

  puedes revisar más en detalle los pasos realizados dentro del archivo [`ETL DL.ipynb`](https://github.com/Aspirina180mg/PF_DATAPT07/blob/main/ETL.ipynb) donde preparamos los datods para insertarlos en el DataLake y luego el archivo [`ETL DW.ipynb`](https://github.com/Aspirina180mg/PF_DATAPT07/blob/main/ETL.ipynb) donde se trabaja sobre los archivos del DataLake para su inserción en el DataWarehouse

## Ciclo de vida de los datos

<img src="images/Data_lifecycle_overview.png"  alt="Ciclo de vida de los datos en general" style="width:100%; max-width:800px;">

#### Adquisición de datos:

- En esta fase, se recolectan datos de diversas fuentes, como bases de datos, APIs, entre otros. Es crucial asegurar la calidad y la integridad de los datos desde su origen.

#### Limpieza y Preprocesamiento:

- Los datos adquiridos pueden contener ruido, valores faltantes o datos inconsistentes. En esta etapa, se realiza la limpieza de los datos para eliminar errores y se lleva a cabo el preprocesamiento necesario para prepararlos para su análisis posterior.

#### Almacenamiento y Gestión:

- Los datos limpios se almacenan en una infraestructura de almacenamiento adecuada, garantizando su seguridad y accesibilidad. Además, se establecen políticas de gestión de datos para administrar el acceso, la privacidad y la seguridad de los datos.

#### Análisis Exploratorio de Datos (EDA):

- En esta fase, se exploran los datos mediante técnicas estadísticas y visuales para comprender su estructura, identificar patrones y tendencias, y detectar posibles relaciones entre las variables.

#### Modelado y Procesamiento de Datos:

- Con base en los insights obtenidos durante el análisis exploratorio, se construyen modelos predictivos o descriptivos para extraer información valiosa de los datos. Se utilizan técnicas de aprendizaje automático, minería de datos u otras metodologías.

#### Interpretación y Comunicación de Resultados:

- Los resultados del análisis y del modelado se interpretan y se comunican de manera clara y efectiva a las partes interesadas. Se presentan hallazgos importantes, conclusiones y recomendaciones que puedan derivarse del estudio de los datos.

#### Implementación y Monitoreo:

- Los modelos desarrollados se implementan en entornos de producción, donde se utilizan para tomar decisiones o automatizar procesos. Se establecen mecanismos de monitoreo continuo para evaluar el rendimiento de los modelos y garantizar su actualización y mantenimiento.

#### Retención y Eliminación:

- Se definen políticas de retención de datos para determinar cuánto tiempo se conservarán los datos y en qué condiciones. También se establecen procedimientos para la eliminación segura de los datos cuando ya no sean necesarios o relevantes.

<img src="images/Data_lifecycle_detail.png" alt="Ciclo de vida de los datos en general" style="width:100%; max-width:800px;">

## KPIs

### Fórmulas

<img src="images/KPI_formulas.png" alt="Fórmulas KPIs" style="width:100%; max-width:800px;">

## Panel de datos o Dashboard

<img src="images/Dashboard_mockup1.png" alt="Maqueta del dashboard" style="width:100%; max-width:800px;">
<img src="images/Dashboard_mockup2.png" alt="Maqueta del dashboard" style="width:100%; max-width:800px;">

El siguiente enlace lleva al dashboard interactivo: [Dashboard](https://app.powerbi.com/view?r=eyJrIjoiYzEyOTkxZWQtNzU5ZS00MzY0LTk0M2MtNWE2ODhjOTc0OWRlIiwidCI6Ijc1MDRlMzE4LThlMWUtNGQ1NS1iZmZkLTg3NWI0ZGVlODI2MCIsImMiOjR9&embedImagePlaceholder=true&pageName=c4ea6585a17c3b1d63b5)

EL archivo local se encuentra en la carpeta "Dashboard".

## Modelo de Machine Learning

### Modelo de Aprendizaje Supervisado

Se puede consultar la información entregada por el modelo en el siguiente enlace: [Streamlit](https://ptf-data-subway.streamlit.app/?id=0x865681564f2dfd47:0x1f030438f1ceed23)

![1717785299679](images/Streamlit.png)

Al seleccionar el id de restaurante en el dropdown, luego se debe dar click al enlace para visualizar la información el nuevo restaurante seleccionado

#### Objetivo

El objetivo es tomar las características de todos los restaurantes y entrenar un modelo que pueda predecir la calificación, como negativa o positiva.
En nuestro proyecto de restaurantes Subway se utiliza este modelo para poder inferir qué atributos debemos cambiar para mejorar la calificación de negativa a positiva.

#### Preprocesamiento

Se busca el promedio de calificaciones y se establece como umbral para determinar si son positivas o negativas.
Se eligen las features consideradas más representativas y con más información disponible.
Se hace un balanceo con las salidas, para que los "sí" y los "no" tengan la misma cantidad de registros en el entrenamiento.

#### Prueba de Regresores

Al ser un problema de clasificación dicotómica se prueba la eficiencia de diferentes algoritmos: `<code>`Regresión Logística, RandomForest, HistGradientBoosting, XGBClassifier, Kneighbors, GradientBoosting `</code>`; con diferentes escaladores: `<code>`StandardScaler, MaxAbsScaler, MinMaxScaler `</code>`.
Con el criterio de que la combinación de escalador y regresor que tenga más 75% de precisión se elige la combinación de ``XGBClassifier``y como regresor ``Standard Scaler``.

Mejores parámetros

```python
{'colsample_bytree': 0.85, 
'learning_rate': 0.05, 
'max_depth': 9, 
'n_estimators': 250, 
'subsample': 0.8}
```

Mejor cross-validation score: ``0.760407``

Mejor Precisión ``0.76``

Con esos parámetros entremanos el modelo y conseguimos:

    precision    recall  f1-score   support
         0         0.89      0.93      0.91      9672
         1         0.93      0.89      0.91      9906

Con una precisión de: 91 %

![1717784740704](image/Readme/1717784740704.png)

#### Implementación

Con este modelo podemos implementar una predicción, tomado un restaurante y sus características, cuáles modificar para pasar de una calificación negativa a positiva.
Enlace: [Link Streamlit](https://ptf-restaurants-ia.streamlit.app/?id=0x8869a1416d8fd145:0x5d51304c2f5b6910)

![1717784761997](image/Readme/1717784761997.png)

Clicamos sugerir, esperamos unos segundos y:

![1717784786187](image/Readme/1717784786187.png)

Aplicando las características

![1717784801655](image/Readme/1717784801655.png)

Luego Evaluamos

![1717784820526](image/Readme/1717784820526.png)

### Modelo de Clusterización

#### Objetivo

la clusterización de los restaurantes de Subway, proporciona una base sólida para tomar decisiones más informadas y estratégicas. Al entender mejor los diferentes segmentos de su mercado, Subway puede mejorar la satisfacción del cliente, optimizar sus operaciones y mantenerse competitiva en el mercado.

#### Preprocesamiento

- Se busca rellenar nulos de en las caracteristicas de los restaurantes en base a las palabras mas frecuentes en las reseñas de los mismo.
- Se crea la columna `Puntaje` en base a la cantidad de caracteristicas para agruparlos en diferentes categorías (por ejemplo, alto, medio y bajo puntaje)

#### Exploración de Variables y Algoritmos de Clustering

Probamos tratar diversa cantidad de variables, reductores de dimensionalidad y Algoritmos de Clustering a continuación dejo una lista:

* Variables: Desde variables de posición, turisticas, cantidad de reseñas, satisfaciòn de cliente, categorias, accesibilidad, ambiente, etc.

* Reductores de Dimensionalidad: Probamos con ``PCA`` (Análisis de Componentes Principales) y con ``t-SNE`` (t-distributed Stochastic Neighbor Embedding)

* Algoritmos de Clustering: Trabajamos con ``K-Means``, ``DBSCAN`` (Density-Based Spatial Clustering of Applications with Noise) y ``Agglomerative Hierarchical Clustering``

Al final Se decide que se va trabajar con las variables `Volumen de Clientes`, `Satisfacción del cliente` y `Atributos de los Restaurantes`, Sin reductores de dimensionalidades puesto que son pocas las variables y nos decidimos por el algoritmo de clusterización de `K-Means` debido a su eficiencia, su fácilidad de interpretar y escalabilidad.

#### Métricas de Evaluación

Hicimos uso del método del codo, también conocido como método de la suma de los cuadrados dentro del cluster (SSC), es importante en la clusterización porque ayuda a seleccionar el número óptimo de clusters, evita el sobreajuste, facilita la interpretación de los resultados y mejora la eficacia del modelo de clustering.

![image-2](image/Readme/image-2.png)

#### Resultados y Análisis

![image-3t](image/Readme/image-3.png)

Luego de la clusterización con `K-Means` se pueden observar claramente 4 grupos bien diferenciados.

***Conclusión General Detallada***

A continuación se presenta una conclusión más detallada basada en el análisis de los cuatro grupos de restaurantes:

- Grupo 1

*Desempeño Destacado*

Destaca en casi todas las categorías con puntajes altos en servicios, accesibilidad, comodidades, tipos de clientes, tipos de comidas, seguridad e higiene, opciones del menú, y opciones de pago. También tiene el mayor volumen de clientes y la calificación promedio más alta. Este grupo parece ser el mejor en términos generales.

Recomendaciones: Mantener y seguir mejorando en todas estas áreas clave. El enfoque podría estar en mantener la calidad y gestionar el alto volumen de clientes para asegurar una experiencia consistente.

- Grupo 3

*Alto Desempeño*

Aunque no supera al grupo 1 en la mayoría de las categorías, mantiene puntajes altos en servicios, accesibilidad, comodidades, tipos de clientes, tipos de comidas, opciones del menú, y opciones de pago. También tiene un volumen de clientes significativo y una alta calificación promedio. Este grupo es también muy fuerte, aunque no tan sobresaliente como el grupo 1.

Recomendaciones: Continuar enfocados en mantener la calidad del servicio y explorar áreas de mejora en comodidades y salud para competir aún más fuertemente con el grupo 1.

- Grupo 0

*Desempeño Intermedio*

Tiene un desempeño intermedio, con puntajes moderados en servicios, comodidades, tipos de clientes, tipos de comidas, opciones del menú, y opciones de pago. El volumen de clientes es menor comparado con los grupos 1 y 3, y su calificación promedio es más baja que la de estos grupos.

Recomendaciones: Priorizar mejoras en accesibilidad, seguridad e higiene, y comodidades. También es vital explorar formas de aumentar el volumen de clientes y mejorar la satisfacción general del cliente.

- Grupo 2

*Desempeño Bajo*

Consistentemente tiene los puntajes más bajos en todas las categorías analizadas. Tiene el volumen de clientes más bajo y una calificación promedio más baja, indicando que este grupo es el menos destacado.

Recomendaciones: Urge una revisión exhaustiva de todas las áreas. Se debe priorizar la mejora en servicios, accesibilidad, comodidades, opciones de menú, y seguridad e higiene. También es crucial aumentar el volumen de clientes y mejorar la satisfacción del cliente para evitar perder competitividad.
Conclusión Global

**Fortalezas de los Grupos 1 y 3:**

    Ambos grupos destacan en la mayoría de las categorías, con altas calificaciones y volumen de clientes.
    Estos grupos deben continuar manteniendo sus altos estándares y enfocarse en pequeñas mejoras para consolidar su posición de liderazgo.

**Áreas de Mejora para los Grupos 0 y 2:**

    Grupo 0: Aunque tiene un desempeño intermedio, necesita mejorar en accesibilidad, seguridad, higiene, y comodidades para incrementar su volumen de clientes y calificación promedio.
    Grupo 2: Requiere una transformación completa, enfocándose en todas las áreas clave para volverse competitivo.

##### Recomendaciones Generales:

    Análisis Continuo: Implementar un sistema de retroalimentación constante para identificar áreas de mejora y actuar rápidamente.
    Capacitación del Personal: Aumentar la capacitación en servicio al cliente, seguridad, y operaciones para mejorar los puntajes.
    Estrategias de Marketing: Desarrollar estrategias de marketing enfocadas para atraer más clientes, especialmente para los grupos 0 y 2.
    Inversiones en Infraestructura: Invertir en mejoras de infraestructura para aumentar las comodidades y accesibilidad, especialmente en los grupos con puntajes más bajos en estas áreas.

Este análisis detallado proporciona una hoja de ruta para que cada grupo de restaurantes entienda sus fortalezas y debilidades, permitiéndoles tomar decisiones estratégicas informadas para mejorar su desempeño y competitividad en el mercado.

## Contribuciones y Colaboraciones

Se aceptan contribuciones al proyecto, puede enviar una solicitud de extracción (pull request) o abrir un problema (issue) en el repositorio de GitHub.

## Links

Proyecto Original: https://github.com/soyHenry/PF_DS/blob/FULL-TIME/Proyectos/yelp-goople.md

Repositorio: https://github.com/Aspirina180mg/PF_DATAPT07

Seguimiento de problemas: https://github.com/Aspirina180mg/PF_DATAPT07/issues

- En caso de bugs sensibles como vulnerabilidades de seguridad, por favor
  contacte directamente al correo misagtor@gmail.com en lugar de abrir un
  problema (issue), esto para agilizar el proceso de resolución.

## Licencia

Este proyecto se distribuye bajo la [licencia MIT](https://choosealicense.com/licenses/mit/). Consulta el archivo `LICENSE.txt` para obtener más detalles.

## Contacto

Para obtener más información o realizar preguntas sobre el proyecto, puedes ponerte en contacto con los miembros del equipo:

José Alcántara

- Rol: Data Analyst
- Teléfono: +51 986 564 461
- Correo Electrónico: [jalcantara777@yahoo.com](mailto:jalcantara777@yahoo.com)
- Github: [github.com/jalcantara777](https://github.com/jalcantara777)
- LinkedIn: [linkedin.com/in/jalcantara777](https://www.linkedin.com/in/jalcantara777/)

Javier Bengolea

- Rol: Data Scientist
- Teléfono: +54 935 1211 2766
- Correo Electrónico: [javierbengolea38@gmail.com](mailto:javierbengolea38@gmail.com)
- Github: [github.com/javierbengolea](https://github.com/javierbengolea)
- LinkedIn: [linkedin.com/in/javier-bengolea](https://www.linkedin.com/in/javier-bengolea/)

Lucas Colantoni

- Rol: Data Engineer
- Teléfono: +54 934 3644 7764
- Correo Electrónico: [lucascolantoni@hotmailcom](mailto:lucascolantoni@hotmailcom)
- Github: [github.com/Lcolantoni](https://github.com/Lcolantoni)
- LinkedIn: [linkedin.com/in/lucas-colantoni-39b196153](https://www.linkedin.com/in/lucas-colantoni-39b196153/)

Misael García

- Rol: Líder de Equipo y Data Engineer
- Teléfono: +56 931 854 247
- Correo Electrónico: [misagtor@gmail.com](mailto:misagtor@gmail.com)
- Github: [github.com/Aspirina180mg/](https://github.com/Aspirina180mg/)
- LinkedIn: [linkedin.com/in/mgarciat](https://linkedin.com/in/mgarciat/)

Luca Monzón

- Rol: Data Scientist
- Teléfono: +54 911 3095 0937
- Correo Electrónico: [lucamonzon2003@gmail.com](mailto:lucamonzon2003@gmail.com)
- Github: [github.com/lucamonzon2003](https://github.com/lucamonzon2003)
- LinkedIn: [linkedin.com/in/luca-monzon-94aa31238](https://www.linkedin.com/in/luca-monzon-94aa31238/)

Leonardo Morán León

- Rol: Data Scientist
- Teléfono: +59 39 7869 3382
- Correo Electrónico: [oel.espol@gmail.com](mailto:oel.espol@gmail.com)
- Github: [github.com/LeonardoMoran19](https://github.com/LeonardoMoran19/)
- LinkedIn: [linkedin.com/in/leomleon/](https://www.linkedin.com/in/leomleon/)

## Menciones y agradecimientos

Para la realización de este proyecto se utilizaron los conocimientos adquiridos en el Bootcamp de Data Science del Equipo de "[Henry](https://web.soyhenry.com/about-us)".
