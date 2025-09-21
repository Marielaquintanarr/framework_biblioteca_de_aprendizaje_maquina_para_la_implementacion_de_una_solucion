**Predicción de Resultados de Fútbol con Regresión Lineal**
--

Este proyecto utiliza datos de partidos internacionales de fútbol para entrenar un modelo de regresión lineal que predice el resultado de los encuentros y genera un ranking de países con mayor probabilidad de ganar el Mundial.

**Descripción**
---

Se cargan los datos de partidos con estadísticas como posesión, tiros a puerta, faltas, tarjetas y goles.

Se define una variable objetivo (result) que toma los valores:

1 = gana el equipo local

0 = empate

-1 = gana el equipo visitante

Se entrena un modelo de regresión lineal con scikit-learn.

Se calcula el R² para evaluar el ajuste del modelo.

Se genera un ranking de países basado en la fuerza promedio predicha por el modelo.

Se muestra una gráfica de barras con el Top 10 de selecciones.


**Requisitos**
---
* Pandas
* NumPy
* scikit-learn
* Matplotlib

**Instalación de dependencias:**
---
```
pip install pandas numpy scikit-learn matplotlib
```

**Uso**
---
Colocar el archivo FIFAallMatchBoxData.csv en el mismo directorio del script.
Ejecutar el programa

Se mostrará:

El valor de R² del modelo.

El ranking de países con mayor probabilidad de ganar en una gráfica.

**Fuentes**
---
FIFA World Cup match stats. (2021, July 1). Kaggle. https://www.kaggle.com/datasets/kaito510/fifa-world-cup-match-stats
