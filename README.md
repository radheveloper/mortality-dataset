# Patrones de Mortalidad en Bucaramanga (2021-202X)

Este repositorio contiene el análisis y procesamiento avanzado de datos de defunciones registrados en Bucaramanga, Santander, Colombia, desde el año 2021 hasta la actualidad. El objetivo principal es explorar, limpiar y modelar los datos para identificar patrones relevantes y factores asociados a la mortalidad en la ciudad.

## Descripción del Dataset

El dataset proviene de la [Empresa Social del Estado Instituto de Salud de Bucaramanga (ISABU)](https://www.datos.gov.co/Salud-y-Protecci-n-Social/DEFUNCIONES/sgf4-8tf8/about_data) y contiene más de 18,000 registros de defunciones, cada uno con 22 atributos que incluyen información demográfica, social y médica.

### Principales columnas del dataset:

- **SITIO DEFUNCIÓN:** Lugar del fallecimiento (hospital, domicilio, vía pública, etc.).
- **TIPO DEFUNCIÓN:** Defunción fetal o no fetal.
- **FECHA DEFUNCIÓN / NACIMIENTO:** Fechas relevantes.
- **SEXO, EDAD, ESTADO CONYUGAL:** Variables demográficas.
- **NIVEL EDUCATIVO, OCUPACIÓN, PERTENENCIA ÉTNICA:** Variables socioeconómicas y culturales.
- **DEPARTAMENTO/MUNICIPIO/ÁREA DE RESIDENCIA:** Localización geográfica.
- **RÉGIMEN SEGURIDAD:** Afiliación al sistema de salud.
- **PROBABLE MANERA MUERTE / CAUSA DIRECTA:** Clasificación preliminar y diagnóstico médico.

## Proceso de Limpieza y Preprocesamiento

Uno de los puntos centrales de este proyecto es el **proceso de limpieza de datos**, que fue **notablemente extenso y meticuloso**. Se realizó una exploración profunda de las columnas para identificar y gestionar valores nulos, inconsistencias, redundancias y errores de codificación. 

Además de la depuración tradicional, se empleó **inteligencia artificial avanzada** para transformar los datos y **extraer macro-categorías** que simplifican y potencian el análisis:

- **Macro-categorías médicas:** Se procesaron los textos libres de las causas de muerte y se agruparon en categorías médicas homogéneas, permitiendo análisis epidemiológicos más robustos y comparables.
- **Macro-categorías de ocupación:** Se utilizaron modelos de IA para agrupar las ocupaciones reportadas en grandes categorías del mercado laboral y socioeconómico, facilitando el estudio de factores sociales asociados a la mortalidad.

Este enfoque permitió transformar los datos crudos en información accionable y mucho más útil para la modelización y visualización.

## Estructura del Proyecto

- **Patrones_de_Mortalidad_en_Bucaramanga_(2021_202X).ipynb:** Notebook principal con la exploración, limpieza avanzada, preprocesamiento y primeros análisis del dataset.
- **defunciones.csv (no incluido):** Archivo fuente de datos, debe ser descargado desde el portal oficial de datos abiertos.

## Análisis Realizados

1. **Exploración Inicial:** Inspección de la estructura, cardinalidad y calidad de los datos.
2. **Limpieza y Preprocesamiento Extensivo:** Eliminación de columnas irrelevantes, manejo de valores nulos y estandarización de categorías mediante IA.
3. **Extracción de Macro-categorías:** Clasificación inteligente de causas médicas y ocupaciones.
4. **Visualización de Patrones:** Identificación de tendencias y correlaciones entre variables relevantes.
5. **Preparación para Modelado Predictivo:** Estructuración de los datos para futuros modelos de Machine Learning.
