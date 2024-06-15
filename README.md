# Predictor de Precios de Laptops
### Matematica III: Segundo TP integrador.

Dataset tomado de Kaggle: https://www.kaggle.com/datasets/juanmerinobermejo/laptops-price-dataset

El dataset fue hecho scrapeando el sitio español PC Componentes: https://www.pccomponentes.com/

Este es un proyecto de machine learning para Matematica III de la carrera de Programacion de la UNSAM. 
Es un modelo basado en Regresion Lineal Multiple, el cual predice precios de laptops basandose en el dataset proveido.

Se toman como atributos el modelo, cpu, gpu, cantidad de memoria ram, almacenamiento, y tamaño de la pantalla. Como variable dependiente se tomo el precio final de la laptop.
El notebook, por medio de un bloque de configuracion, permite al usuario filtrar el entrenamiento del modelo por marca, y tambien da la opcion de si sacar o no los valores atipicos (outliers).

Tambien al final tiene un menu para ingresar los valores y te lanza el precio que predice el modelo a partir de los datos ingresados.

## Dependencias
- Matplotlib
- Numpy
- Pandas
- Scikit-Learn
- Seaborn
- IPyWidgets (para el menu para el predictor)
- Y para correrlo, Jupyter Notebook
