Clasificación del Riesgo de Inundación por Parroquia — Los Ríos
Descripción
Modelo de clasificación supervisada para predecir el nivel de riesgo de inundación (bajo, medio, alto) de las 30 parroquias de la provincia de Los Ríos, Ecuador.

🛠️ Tecnologías utilizadas
Tecnología	Uso
Python	Flask, scikit-learn, pandas
Leaflet	Mapa interactivo
PythonAnywhere	Hosting en producción

Estructura del proyecto

app.py — backend Flask que carga el modelo y el GeoJSON
modelo.pkl — Regresión Logística entrenada
scaler.pkl — escalador para normalizar datos
label_encoder.pkl — decodificador de etiquetas
predicciones_parroquias.csv — predicciones para el mapa
notebook/ — análisis exploratorio y modelado
informe/ — informe académico en LaTeX
presentacion/ — diapositivas del proyecto

plicación en producción
https://andresvl.pythonanywhere.com

Cómo ejecutar localmente
# 1. Instalar dependencias
pip install -r requirements.txt

# 2. Ejecutar la aplicación
python app.py

Autor
Andrés V. López

