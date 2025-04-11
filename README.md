# Clasificación de Setas Venenosas con Machine Learning

## 📌 Descripción
En este proyecto recibi un dataset de setas desordenada y poco legible, aplicando feature engineer logre realizar una limpieza exhaustiva hasta tener un dataset limpio, luego realice un EDA para detectar cual es la mejor manera de imputar nulos y outliers. Por ultimo realice un modelo de ML para predecir si la seta es venenosa o no, teniendo en cuenta sus caracteristicas.

## 🛠️ Tecnologías y Herramientas
- Python
- Jupyter Notebook
- Pandas
- NumPy
- Scikit-learn
- Matplotlib / Seaborn

### Estructura del repositorio
```
Proyecto_setas/
│── Data/                        
│   ├── train.snappy               # Dataset principal.
│   ├── train_use.csv              # Dataset limpio.
│
│── Notebooks/                     # Jupyter Notebooks
│   ├── Eda.ipynb                  # Analisis Exploratorio.
│   ├── Feature_engenieer.ipynb    # Apartura de dataset y limpieza.
│   ├── Modelo_ml.ipynb            # Aplicacion de modelos ML.
│   ├── Red_neuronal.ipynb         # Red neuronal.
|
│── Utils/                        
│   ├── ClaseAbdon.py              # Clase utilizada para el EDA.
|
│── pyproject.toml                 # Dependencias del proyecto.
│── README.md                      # Documentación del proyecto.
```

