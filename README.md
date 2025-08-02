# Proyecto IA - Sentimientos

## Descripción
Este proyecto implementa un pipeline completo de Inteligencia Artificial para análisis de sentimientos, desde la ingesta y limpieza de datos hasta el modelado y despliegue en una API.  
Incluye scripts, notebooks, modelos y una estructura modular para desarrollo profesional.

## Estructura del Proyecto
```plaintext
proyecto-ia-sentimientos/
├── README.md                  # Documentación del proyecto
├── requirements.txt           # Librerías necesarias
├── setup.py                   # Instalación como paquete
├── data/                      # Datos utilizados en el proyecto
│   ├── raw/                   # Datos originales sin procesar
│   ├── processed/             # Datos limpios y listos para modelar
│   └── external/              # Datos externos o complementarios
├── src/                       # Código fuente del proyecto
│   ├── __init__.py
│   ├── data/                  # Scripts de ingesta y limpieza
│   ├── models/                # Entrenamiento y predicciones
│   ├── features/              # Ingeniería de características
│   ├── visualization/         # Visualizaciones y gráficos
│   └── utils/                 # Funciones auxiliares
├── models/                    # Modelos entrenados y configuraciones
│   ├── trained_models/
│   └── model_configs/
├── notebooks/                 # Notebooks de Jupyter
│   ├── exploratory/           # Análisis exploratorio (EDA)
│   ├── modeling/              # Entrenamiento y ajuste
│   └── evaluation/            # Evaluación y métricas
├── api/                       # API para exponer el modelo
│   ├── app.py
│   ├── routes/
│   └── schemas/
├── dashboard/                 # Visualización interactiva (ej. Streamlit)
├── tests/                     # Pruebas unitarias
├── docs/                      # Documentación técnica
└── docker/                    # Archivos para contenedores Docker
