# Proyecto_Arraigo_Recomender_System

![cabecera](https://github.com/BeaZatarain/Proyecto_Arraigo_Recomender_System/blob/main/images/cabecera_readme.png)


## Descripción general:

Este proyecto resulta de la colaboración real con la Asociación **Proyecto Arraigo** cuyo objetivo principal consiste en dar apoyo técnico a su proceso del dato para poder tomar decisiones informadas. 

La misión de Proyecto Arraigo escontribuir a dar vida a los pueblos a través de una repoblación sostenible acompañando a familias y personas con ilusión por realizar un cambio de vida al mundo rural y con un proyecto de vida que les permita realizar este cambio mientras contribuyen a aportar valor al territorio. Con ello, debido a la implementación del trabajo en remoto, el COVID y el aumento del coste que conlleva vivir en grandes ciudades, han tenido un gran aumento en la demanda de solicitudes lo que ha propiciado encontrarse con grandes dificultades en el manejo de la información que reciben y, como consecuencia directa, sus procesos internos se han visto afectados.

En este sentido, se ha profundizado sobre todo en su proceso de recopilación, transformación y conservación del dato para detectar puntos de mejora y, por otro lado, proporcionarles una herramienta de visualización para poder manejar mejor la información con la que cuentan.

En términos generales, el proyecto se ha basado en realizar un proceso de limpieza y transformación del dato con **Python** y la creación de un dashboard o cuadro de mando con **Power BI**.


## Desarrollo del proyecto:

### Exploración de los datos y unificación de los mismos:

El punto de partida de este proyecto es un documento CSV con el histórico de solicitudes que ha recibido esta Asociación desde que inició su misión en mayo de 2020. Este consiste en una recopilación de formularios que rellena la gente cuando se plantea mudadarse al mundo rural. 

Sin embargo, este sistema de recopilación de datos, si bien puede ser una forma ideal para el proyecto a priori, en nuestro caso, nos hemos encontrado con cambios que se han realizado a lo largo del tiempo (preguntas nuevas, respuestas cerradas o abiertas...) sin llevar a cabo una posterior migración de datos para conservar la coherencia del dato. 

Por tanto, el primer reto de este proyecto ha sido realizar un proceso de exploración de los datos y por razones de tiempo, especificar con el cliente qué columnas o preguntas son más prioritarias para sus procesos y enfocar la homogeneización del dato a las mismas para poder tener datos consistentes de cara a posteriores análisis y el objetivo del proyecto. 

Todo este proceso se ha llevado a cabo con Python en distintos Jupyter Notebooks (Arraigo_ETL1, Arraigo_ETL2 y Arraigo_ETL3).

### Creación de Dashboard con Power BI: 

Una vez contabamos con los datos limpios y consistentes y tras especificar con el cliente los principales KPIs y la información principal que deseaban visualizar se tomó la decisión de crear un cuadro de mando en Power BI, dado que permite un mejor enfoque de negocio. 

Con ello, creamos una Dataframe específico a partir de los datos limpios, modificando el tipo de dato de algunas columnas para optimizar la posible visualización. 

El resultado del cuadro de mando se puede ver en el siguiente video: 

<video src="./images/prueba3.mp4" width="320" height="240" controls>
  Tu navegador no soporta la etiqueta video.
</video>








## Futuros pasos:

Dado que este proyecto se ha tenido que realizar en el plazo de dos semanas al tratarse del proyecto final de mi paso por el Bootcamp de Data en Ironhack, el objetivo del proyecto se ha centrado en intentar dar solución a los problemas prioritarios del cliente. Sin embargo, con el fin de poder dar una solución más efectiva, se plantean los siguientes retos: 

  1. Establecer y concretar la mejor forma de respuesta a las preguntas del cuestionario para tener un sistema de recopilación del dato   sostenible a largo plazo. 
  2. Continuar con el proceso de limpieza y unificación de los datos históricos. 
  3. Creación de una Base de Datos consistente. 
  4. Alimentar el cuadro de mando con la nueva información y posibles futuros enfoques. 
  5. Como valor añadido, crear un modelo de predicción de la demanda para poder plantear escenarios de actuación en el futuro y mejorar la organización interna de recursos. 






