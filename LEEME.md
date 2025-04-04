# Predicción del Consumo Energético en la Zona de Gran Buenos Aires

## Resumen del Trabajo de Tesis de Maestría

Este repositorio contiene el código que respalda la investigación realizada en la tesis de maestría titulada **"Predicción del consumo energético en la zona de Gran Buenos Aires"**.

**Autor:** Franco Ariel Demare
**Título de la Tesis:** Magister en Inteligencia de Datos orientada a Big Data
**Director/Codirector:** Prof. Dr. Aurelio F. Bariviera
**e-mail de contacto del tesista:** frandemare@gmail.com

## Motivación

La motivación principal de este trabajo radica en la creciente necesidad de predecir con precisión la demanda de energía eléctrica debido a la rápida expansión económica y el aumento del consumo energético, tanto industrial como doméstico. La predicción precisa del consumo es fundamental para optimizar la gestión de recursos, reducir costos y minimizar el impacto ambiental, en línea con los Objetivos de Desarrollo Sostenible (ODS).

## Metodología

En esta investigación, se exploraron y compararon modelos estadísticos y de aprendizaje automático para la predicción del consumo energético:

* **Modelos Estadísticos:**
    * Modelo Autorregresivo y con media móvil (ARIMA)
    * Modelo SVM
* **Modelos de Aprendizaje Automático:**
    * Long Short-Term Memory (LSTM)
    * Convolutional Neural Network (CNN)
    * Modelos CNN-LSTM


Se utilizaron datos históricos de consumo energético para entrenar y evaluar estos modelos, prestando especial atención a la naturaleza de series temporales de los datos y a la **estacionalidad**. Se menciona específicamente el uso de la técnica de **Descomposición en Modos Empíricos (EMD)** para mejorar el rendimiento del modelo LSTM al descomponer la serie temporal en componentes intrínsecos.

## Resultados

La investigación concluyó con la evaluación del rendimiento de los diferentes modelos. Se destaca que el modelo **LSTM combinado con la técnica EMD (LSTM-EMD)** demostró ser el más efectivo para la predicción del consumo energético en el horizonte de pronóstico evaluado (201 observaciones horarias). Este modelo superó en precisión a las predicciones realizadas por CAMMESA para el mismo período.

## Palabras Clave

Aprendizaje automático; Modelo estadístico; Consumo energético; Redes neuronales; Series Temporales; Predicción.

## Contenido del Repositorio

Este repositorio contiene el código fuente desarrollado para la implementación y evaluación de los modelos de predicción descritos en la tesis. Encontrarás scripts para:

* Preprocesamiento y limpieza de los datos.
* Implementación de los modelos estadísticos.
* Implementación de los modelos de aprendizaje automático (incluyendo la integración de EMD con LSTM).
* Entrenamiento y evaluación de los modelos utilizando métricas relevantes.
* Visualización de los resultados y comparativas entre modelos.

El código está principalmente desarrollado en Python y hace uso de librerías como pandas, numpy, scikit-learn, TensorFlow, Keras, statsmodels, etc.

## Cómo Utilizar

Para ejecutar el código en este repositorio, asegúrate de tener instalado un entorno python que puede ser en Anaconda o en Google Colab.

Se recomienda seguir los siguientes pasos:

1.  Clonar este repositorio.
2.  Crear un entorno virtual (opcional) e instalar las dependencias necesarias.
3.  Ejecutar los scripts que se encuentra dentro de Visualización de datos diarios. Para visualizar los datos del set de datos.
4.  Ejecutar los scripts que se encuentra dentro de Implementación de modelos con datos diarios. Para entender las justificaciones de la tesis.
5.  Ejecutar los scripts que se encuentra dentro de Implementación de EMD a modelos LSTM y CNN con datos diarios e intradiarios. Para conocer un caso de uso real del mejor modelo entrenado.

## Contacto

frandemare@gmail.com
