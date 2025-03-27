# Churn_rate_prediction
Creación y prueba de modelos de machine learning para predecir la probabilidad de cancelación de contratos de telecomunicaciones. 
***Proyecto desarrollado como evaluación final del Bootcamp de Data Scientist de TripleTen.***

## Contexto del proyecto
Al operador de telecomunicaciones Interconnect le gustaría poder pronosticar su tasa de cancelación de clientes. Si se descubre que un usuario o usuaria planea irse, se le ofrecerán códigos promocionales y opciones de planes especiales. El equipo de marketing de Interconnect ha recopilado algunos de los datos personales de sus clientes, incluyendo información sobre sus planes y contratos.

## Objetivo del proyecto
Crear un modelo de machine learning de clasifiación que obtenga un score ROC-AUC mayor al 0.75

## Modelos de machine learning creados
- Logistic Regression
- Random Forest Classifier
- Light Gradient Boosting Machine (Light GBM)
- XGBoost

## Resultados
- Se logró un score **ROC-AUC de 0.89** con el modelo Light GBM, **19% mejor** que el mínimo solicitado.
- Se identificaron las características más relevantes para la predicción de la cancelación de contratos.
- En el archivo de informe_final se pueden observar los resultados completos.
- En el archivo de código se puede observar el dasarrollo completo del proyecto, desde el análisis exploratorio hasta el entrenamiento de los modelos de machine learning.