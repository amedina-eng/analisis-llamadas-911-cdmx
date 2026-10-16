Análisis Exploratorio y Predictivo de Llamadas al 911 (CDMX - 2022)

Este proyecto realiza un análisis integral del flujo de llamadas de emergencia al servicio 911 en la Ciudad de México durante el primer semestre del año 2022, procesando un dataset real de más de **390,000 registros**.

##  Objetivos
- Identificar las alcaldías y colonias con mayor volumen de atención de emergencias.
- Analizar los tipos e incidentes más recurrentes mediante estadística descriptiva y multivariable.
- Evaluar tendencias temporales y aplicar modelos estadísticos y de Machine Learning para clasificar días de alta demanda.

##  Tecnologías Utilizadas
- **Lenguaje:** Python 3.x
- **Entorno:** Google Colab / Jupyter Notebooks
- **Librerías principales:**
  - `pandas` y `numpy` para manipulación y limpieza de datos.
  - `matplotlib` y `seaborn` para la creación de histogramas, diagramas de caja (boxplots), mapas de calor y gráficos multivariable.
  - `scipy` para estimadores de locación/variabilidad y análisis estadístico.
  - `scikit-learn` para regresión lineal, árboles de decisión, validación cruzada y evaluación del modelo (Precision, Recall, F1-Score).

##  Principales Hallazgos
- **Concentración Geográfica:** Las alcaldías **Iztapalapa**, **Gustavo A. Madero** y **Cuauhtémoc** concentran la mayor carga del servicio, sumando más de 157,000 llamadas combinadas.
- **Incidentes Frecuentes:** Las categorías de *Servicios*, *Disturbios/Faltas Cívicas* y *Agresiones* predominan drásticamente sobre otro tipo de reportes.
- **Tendencia Temporal:** Se identificó una correlación positiva fuerte ($r = 0.77$) entre el transcurso de los días del semestre y el incremento en el volumen diario de llamadas.

##  Estructura del Repositorio
- `ProyectoFinal_911.ipynb`: Cuaderno interactivo de Google Colab con el código fuente completo, limpiezas de datos y visualizaciones.
