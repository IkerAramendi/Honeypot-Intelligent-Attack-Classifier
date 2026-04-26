# Honeypot-Intelligent-Attack-Classifier
Proyecto sobre honeypots inteligentes con clasificación automática de ataques mediante machine learning.

## Objetivo
Desplegar un honeypot, capturar ataques reales y entrenar un modelo de ML que clasifique los ataques.

## Tecnologías
- Cowrie honeypot
- Python
- Machine Learning
## Estructura
db/ 
Archivo para el mapeo de IPs y saber su país

log/
Datos del proyecto. Incluye logs capturados por el honeypot y una vez ejecutado, el dataset procesados usados para entrenar los modelos.

script/
Jupyter Notebooks utilizados para procesar los logs, análisis exploratorio de datos (EDA), feature engineering y entrenamiento de modelos.

model/
Modelo de Machine Learning entrenados y guardados (por ejemplo archivos .pkl o .joblib).

informe/
Documentación del proyecto e informe final
