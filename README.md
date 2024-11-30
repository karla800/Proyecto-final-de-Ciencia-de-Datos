# Introducción a la Ciencia de Datos Proyecto Final:
## Análisis de cancelaciones de subscripciones en la plataforma de Netflix en la ciudad de Xalapa

Elaborado por: 

Fernández Mendoza Karla Valeria
Gómez Días Giovanna Arlette 
Méndez Lara Vanessa Guadalupe
Rivera Báez Vanessa Lizeth

## Objetivo
Analizar las cancelaciones de subscripciones en la plataforma de Netflix en la ciudad de Xalapa, opiniones de los usuarios al tener una cuenta en esta plataforma y posibles motivos por los cuales existiría una cancelación a futuro.

## Investigación del Problema	
Definición del Problema: Identificar patrones en las cancelaciones de suscripciones de Netflix en Xalapa, entender las razones detrás de la permanencia o cancelación de cuentas y evaluar cómo diversos factores (como la satisfacción del usuario y el acceso a contenido) influyen en la decisión de cancelar la suscripción.

Conformación del Equipo: Estudiantes de la Licenciatura Ingeniería en Ciencia de Datos

Recolección de Datos: Recopilar datos sobre cancelaciones de suscripciones, encuestas de satisfacción de usuarios, comentarios sobre contenido y calidad de servicio, y análisis de competencia y precios de Netflix en comparación con otras plataformas de streaming en la ciudad de Xalapa.

## Diseño de la Propuesta de Solución
Análisis Exploratorio: Realizar un análisis exploratorio de los datos recolectados a través de una encuesta, para identificar las variables que afectan la decisión de cancelar la suscripción a Netflix en Xalapa. Analizar la distribución de respuestas y explorar las correlaciones entre variables como la satisfacción con el contenido, el precio, la calidad del servicio y otros factores socioeconómicos o de acceso.

Modelado de Datos: Desarrollar modelos predictivos utilizando los resultados de la encuesta para identificar los factores clave que influyen en la cancelación de la suscripción. El modelo podrá proyectar la probabilidad de cancelación en función de los comportamientos y opiniones de los usuarios encuestados.

Selección de Análisis: Aplicar técnicas de análisis como regresión para cuantificar la relación entre las variables clave y la cancelación, así como clustering (algoritmo de datos) para segmentar a los usuarios en grupos con comportamientos similares o con alto riesgo de cancelar.

## Desarrollo del Piloto
Pruebas Iniciales: Implementar un piloto recolectando datos de una muestra representativa de usuarios de Netflix en Xalapa a través de la encuesta. Validar los modelos predictivos en función de la información obtenida y realizar análisis cualitativos adicionales con respuestas abiertas en la encuesta para entender mejor los motivos detrás de las cancelaciones.

Evaluación de Impacto: Evaluar el impacto de las intervenciones basadas en los resultados de la encuesta, como cambios en el contenido o en las estrategias de precios, midiendo indicadores como la mejora en la satisfacción de los usuarios y la tasa de retención o reducción de cancelaciones.

## Implementación y Escalamiento
Planificación de Despliegue: Si el piloto en Xalapa es exitoso, extender el modelo de encuesta a otras ciudades para obtener datos adicionales, adaptando las preguntas según las características y preferencias de los usuarios en otras regiones.

Monitoreo y Ajuste: Realizar un seguimiento continuo a través de encuestas periódicas para ajustar los modelos predictivos y las estrategias de intervención, considerando los cambios en las preferencias de los usuarios, las condiciones de mercado y las respuestas a las modificaciones implementadas.

## Fases del proyecto
1. Introducción [haz click para ir]# Bienvenido(a) al Proyecto Final 

## Introduccion del Proyecto

