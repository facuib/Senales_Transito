![membrete ISPC](https://user-images.githubusercontent.com/107323698/201164371-dc86b2fe-f847-49d3-9cd1-b11cdae1f1d0.PNG)
# PROYECTO INTEGRADOR TSCDIA - GRUPO 17 - Cohorte 2022

Ancillotti, Angel - 
Ibarra, Facundo - 
Zorrilla, Juan Pedro - 



# Sistema de Reconocimiento y Alerta de Señales de Tráfico
---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
Este proyecto tiene como objetivo desarrollar un sistema de reconocimiento y alerta de señales de tráfico utilizando técnicas de visión por computadora y procesamiento del habla. El sistema será capaz de detectar automáticamente señales de tráfico en imágenes y proporcionar alertas verbales basadas en la detección realizada.



*Descripción del Proyecto*:
El proyecto se divide en varias etapas principales:

*Preprocesamiento de Imágenes*: 
Se realizará la extracción de imágenes de señales de tráfico, conversión a escala de grises, normalización y reducción de ruido para preparar los datos de entrada.

*Detección de Señales de Tráfico*: 
Se empleará un modelo pre-entrenado de visión por computadora para detectar y clasificar señales de tráfico en las imágenes.

*Generación de Alertas Verbales*: 
Se creará una base de datos de grabaciones de audio para cada señal de tráfico detectada y se desarrollará una función que seleccione la grabación correspondiente para generar una alerta verbal.

*Integración del Procesamiento del Habla*: 
Se integrará un modelo pre-entrenado de reconocimiento de voz para interpretar y procesar las alertas verbales generadas, mejorando así la experiencia del usuario.

*Objetivos del Proyecto*:
Desarrollar un sistema eficiente y preciso de reconocimiento de señales de tráfico.
Implementar alertas verbales para mejorar la seguridad y accesibilidad del sistema.
Integrar tecnologías de procesamiento del habla para una experiencia de usuario mejorada.
Validar y optimizar el sistema para su despliegue en entornos del mundo real.


--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

#Marco de Tabajo:


#Etapas del Proyecto x tiempo de desarrollo:

*Preprocesamiento de Imágenes (1 semana):*
Extraer imágenes de señales de tráfico del PDF.
Convertir las imágenes a escala de grises.
Normalizar las imágenes.
Reducir el ruido en las imágenes.
Investigar y recopilar conjuntos de datos relevantes de señales de tráfico para entrenar y validar el modelo.
Explorar y visualizar los conjuntos de datos para comprender la distribución de las clases y la calidad de las imágenes.

*Detección de Señales de Tráfico (1 semana):*
Cargar un modelo pre-entrenado (por ejemplo, VGG16, ResNet50, InceptionV3).
Adaptar el modelo a tus datos (fine tuning).
Entrenar el modelo con tus datos.
Evaluar el rendimiento del modelo.
Experimentar con diferentes modelos de detección de objetos y técnicas de transfer learning para mejorar el rendimiento del modelo.

*Generación de Alertas Verbales (1 semana):*
Crear una base de datos de grabaciones de audio para cada señal de tráfico.
Desarrollar una función que seleccione la grabación de audio correspondiente a la señal de tráfico detectada.
Investigar y probar modelos más avanzados de reconocimiento de voz, como modelos basados en transformers, para mejorar la precisión del sistema de alertas verbales.

*Integración del Procesamiento del Habla (1 semana):*
Cargar un modelo pre-entrenado para el reconocimiento de voz (por ejemplo, DeepSpeech).
Adaptar el modelo a tus datos (fine tuning).
Entrenar el modelo con tus datos.
Evaluar el rendimiento del modelo.
Integrar el sistema de alertas verbales con el modelo de detección de señales.

*Implementación del Estándar de Minería de Datos (a lo largo del proyecto):*
Preparar los datos para el entrenamiento y la validación.
Seleccionar los modelos más adecuados para tus datos.
Validar los modelos.
Optimizar los modelos.
