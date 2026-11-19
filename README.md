Analisis de Rendimiento y Tiempos de Resolucion de Incidentes IT
Repositorio del proyecto final de ciencia de datos, desarrollado de forma individual con un enfoque practico aplicado a la gestion de infraestructura tecnologica y soporte tecnico.

Estructura del Proyecto
El proyecto se divide en las tres etapas fundamentales del ciclo de vida de los datos:

Etapa 1: Seleccion, exploracion y limpieza de datos.

Etapa 2: Estadistica descriptiva, analisis comparativo y deteccion de valores atipicos.

Etapa 3: Visualizacion efectiva, modelado predictivo mediante regresion lineal y storytelling profesional.

Contenido del Repositorio
notebooks/proyecto_ciencia_de_datos.ipynb: Cuaderno de Google Colab con el codigo completo ejecutable.

data/dataset_depurado.csv: Conjunto de datos limpio y transformado listo para analisis.

presentation/: Diapositivas de apoyo para la exposicion.

README.md: Documentacion principal del proyecto.

Resumen por Etapas
ETAPA 1 · Fundamentos y Herramientas
Seleccion del Dataset: Se diseno y adapto un conjunto de datos realista de operaciones de TI para evaluar el ciclo de atencion de fallas tecnicas en sistemas.

Limpieza y Transformacion:

Se identificaron celdas con valores nulos en el tiempo de resolucion, corrigiendolas mediante imputacion por mediana.

Se eliminaron registros duplicados para evitar sesgos en el analisis.

Se estandarizaron los formatos de texto y las categorias de prioridad y tipos de sistemas, pasando de un conjunto bruto de 205 filas a un set depurado de 200 registros limpios.

ETAPA 2 · Estadistica Descriptiva y Preprocesamiento
Medidas Estadisticas: Se calcularon metricas clave sobre el tiempo de resolucion en horas, lo que permitio obtener una vision clara de la tendencia central y la dispersion operativa.

Segmentacion: Mediante analisis agrupados, se evaludo el comportamiento de los tiempos de atencion segun la prioridad del incidente.

Deteccion de Outliers: El uso de diagramas de caja facilito la identificacion de incidentes criticos atipicos que superaban el rango intercuartilico habitual, senalando posibles cuellos de botella operativos.

ETAPA 3 · Modelado Matematico y Storytelling
Visualizaciones: Se implementaron histogramas de distribucion y diagramas comparativos para ilustrar de forma clara la naturaleza de la carga de trabajo tecnica.

Modelo Predictivo: Se entreno un modelo de regresion lineal simple para analizar la relacion entre la complejidad de los incidentes y el tiempo total de resolucion, evaluando su ajuste mediante el coeficiente de determinacion y el error cuadratico medio.

Aplicacion Profesional: Este enfoque analitico demuestra como las areas de TI y la gestion tecnica pueden anticipar demoras operativas, optimizar la asignacion de recursos de soporte y fundamentar la toma de decisiones en metricas basadas en datos reales.

Enlaces y Recursos
https://colab.research.google.com/drive/1DsRmDb-Rd9D4g_zizlYXWVjITWl8DQ4K?usp=sharing

https://youtu.be/v-HcLHqgm2A
