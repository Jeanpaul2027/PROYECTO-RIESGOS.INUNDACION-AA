# PROYECTO-RIESGOS.INUNDACION-AA
🌊 Clasificación del Riesgo de Inundación por Parroquia — Los Ríos
Descripción
Modelo de clasificación supervisada para predecir el nivel de riesgo de inundación (bajo, medio, alto) de las 30 parroquias de la provincia de Los Ríos, Ecuador.

Tecnologías utilizadas
Python (Flask, scikit-learn, pandas)

Leaflet (mapa interactivo)

PythonAnywhere (hosting)

Estructura del proyecto
text
proyecto-riesgo-inundacion/
├── app.py                      # Backend Flask
├── requirements.txt            # Dependencias
├── data/
│   ├── los_rios.geojson        # Polígonos de parroquias
│   └── predicciones_parroquias.csv # Resultados del modelo
├── templates/
│   └── index.html              # Mapa interactivo
├── model/
│   ├── modelo.pkl              # Regresión Logística entrenada
│   ├── scaler.pkl              # Escalador para normalizar datos
│   └── label_encoder.pkl       # Decodificador de etiquetas
├── notebook/                   # Análisis exploratorio y modelado
├── informe/                    # Informe académico en LaTeX
└── presentacion/               # Diapositivas del proyecto
Aplicación en producción
https://andresvl.pythonanywhere.com

Cómo ejecutar localmente
bash
pip install -r requirements.txt
python app.py
