### PROYECTO FINAL DE AUTOMATIZACION Y CONTROL

####Selector De CafE
####Solucion

- Nuestro software basado en Inteligencia Artificial, puede cambiar esto. Utiliza tecnología avanzada para detectar y seleccionar solo las cerezas de café rojas y maduras, dejando los granos de café sin madurar verdes.

- Los productores de café pueden aumentar la eficiencia de la recolección y mejorar la calidad del café. Esto puede llevar a un aumento en las exportaciones de café, que en 2023 se estimaron en 714.000 toneladas


![](https://museodelchocolate.com.co/wp-content/uploads/2022/10/historia-del-cafe.jpg)


####Desarrollo: herramientas utilizadas

- El desarrollo del Selector de Café comenzó con la instalación de Ultralytics, una biblioteca de Python que facilita el entrenamiento y la implementación de modelos de detección de objetos YOLO 
 
- Específicamente se uso la versión YOLOv8, que es la última versión del algoritmo YOLO. Este modelo se puede utilizar para tareas de detección de objetos, clasificación de imágenes y segmentación de instancias


- Roboflow es una plataforma que te ayuda a crear, entrenar, alojar y desplegar modelos de visión por computadora usando varias herramientas de anotación y etiquetado. Se puede usar Roboflow para etiquetar, entrenar y desplegar modelos para diversas industrias y aplicaciones,-

##pasos 
- Se invoca la biblioteca YOLO 
- Se establece la tarea: detectar
-  Se establece el parámetro para modo de entrenar
- El modelo yolov8m.pt preentrenado que se utilizará como punto de partida para el -entrenamiento.
- Se definen el número de épocas (o iteraciones completas a través del conjunto de datos de entrenamiento) que se realizarán durante el entrenamiento.


###GIT
Proyecto Plantilla Cafe

[github](https://github.com/German1999-crack/PRoyecto_Final "github")



