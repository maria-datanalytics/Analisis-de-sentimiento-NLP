# Análisis de Sentimiento de Reseñas en Trustpilot mediante NLP

## Descripción

Este proyecto aplica técnicas de Procesamiento del Lenguaje Natural (NLP) para analizar las opiniones de clientes publicadas en Trustpilot. El objetivo es identificar la percepción de los usuarios, descubrir los principales temas de conversación y detectar oportunidades de mejora para el negocio.

La empresa seleccionada para el análisis es **Monzo**, perteneciente al sector financiero.

## Objetivos

* Analizar el sentimiento de las reseñas mediante modelos preentrenados de Deep Learning.
* Identificar los principales temas (topics) presentes en las opiniones de los clientes.
* Evaluar el sentimiento asociado a cada topic.
* Comparar los resultados obtenidos con otras empresas del mismo sector.
* Proponer recomendaciones de negocio basadas en datos.

## Metodología

El proyecto sigue las siguientes fases:

1. Carga y exploración de datos.
2. Limpieza y preprocesamiento del texto.
3. Análisis de sentimiento mediante Transformers (DistilBERT).
4. Extracción de topics mediante TF-IDF y NMF.
5. Análisis conjunto de sentimiento y topics.
6. Benchmark frente a empresas competidoras del sector financiero.

## Principales Resultados

* El 69% de las reseñas analizadas presentan sentimiento negativo.
* Los aspectos mejor valorados están relacionados con la experiencia digital, la facilidad de uso y las funcionalidades de gestión financiera.
* Los principales focos de insatisfacción se concentran en atención al cliente, incidencias operativas y bloqueos de cuentas.
* En comparación con otras empresas del sector, Monzo ocupa la segunda posición en porcentaje de reseñas positivas dentro del benchmark analizado.

## Tecnologías Utilizadas

* Python
* Pandas
* NumPy
* Scikit-Learn
* Matplotlib
* Seaborn
* NLP (Sentiment Analysis & Topic Modeling)

## Autor

**María Monedero**
Máster en Data Science e Inteligencia Artificial
