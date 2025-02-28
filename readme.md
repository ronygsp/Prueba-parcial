# TelcoAndes: Proyecto de Minería de Datos para Predicción de Facturación

## Descripción del Proyecto

El objetivo del proyecto es predecir la facturación total de cada usuario en el próximo mes para la empresa TelcoAndes. Se trabaja con cinco tablas principales: **USUARIOS, LLAMADAS, MENSAJES, INTERNET y PLANES**. 

El proceso se divide en:
- **Análisis Exploratorio de Datos (EDA):** Se estudian las distribuciones, la calidad de los datos y se identifican outliers y valores nulos.
- **Data Wrangling:** Se limpian y unifican las tablas, se convierten variables de fecha y se agregan consumos totales por usuario.
- **Feature Engineering:** Se crean variables derivadas, incluyendo la variable objetivo "facturación" (calculada como la suma de la tarifa base del plan y los costos extra por consumo).
- **Modelado de Datos:** Se diseña un modelo de datos en forma de Star Schema, definiendo la tabla de hechos y las dimensiones correspondientes.
- **Entrenamiento y Evaluación de Modelos:** Se entrenan varios modelos de regresión (LinearRegression, SGDRegressor y Ridge Regression) y se evalúan con métricas (RMSE, MAE, R²) y validación cruzada.
- **Conclusiones:** Se resumen los hallazgos, se explica la decisión de descartar la regresión polinomial por sobreajuste y se ofrecen recomendaciones de negocio para optimizar estrategias de precios y segmentación.


