# Sure Tomorrow - Machine Learning para Compañía de Seguros

## 📌 Descripción

Este proyecto aborda varias tareas clave para la compañía de seguros **Sure Tomorrow** mediante técnicas de machine learning, con un enfoque especial en la protección de datos personales.

Las tareas incluyen identificación de clientes similares, predicción de probabilidad de prestación, estimación del número de prestaciones y enmascaramiento de datos para proteger la privacidad sin sacrificar la calidad del modelo.

---

## 🎯 Objetivos del Proyecto

1. Encontrar clientes similares a un cliente dado para mejorar las estrategias de marketing.
2. Predecir la probabilidad de que un cliente reciba una prestación del seguro, comparando modelos predictivos con modelos dummy.
3. Predecir el número de prestaciones que un cliente pueda recibir mediante regresión lineal.
4. Implementar un algoritmo de enmascaramiento de datos que proteja la información personal sin afectar el rendimiento del modelo predictivo.

---

## 📊 Descripción de los Datos

El dataset contiene información relevante para las tareas de clasificación y regresión, así como variables personales que requieren protección mediante ofuscación.

---

## ⚙️ Tecnologías Utilizadas

- Python 3
- pandas, numpy, seaborn, matplotlib
- scikit-learn (KNeighborsClassifier, NearestNeighbors, LinearRegression, métricas, preprocesamiento)

---

## 🧪 Metodología

- Análisis exploratorio y preprocesamiento de datos, incluyendo escalado para balancear la influencia de variables.
- Uso de KNN para identificación de clientes similares y clasificación, demostrando su ventaja sobre modelos dummy.
- Aplicación de regresión lineal para predecir la cantidad de prestaciones.
- Desarrollo y validación de un algoritmo de ofuscación basado en transformaciones lineales invertibles, asegurando la protección de datos sin afectar las métricas de regresión (RMSE, R²).

---

## 📈 Resultados

- El escalado mejoró significativamente el desempeño del modelo KNN en clasificación.
- Modelos simples, con el preprocesamiento adecuado, superan a los modelos dummy básicos.
- La regresión lineal mostró robustez frente a la ofuscación, manteniendo métricas de error y precisión.
- El algoritmo de enmascaramiento protege datos personales y permite preservar la calidad del modelo, facilitando su uso en entornos seguros.

---

## ▶️ Cómo Ejecutar

1. Clona el repositorio:
   ```bash
   git clone https://github.com/ely00carmen/Proyecto_13.git
2. Instala las dependencias:
   ```bash
  pip install -r requirements.txt
4. Ejecuta el script o notebook principal:
  ```bash
  jupyter notebook

