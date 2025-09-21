# Regresion-logistica-y-validacion-cruzada

Este proyecto aplica un modelo de **Regresión Logística** para predecir si un hongo es **venenoso o comestible** utilizando el clásico dataset de **UCI Mushroom Dataset**.

## Objetivo
- Predecir la variable binaria `class_num`, donde:
  - `0` = hongo comestible  
  - `1` = hongo venenoso
- Analizar cómo diferentes atributos morfológicos y organolépticos influyen en la clasificación.
- Evaluar el modelo con **validación cruzada** y diferentes umbrales de decisión.

## Dataset
El conjunto de datos proviene del [UC Irvine Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/mushroom).  
Cada observación corresponde a un hongo descrito por atributos categóricos (color, forma, olor, etc.).  

Después de aplicar **One-Hot Encoding**, cada categoría se convirtió en una variable booleana (`0` o `1`).

- **Variable objetivo**: `class_num`  
- **Número de muestras**: 8124  
- **Número de variables después de one-hot**: 138  


[Base de datos](https://github.com/NelsonAbad/Regresion-logistica-y-validacion-cruzada/blob/fbd0335d5ce46ed6a1f30ba719f5e131b902b228/mushroom_clean_onehot.csv)

[Reporte en .ipynb](https://github.com/NelsonAbad/Regresion-logistica-y-validacion-cruzada/blob/fbd0335d5ce46ed6a1f30ba719f5e131b902b228/A2.1%20Regresi%C3%B3n%20log%C3%ADstica%20y%20validaci%C3%B3n%20cruzada.ipynb)

[Reporte en HTML](A2.1%20Regresi%C3%B3n%20log%C3%ADstica%20y%20validaci%C3%B3n%20cruzada.html)
