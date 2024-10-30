# Practica-Machine-Learning
Práctica Machine Learning


Proyecto de Machine Learning - Predicción de Ciberataques 🛡️
¡Bienvenidos a mi práctica de Machine Learning donde hemos estado jugando a ser detectives cibernéticos! Este proyecto se trata de predecir qué acción se tomará ante diferentes tipos de ciberataques utilizando un modelo de regresión logística.

Descripción del Proyecto 📝
En este proyecto, hemos utilizado un dataset de ciberseguridad para entrenar y evaluar un modelo que nos ayude a predecir la variable "Action Taken". Aunque los resultados iniciales del modelo tienen una precisión de alrededor del 33-34%, hay mucho potencial para mejorar.

Pasos Seguidos 📈
Preparación de Datos:

Cargamos el dataset y dividimos los datos en conjuntos de entrenamiento y prueba.

Analizamos las características del dataset para entender mejor su estructura.

Análisis Exploratorio:

Visualizamos la distribución de la variable objetivo ("Action Taken") para ver cuántas veces se toma cada acción.

Creamos boxplots para detectar valores atípicos en las características numéricas.

Generamos una matriz de correlación para ver cómo se relacionan las variables numéricas entre sí.

Preprocesamiento:

Imputamos los valores nulos en las columnas numéricas con la mediana y en las categóricas con el valor más frecuente.

Utilizamos un modelo de Random Forest para identificar y seleccionar las características más importantes.

Visualizamos la distribución de las 5 características más relevantes.

Modelado:

Estandarizamos las características seleccionadas.

Entrenamos un modelo de regresión logística y evaluamos su rendimiento mediante validación cruzada.

Evaluación:

Evaluamos el modelo utilizando métricas como precisión, recall y F1-score.

Conclusión 🤔
El modelo de regresión logística muestra una precisión de alrededor del 33-34% basado en la validación cruzada. Estos resultados nos indican que posiblemente se pueda mejorar. Tal vez no se han seleccionado las mejores características para la variable objetivo, o puede que las características disponibles en el dataset no sean lo suficientemente predictivas. Otra posibilidad es que este dataset esté diseñado para que intentemos conseguir un modelo mejor a fuerza de ensayo/error, como si de un reto se tratara.
