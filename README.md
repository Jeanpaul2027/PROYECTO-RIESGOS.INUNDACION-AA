# PROYECTO-RIESGOS.INUNDACION-AA
Clasificación del Riesgo de Inundación por Parroquia — Los Ríos
Descripción
Modelo de clasificación supervisada que predice el nivel de riesgo de inundación (bajo, medio, alto) para las 30 parroquias de la provincia de Los Ríos, Ecuador. El proyecto combina machine learning con visualización geoespacial interactiva.

🛠️ Tecnologías
Backend: Python (Flask)

Machine Learning: scikit-learn (Logistic Regression)

Datos: pandas, numpy

Visualización: Folium (mapas interactivos)

Despliegue: PythonAnywhere

Estructura
text
proyecto-riesgo-inundacion/
├── app.py                      # Aplicación Flask
├── requirements.txt            # Dependencias
├── data/
│   ├── los_rios.geojson        # Polígonos de parroquias
│   └── predicciones_parroquias.csv # Resultados del modelo
├── templates/
│   └── index.html              # Mapa interactivo
└── model/                      # Modelo entrenado
    ├── modelo.pkl
    ├── scaler.pkl
    └── label_encoder.pkl
Ejecución local
bash
# Clonar repositorio
git clone https://github.com/tu-usuario/proyecto-riesgo-inundacion.git

# Instalar dependencias
pip install -r requirements.txt

# Ejecutar aplicación
python app.py
Abrir en navegador: http://localhost:5000

Demo en producción
https://andresvl.pythonanywhere.com

Rendimiento del modelo
Métrica	Valor
Precisión	85%
Precisión (macro)	0.83
Recall (macro)	0.81
F1-Score (macro)	0.82
Características
Predicción automatizada de riesgo por parroquia

Mapa interactivo con codificación por colores

API REST para consultas

Código modular y escalable
