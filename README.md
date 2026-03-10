
# Reporte de Analisis de Evasion de Clientes - Telecom X

## Descripcion del Proyecto
Este proyecto se centra en el analisis del Churn (evasion de clientes) para la empresa de telecomunicaciones Telecom X. El objetivo principal es identificar los factores demograficos y de consumo que influyen en la perdida de clientes para proporcionar informacion estrategica al equipo de Ciencia de Datos y a la gerencia.

## Estructura del Proyecto
El trabajo se divide en cuatro fases principales siguiendo una metodologia de analisis de datos:
1. Extraccion de Datos (ETL)
2. Transformacion y Limpieza
3. Analisis Exploratorio de Datos (EDA)
4. Informe de Resultados y Recomendaciones

## Tecnologias Utilizadas
* Python
* Pandas (Manipulacion y tratamiento de datos)
* Matplotlib / Seaborn (Visualizacion de datos)
* Google Colab (Entorno de desarrollo)

## Procesamiento de Datos (ETL)
Durante la fase de limpieza se realizaron las siguientes acciones:
* Normalizacion de estructuras JSON anidadas para su conversion a DataFrames de Pandas.
* Conversion de tipos de datos: Se transformo la columna de cargos totales a formato numerico, gestionando errores de formato de origen.
* Tratamiento de nulos: Se imputaron valores faltantes en cargos totales basados en la facturacion mensual.
* Limpieza de texto: Se eliminaron espacios en blanco y se estandarizaron las categorias para evitar duplicidades en el analisis.

## Hallazgos Principales
* El indice de evasion general se situa en un 26% de la base total de clientes.
* Los clientes con contratos mes a mes presentan una vulnerabilidad significativamente mayor a la evasion en comparacion con los contratos anuales o bianuales.
* Se identifico un periodo critico de perdida de clientes durante el primer año de contrato (especialmente entre los meses 1 y 12).
* Existe una correlacion entre los cargos mensuales elevados y la decision de cancelar el servicio, particularmente en usuarios del servicio de fibra optica.

## Conclusiones e Insights
El analisis sugiere que la flexibilidad de los contratos de corto plazo es el principal facilitador de la salida de clientes. Asimismo, la falta de programas de fidelizacion efectivos durante el primer año de servicio contribuye a una baja retencion inicial.

## Recomendaciones
* Implementar estrategias de migracion de contratos mes a mes hacia modelos de mayor permanencia mediante incentivos comerciales.
* Desarrollar un programa de acompañamiento proactivo para nuevos clientes durante sus primeros 6 meses de antiguedad.
* Revisar la relacion calidad-precio del servicio de internet de fibra optica para asegurar la satisfaccion del segmento de mayor gasto.
"""
