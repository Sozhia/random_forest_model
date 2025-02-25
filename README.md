# Random Forest para Predicción de Diabetes 🩺📊
Este proyecto implementa un modelo de clasificación supervisado utilizando Random Forest para predecir la presencia de diabetes en pacientes a partir de un conjunto de datos clínicos.

## 📌 Características del Proyecto
✅ Preprocesamiento de datos:
* Eliminación de datos no estructurados (clinical_notes).
* Conversión de variables categóricas a numéricas mediante one-hot encoding.
* División del dataset en 80% entrenamiento / 20% prueba.

✅ Entrenamiento del Modelo:
* Se emplea un Random Forest Classifier con 100 árboles de decisión.
* Ajuste del modelo con el dataset de entrenamiento.

✅ Evaluación y Visualización de Resultados:
* Matriz de confusión 📊: Para analizar los aciertos y errores del modelo.
* Importancia de las características 🔍: Identificación de las variables más influyentes.
* Curva ROC y AUC 📈: Evaluación del rendimiento en clasificación.
* Precisión y métricas 📑: Reporte detallado de desempeño.
  
## 📌 Requisitos
* Bibliotecas necesarias:
pip install pandas numpy matplotlib seaborn scikit-learn
* Carga de datos:
Asegurar que el dataset esté disponible en formato CSV antes de ejecutar el código.

## 📌 Resultados y Conclusiones
📢 Hallazgos Clave:
El modelo alcanzó una precisión significativa en la predicción de diabetes.
La edad, hipertensión y nivel de glucosa en sangre fueron las variables más influyentes.
La curva ROC y AUC reflejaron un buen desempeño en la clasificación binaria. 

🚀 Posibles Mejoras:
Ajuste de hiperparámetros para optimizar la precisión.
Aplicación de técnicas de balanceo si se detecta desbalance en las clases.
Exploración de modelos más avanzados como XGBoost o redes neuronales.

----------------------------
📌 Autor: Miqueas G.G.
