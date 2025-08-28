# Data-Scientist-III
# Proyecto Final
# "Análisis de opiniones de clientes mediante NLP: identificación de tendencias y sentimientos"
# Héctor leonardo Ferreyra
# Abstracto
## Motivación:
En la actualidad, los negocios dependen fuertemente de la percepción que sus clientes tienen sobre sus productos y servicios. Lo que empuja el anaálisis de las opiniones y reseñas que permiten identificar fortalezas, debilidades y áreas de mejora, generando información valiosa para la toma de decisiones, esto es, la evaluación de satisfacción del cliente. Además, el aprendizaje automático y el procesamiento de lenguaje natural (NLP) ofrecen herramientas potentes para extraer insights de grandes volúmenes de texto de manera automática y escalable.

## Audiencia:
El presente trabajo está dirigido a la dirección de la empresa Directorio Refrigeración SA, que busca comprender mejor la experiencia del cliente y cuantificar el sentimiento general hacia la misma.

## Contexto Comercial y Analítico
El proyecto se centra en la satisfacción del cliente hacia la empresa Directorio Refrigeración SA, con reseñas en Google, cuyos clientes expresan opiniones sobre atención, precios, calidad del servicio y otros aspectos. Analíticamente, el proyecto combina técnicas de NLP para preprocesar, analizar y visualizar opiniones, con un enfoque exploratorio de sentimientos.

El análisis incluye:
-Limpieza y tokenización de texto.
-Identificación de palabras y n-grams más frecuentes.
-Clasificación de sentimientos(positivo, negativo, neutral).
-Visualización de patrones mediante gráficos y WordCloud.
-Este contexto permite transformar datos no estructurados en información accionable para decisiones comerciales.

## Hipótesis a Resolver
-¿Cuáles son los aspectos más mencionados por los clientes en sus opiniones?
-¿Predomina un sentimiento positivo, negativo o neutral hacia el comercio?
-¿Se pueden identificar patrones de lenguaje que indiquen oportunidades de mejora (por ejemplo, precios o atención)?

## Hipótesis: La mayoría de opiniones destacan la atención y los precios como los factores más relevantes, y la percepción general es positiva.

## Objetivo
Objetivo General:
-Analizar las opiniones de los clientes de Directorio Refrigeraciín utilizando técnicas de NLP y visualización, para identificar los tópicos más mencionados y el sentimiento general de los clientes.

Objetivos Específicos:
-Preprocesar y limpiar el texto de opiniones.
-Extraer palabras clave y combinaciones frecuentes de palabras (n-grams).
-Clasificar el sentimiento de cada opinión en positivo, negativo o neutral.
-Visualizar los resultados mediante gráficos y WordCloud para facilitar la interpretación.
-Generar insights prácticos que puedan guiar decisiones comerciales.

## Conclusión
El análisis de las opiniones extraídas de Google permitió extraer información valiosa sobre la experiencia y satisfacción de los clientes.
Los análisis exploratorios iniciales (longitud de oraciones, frecuencia de palabras, n-grams y POS tagging) permitieron entender la estructura y el énfasis del lenguaje utilizado por los clientes.
Las visualizaciones (nubes de palabras, distribuciones de frecuencias y gráficos de entrenamiento de modelos) facilitaron la interpretación de patrones de manera clara e intuitiva.
Se identificaron los tópicos más mencionados, principalmente relacionados con la atención del personal, la calidad del servicio y los precios.
A través del análisis de sentimiento, se comprobó que la mayoría de los comentarios tienen una carga positiva, destacando la buena atención y la satisfacción general.
Respecto de los comentarios negativos, se detectaron áreas de mejora asociadas a la puntualidad en la atención, la variedad de medios de pago y algunos aspectos de organización interna.De este modo, las principales oportunidades de mejora se centran en:
-Formas de pago: algunos clientes reportaron limitaciones o dificultades para pagar con ciertos medios, lo cual genera frustración.
-Atención puntual: se evidencian quejas vinculadas a demoras y tiempos de espera más prolongados de lo esperado.
-Comunicación: en algunos casos se señalaron problemas de información poco clara o falta de respuesta rápida a consultas.


# Deep Learning - Redes neuronales
# Clasificación de Fallas en Piezas o Maquinaria

## Resumen del Proyecto
El proyecto consiste en desarrollar un modelo de Red Neuronal Convolucional (CNN) para la detección automática de fallas en piezas de acero laminado en caliente mediante imágenes. Se trabajó sobre un dataset de imágenes que representan diferentes tipos de defectos: Crazing, Inclusion y Patches. El análisis incluye la descarga, organización y preprocesamiento de los datos, el entrenamiento de la CNN, y la evaluación de su capacidad de generalización para clasificar correctamente nuevas imágenes.

## Objetivo del Análisis
El objetivo principal del análisis es automatizar la identificación de fallas en superficies de piezas de acero laminado en caliente, reduciendo el tiempo y la dependencia de inspecciones manuales. Esto se logra entrenando una CNN capaz de reconocer patrones visuales específicos de cada tipo de defecto, generando predicciones precisas y confiables a partir de imágenes nuevas.

## Usuario Final
El usuario final de este proyecto son ingenieros de control de calidad, técnicos de inspección y personal de producción en industrias metalúrgicas. Estas personas podrán utilizar la herramienta para realizar inspecciones rápidas, obtener reportes automáticos y tomar decisiones basadas en información confiable sobre el estado de las piezas de acero.

## Alcance
El proyecto se enfoca en la clasificación de fallas visuales en superficies de piezas de acero laminado en caliente a partir de imágenes estáticas. No aborda fallas internas o datos de sensores, sino exclusivamente la identificación de defectos visibles en las superficies. El modelo está limitado a las clases presentes en el dataset (Crazing, Inclusion, Patches) y puede ampliarse en el futuro con nuevos tipos de defectos.

## Impacto
La implementación de este sistema permite mejorar la eficiencia y precisión en los procesos de inspección de calidad del acero laminado en caliente, reduciendo errores humanos y tiempos de revisión. Además, facilita la detección temprana de defectos, lo que puede prevenir pérdidas económicas, optimizar el mantenimiento y aumentar la confiabilidad de las piezas producidas.

## Definición del problema
El objetivo es implementar un modelo de red neuronal profunda para predecir fallas basadas en defectos superficiales en piezas de acero laminados en caliente, utilizando imágenes para el análisis. Este tipo de análisis es bueno para la implementación de mantenimiento predictivo en entornos industriales.

## Conclusiones
El proyecto demuestra que las CNN son herramientas efectivas para la clasificación automática de fallas en superficies de piezas de acero laminado en caliente. El modelo entrenado alcanzó una buena capacidad de generalización, permitiendo identificar correctamente los defectos presentes en el dataset. Esto evidencia que la visión por computadora puede integrarse en procesos industriales para optimizar la inspección y el control de calidad de manera confiable.
