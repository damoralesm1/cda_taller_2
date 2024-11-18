# Taller 2: Implementación de Machine Learning en un Supermercado Inteligente

**Ingeniería de Sistemas y Computación**  
**Escuela de Posgrado**  
**MINE-4101: Ciencia de Datos Aplicada**  
**Semestre:** 2024-20  
**Horario:** Jueves de 6:00 a 9:00 p.m.

**Alumno:** Diego Alvaro Morales Medrano  
**Código:** 202315708  

---

## Archivos del Repositorio

- **GroceryStoreDataset**: Carpeta que contiene el dataset utilizado en el proyecto. Incluye imágenes de productos y archivos de etiquetas necesarios para el entrenamiento y validación de los modelos.

- **taller-2.ipynb**: Jupyter Notebook que contiene el desarrollo completo del taller, organizado en las siguientes secciones:

  - **Importación de librerías y carga de datos**: Preparación del entorno de trabajo y carga del dataset.

  - **Exploración y preparación de los datos**: Análisis inicial del dataset, selección de categorías, preprocesamiento y creación de generadores de datos para el entrenamiento.

  - **Desarrollo y entrenamiento de modelos**: Implementación de los modelos de CNN mejorada y Transfer Learning con VGG16, incluyendo ajustes de hiperparámetros y técnicas de regularización.

  - **Evaluación y selección del mejor modelo**: Comparación de métricas de desempeño, evaluación en el conjunto de prueba y generación de reportes de clasificación.

  - **Análisis financiero y cálculo del ROI**: Cálculos detallados de ahorro en costos de personal, costos por errores y estimación del retorno de la inversión considerando escenarios con validación humana.

  - **Insights y recomendaciones**: Interpretación de los resultados, conclusiones y propuestas para la implementación del modelo en un entorno real.

  - **Clasificación detallada**: Extensión del modelo para clasificar productos por marcas utilizando etiquetas finas.

---

## Dependencias

Para ejecutar el notebook y reproducir el análisis, es necesario instalar las siguientes dependencias:

```bash
pip install numpy
pip install pandas
pip install matplotlib
pip install seaborn
pip install tensorflow
pip install scikit-learn
```

---