En la era digital, las plataformas de streaming como Netflix han transformado la forma en que las personas consumen entretenimiento. Sin embargo, el comportamiento de los usuarios frente a estos servicios varía considerablemente, dependiendo de factores como la accesibilidad, la satisfacción con el contenido y el costo. En este contexto, entender las razones detrás de las cancelaciones de suscripciones se ha convertido en un desafío crucial para empresas como Netflix, que buscan mejorar su retención de usuarios y adaptar sus servicios a las necesidades de los consumidores.
Xalapa, una ciudad con una población diversa y en constante crecimiento, refleja una muestra representativa de estos retos. La variabilidad en los niveles socioeconómicos y las preferencias culturales de los usuarios de Netflix en la ciudad generan diferencias en la satisfacción con la plataforma y, por ende, en las tasas de cancelación de suscripciones. En zonas con menor poder adquisitivo o con un acceso limitado a servicios tecnológicos, las cancelaciones pueden estar más relacionadas con factores económicos, mientras que, en áreas de mayores ingresos, pueden influir otros elementos como la calidad del contenido o las alternativas de entretenimiento.
El análisis de los datos de cancelación de suscripciones a Netflix en Xalapa es esencial para comprender las dinámicas de uso de la plataforma en esta región. Este proyecto se enfoca en identificar los motivos que llevan a los usuarios a cancelar su suscripción, explorar las razones detrás de la permanencia de aquellos que mantienen su cuenta activa y, finalmente, proporcionar recomendaciones que permitan a Netflix mejorar su oferta y retener a más usuarios.
El estudio se centra en la recolección de datos a través de encuestas a usuarios de Netflix en Xalapa, con el objetivo de obtener una visión más clara sobre sus experiencias con la plataforma. Al identificar los factores clave que afectan la decisión de cancelar o mantener la suscripción, se espera ofrecer información valiosa que permita a Netflix tomar decisiones estratégicas más informadas en cuanto a su oferta y estrategias de retención en la ciudad.

### Formulacion del Problema 

#### Personas Usuarias 

Las principales personas usuarias de este análisis son las personas que tienen una cuenta en la 
plataforma y que podrían cancelar su suscripción o, por el contrario, decidir seguir suscritos, y los 
estudiantes de la licenciatura Ingeniería en Ciencia de Datos que buscan estudiar las posibles tendencias de cancelación, el comportamiento 
del consumidor y otros aspectos relacionados con el uso de la plataforma

#### Contexto del Problema 

En Xalapa, los usuarios de Netflix enfrentan diferentes desafíos que pueden influir en su decisión de cancelar la suscripción. Factores como el costo del servicio, la variedad de contenido, la calidad de la conexión a internet y las preferencias personales juegan un papel crucial en la decisión de mantener o cancelar una cuenta. Las diferencias socioeconómicas entre los usuarios de diferentes zonas de la ciudad pueden generar variabilidad en la satisfacción con la plataforma. Por ejemplo, en áreas con mayor poder adquisitivo, los usuarios pueden esperar una mayor calidad de servicio y contenido exclusivo, mientras que, en zonas con menos recursos, el costo y el acceso limitado a internet pueden ser factores determinantes en la cancelación.
Xalapa, como ciudad de tamaño medio en Veracruz, cuenta con una población diversa en cuanto a edades, hábitos de consumo y poder adquisitivo. Sin embargo, actualmente no se dispone de un análisis detallado sobre los patrones de cancelación de suscripciones a Netflix en la ciudad. La falta de esta información dificulta la capacidad de la plataforma para identificar las causas específicas de las cancelaciones y desarrollar estrategias personalizadas de retención para los usuarios de Xalapa. Este análisis busca llenar este vacío y proporcionar datos clave que permitan a Netflix tomar decisiones informadas sobre cómo mejorar su oferta y aumentar la lealtad de los usuarios.

#### Indicadores

Para abordar el problema de las cancelaciones de suscripciones a Netflix en Xalapa, se propusieron los siguientes indicadores clave:
•	Número de usuarios de Netflix por zona de la ciudad.
•	Proporción de usuarios con suscripción mensual, trimestral o anual.
•	Promedio de tiempo de suscripción por usuario antes de la cancelación.
•	Distribución geográfica de los usuarios de Netflix (zonas de la ciudad: urbana, suburbana, rural).
•	Relación entre la satisfacción del usuario y las razones de cancelación de suscripción.

2. Planteamiento del problema [haz click para ir]
3. Conjunto de datos. [haz click para ir]
4. Modelamiento de datos. [haz click para ir]
5. Resultados. [haz click para ir]
6. Conclusiones.
