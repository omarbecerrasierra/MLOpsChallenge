# Desafíos de Machine Learning y Procesamiento de Lenguaje Natural

Este repositorio contiene las soluciones a dos desafíos técnicos en el ámbito de Machine Learning y MLOps, así como en el procesamiento de lenguaje natural (NLP) y modelos de lenguaje grandes (LLMs).

## Contenido

	1.	Descripción General
	2.	Desafío 1: Clasificación de Vinos
	•	Descripción del Problema
	•	Solución Implementada
	•	Resultados y Conclusiones
	3.	Desafío 2: Procesamiento de Hojas de Vida
	•	Descripción del Problema
	•	Solución Implementada
	•	Resultados y Conclusiones

## Descripción General

Este repositorio contiene las soluciones a dos desafíos técnicos. El primero está enfocado en la clasificación de vinos utilizando Machine Learning y MLOps, con la plataforma Databricks y MLflow para el manejo y registro de experimentos. El segundo desafío se centra en la automatización de la revisión de currículums utilizando técnicas de NLP y modelos de lenguaje grandes (LLMs), con el objetivo de extraer información clave de hojas de vida.

## Desafío 1: Clasificación de Vinos

### Descripción del Problema

El objetivo de este desafío es implementar un modelo de clasificación que identifique la variedad de uva de un vino basado en sus características químicas y visuales. Se utilizaron los datos del UCI Machine Learning Repository, y se implementaron diferentes algoritmos de clasificación para seleccionar el modelo más preciso.

### Solución Implementada

La solución incluye:

	•	Preprocesamiento de Datos: Manejo de valores faltantes, outliers, y balanceo de clases.
	•	Entrenamiento del Modelo: Implementación de varios algoritmos de clasificación (Logistic Regression, SVM, Random Forest, etc.).
	•	Evaluación del Modelo: Análisis de las métricas de rendimiento, registradas y gestionadas mediante MLflow en Databricks.
	•	Predicciones en Nuevas Muestras: Se realizaron predicciones sobre dos nuevas muestras de vino.

### Resultados y Conclusiones

El modelo seleccionado mostró un alto nivel de precisión. Se documentan las métricas, los resultados y las conclusiones obtenidas a partir de los experimentos.

Ver más detalles en la Documentacion del Caso 1

## Desafío 2: Procesamiento de Hojas de Vida

### Descripción del Problema

El objetivo de este desafío es automatizar la extracción de información clave de hojas de vida utilizando técnicas de NLP y LLMs. El modelo desarrollado debe retornar la información extraída en formato JSON, incluyendo un score que indique la precisión de la extracción.

### Solución Implementada

La solución incluye:

	•	Extracción de Texto desde PDFs: Utilizando PyMuPDF.
	•	Procesamiento y Limpieza de Texto: Normalización y limpieza del texto extraído.
	•	Uso de LLMs para Extracción de Información: Implementación de un modelo de lenguaje grande para extraer información clave del texto.
	•	Generación de JSON con Resultados: Incluyendo los valores extraídos.

### Resultados y Conclusiones

Se logró extraer la información clave con un nivel aceptable de precisión, documentando tanto los éxitos como las áreas de mejora.

Ver más detalles en la Documentacion Caso 2
