# Análisis de Actividad Humana con Sensores

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![Machine Learning](https://img.shields.io/badge/Machine-Learning-orange)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange)

## 📖 Descripción
Proyecto de análisis de datos de sensores de smartphones para clasificación de actividades humanas utilizando algoritmos de Machine Learning.

## 📁 Estructura del Proyecto
proyecto_aml/
│
├── Analisis_de_trenes_AML.ipynb # Notebook principal
├── README.md # Este archivo
├── requirements.txt # Dependencias
├── data/ # Datos
│ ├── train.csv
│ └── test.csv
└── images/ # Gráficas y resultados


## 🚀 Instalación

1. Clonar el repositorio:
```bash
git clone https://github.com/tuusuario/proyecto-aml.git
cd proyecto-aml

python -m venv venv
source venv/bin/activate  # En Windows: venv\Scripts\activate

pip install -r requirements.txt

📊 Resultados Clave

Clustering K-means

Se identificaron 6 clusters correspondientes a las 6 actividades
Cluster 0: Actividades de pie y sentado
Cluster 4: Movimientos activos (caminar, subir escaleras)
Normalización

Todas las características sensoriales fueron normalizadas (0-1)
Mejora en el rendimiento de algoritmos de ML
📈 Visualizaciones

Incluye gráficos de:

Distribución de clusters
Análisis de componentes principales (PCA)
Matrices de confusión
🧪 Próximos Pasos

Implementar redes neuronales profundas
Optimizar hiperparámetros
Realizar análisis de features importantes
👥 Contribuidores
Martin Sebastian Cálcena

📄 Licencia

Este proyecto está bajo la Licencia MIT.

text

## 5. **Crear requirements.txt**

```txt
pandas==1.5.3
numpy==1.23.5
scikit-learn==1.2.2
matplotlib==3.7.1
seaborn==0.12.2
jupyter==1.0.0
notebook==6.5.3
ipykernel==6.23.1


## 📌 Conclusiones y Lecciones Aprendidas

### ✅ Lo que funcionó bien:
1. La normalización MinMax mejoró significativamente el rendimiento
2. K-means identificó patrones claros entre actividades
3. El análisis PCA permitió visualizar clusters en 2D

### 🔧 Desafíos encontrados:
1. Alta dimensionalidad (561 features)
2. Necesidad de balancear el preprocesamiento
3. Selección de hiperparámetros óptimos

### 🎯 Impacto del proyecto:
- Demostración práctica de técnicas de AML
- Base para sistemas de monitoreo de actividad
- Aplicación en salud y fitness tech
