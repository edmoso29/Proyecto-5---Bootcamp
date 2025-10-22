# Proyecto-5-Bootcamp

•	Objetivo: Análisis de datos de tarifas de una empresa de telefonía

•	Librerías principales: pandas, numpy, matplotlib/seaborn, scipy.stats y/o statsmodels; posible uso de sklearn.

•	Carga y preprocesado:

o	Lectura de uno o varios CSV/TSV; renombrado de columnas y casteo (IDs a str, timestamps a datetime).

o	Generación de columnas derivadas (event_date, event_hour, flags) y agregados por usuario.

o	Filtrado por fecha/condiciones de negocio; manejo básico de nulos/duplicados.

•	Análisis Exploratorio de Datos:

o	Conteos totales de eventos y usuarios únicos; tasa promedio de eventos por usuario.

o	Distribuciones temporales (día/hora), barplots/histogramas e identificación de eventos clave.

o	Construcción de embudo: usuarios únicos por etapa y tasas de conversión entre pasos.

•	Experimentación:

o	Agrupación por variante/exp_id y conteo de usuarios por grupo.

o	Tests de proporciones (z-test / proportions_ztest) para comparar conversiones; p-values calculados y decisión con alpha (0.05).

o	Tablas resumen con resultados por evento/medida.

•	Salidas: tablas y gráficos que resumen usuarios por evento, conversion rates y resultados de los tests; conclusiones y recomendaciones operativas.
