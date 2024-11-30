## Modelado de Datos 

### Descripción del modelo 

El modelo de datos fue desarrollado como parte de un proyecto práctico realizado por estudiantes con el objetivo de analizar las cancelaciones de suscripciones en Netflix a través de una encuesta aplicada a la población de Xalapa. Los estudiantes recopilaron información relevante sobre los motivos de cancelación, la satisfacción con el servicio y los factores que influyen en la decisión de cancelar. El modelo estructurado permite identificar patrones y posibles tendencias en las cancelaciones, facilitando análisis posteriores sobre cómo mejorar la retención de usuarios.

### Proceso de Modelamiento

#### 1.	Recolección de Requisitos:

La encuesta se diseñó para entender las razones detrás de la cancelación de suscripciones en Netflix, y fue aplicada a la población de Xalapa.

Las preguntas clave de la encuesta incluyeron:
-	¿Cuánto tiempo llevaba suscrito el usuario a Netflix antes de cancelar?
-	¿Cuáles fueron los principales motivos de la cancelación (por ejemplo, precio, falta de contenido, otros servicios mejores)?
-	¿El encuestado considera que Netflix ofrecía un buen valor por el dinero?
-	¿Qué cambios harían para que el encuestado volviera a suscribirse?
-	Información demográfica como edad, género, ingresos, etc.

#### 2.	Diseño Conceptual:

Se identificaron las principales entidades relacionadas con la encuesta:
-	Encuestado: Información del usuario (Edad, Género, Ingresos, etc.).
-	Cancelación: Motivos de cancelación, tiempo como suscriptor, valor percibido de Netflix.
-	Satisfacción: Nivel de satisfacción general con Netflix antes de la cancelación.
-	Motivos Cancelación: Razones específicas de la cancelación (por ejemplo, precio, contenido limitado, competencia).

#### 3.	Diseño Lógico:

El modelo lógico incluye las gráficas detalladas y sus relaciones:
1.	-Encuestado:ID_Encuestado Edad, Género, Ingreso, etc.
2.	-Motivo de Cancelación: ID_Motivo (clave primaria), ID_Cancelación (clave foránea), Motivo (Precio, Contenido, Competencia, Otros).
3.	Satisfacción: ID_Satisfacción (clave primaria), ID_Encuestado (clave foránea), NivelSatisfacción (Escala de 1-5), Comentarios.

#### 4.	Diseño Físico:

-	Se diseñó la estructura en hojas de cálculo de la base de datos, considerando la eficiencia en el almacenamiento y las consultas.
-	Se crearon índices en las columnas más relevantes como ID_Encuestado, ID_Cancelación, y Motivo para optimizar las consultas sobre los datos de las cancelaciones.

#### 5.	Validación y Revisión:

-	Las encuestadoras revisaron el modelo para asegurarse de que cubriera todos los aspectos de la encuesta y que los datos se pudieran analizar de manera efectiva.
-	Se hicieron pruebas piloto con algunos registros ficticios para verificar que las relaciones entre las entidades fueran correctas y las consultas funcionaran como se esperaba.

### Implementación del Modelo:

#### 1.	Creación de la Base de Datos:

-	Se implementó el modelo lógico en una base de datos relacional, creando las gráficas correspondientes (por ejemplo, Encuestados, Cancelaciones, MotivosCancelación, Satisfacción)
-	Se definieron claves primarias y foráneas para asegurar la integridad de las relaciones entre las tablas.

#### 2.	Carga de Datos:
-	Los datos de la encuesta fueron importados a la base de datos, con los estudiantes realizando el proceso de validación y limpieza de los datos (eliminación de entradas incompletas, corrección de errores de formato, etc.).

-	Los estudiantes también analizaron patrones en las respuestas, identificando tendencias comunes en las razones de cancelación.

#### 3.	Optimización del Rendimiento:

-	Se crearon índices en las columnas clave (por ejemplo, ID_Encuestado, MotivoCancelación) para asegurar que las consultas sobre los datos de la encuesta fueran rápidas y eficientes.
-	Los estudiantes probaron consultas que permitieran obtener información relevante, como el motivo más común de cancelación por grupo demográfico, o la relación entre la satisfacción y la duración de la suscripción.

#### 4.	Mantenimiento y Actualización:

-	A medida que se recojan más datos de futuras encuestas, los estudiantes implementaron un plan para actualizar el modelo y la base de datos, añadiendo nuevos registros y manteniendo la estructura optimizada.
-	También se planificaron auditorías periódicas para verificar la calidad de los datos y asegurar que el modelo continuara reflejando los objetivos de análisis de cancelaciones.

### Notas adicionales 
El proyecto realizado por los estudiantes no solo se centra en el análisis de datos, sino también en entender los factores que influyen en la retención de usuarios en plataformas de streaming como Netflix. Los estudiantes aplicaron conceptos de bases de datos, modelado de datos y análisis estadístico para generar un modelo que pueda ayudar a identificar posibles áreas de mejora en el servicio.
