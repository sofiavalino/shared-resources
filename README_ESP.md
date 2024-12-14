
# Shared Resources 🛠️

Este repositorio centraliza herramientas reutilizables que facilitan el desarrollo y mantienen la consistencia entre proyectos. Para leer el README en inglés, hacer click en [README.md](https://github.com/sofiavalino/shared-resources/blob/main/README.md).

## Contenido 📚

1. **Preprocesamiento de Datos**
2. **Gestión de Logs**
3. **Timers y Métricas**
4. **Visualización**
5. **Configuración General**
6. **Machine Learning**
7. **Documentación y Ejemplos**

### 1. Preprocesamiento de Datos `shared_resources/data_preprocessing/`
- **Funciones comunes de limpieza de datos**:
  - Eliminar valores atípicos.
  - Imputar valores nulos (media, mediana, forward-fill).
  - Normalización/estandarización de columnas.
  - Codificación categórica (One-Hot, Label Encoding, etc.).
- **Transformaciones**:
  - Escalado logarítmico o Min-Max.
  - Agregar columnas derivadas (por ejemplo, interacciones o polinomios).

### 2. Gestión de Logs `shared_resources/logging/`
- **Configuración de logging**:
  - Función para configurar un logger con diferentes niveles (`DEBUG`, `INFO`, `ERROR`).
  - Formateo de logs con timestamp y nivel de severidad.
  - Escritura de logs en archivos o en consola.

### 3. Timers y Métricas  `shared_resources/timing/`
- **Decoradores de medición de tiempo**:
  - Decorador para medir cuánto tarda una función en ejecutarse.
  - Clase o función para realizar "profiling" de código.
- **Cálculo de métricas de desempeño**:
  - Accuracy, Precision, Recall, F1-Score (en caso de ML).
  - Análisis de distribución (media, mediana, percentiles).

### 4. Visualización `shared_resources/visualizations/`
- **Gráficos preconfigurados con Matplotlib/Seaborn/Plotly**:
  - Gráficos de líneas, barras, cajas (boxplots) y heatmaps.
  - Configuración de estilos personalizados (colores, fuentes).

### 5. Configuración General `shared_resources/utils/`
- **Gestión de archivos y rutas**:
  - Funciones para cargar y guardar archivos en formatos comunes (CSV, JSON, Parquet).
  - Validación de rutas y nombres de archivos.
- **Parámetros y configuración global**:
  - Archivo central para definir constantes (por ejemplo, rutas de datos).
  - Configuración que pueda cargarse desde un archivo JSON o YAML.

### 6. Machine Learning `shared_resources/ml`
- **Pipelines reutilizables**:
  - Preprocesamiento, división de datos, y selección de modelo.
- **Evaluación de modelos**:
  - Función para crear gráficos ROC, PR y matrices de confusión.
  - Reporte automático con métricas clave.

### 7. Documentación y Ejemplos `shared_resources/examples/`
- **Ejemplos o notebooks que expliquen cómo usar cada recurso**:
  - Notebooks interactivos mostrando las funciones en acción.
  - Archivos README para cada categoría.

## Estructura del Repositorio 📂

```plaintext
shared-resources/
│
├── requirements-shared-resources.txt
├── README_ESP.md
├── README.md
├── data_preprocessing/
│   ├── data_cleaning.py
│   ├── feature_engineering.py
├── logging/
│   ├── logger.py
├── timing/
│   ├── timer.py
├── visualizations/
│   ├── plot_helpers.py
├── utils/
│   ├── file_helpers.py
├── ml/
│   ├── model_evaluation.py
├── examples/
│   ├── data_preprocessing_example.ipynb
│   ├── logging_example.ipynb
```
## Contribuciones 🤝

Si tienes alguna sugerencia para mejorar los proyectos, o si encuentras algún problema, no dudes en abrir un issue o enviar un pull request. Puedes también dejar tus comentarios en los proyectos que te interesen.

## Licencia 📜

Este proyecto está bajo la [MIT License](https://github.com/sofiavalino/template-datascience-project/blob/main/LICENSE). Si deseas usar o modificar el código, asegúrate de revisar los términos de la licencia.

## Contacto 📧

¡Explora los proyectos y si tienes alguna pregunta o sugerencia, no dudes en contactarme!

[![LinkedIn](https://img.shields.io/badge/-LinkedIn-0077B5?logo=linkedin&logoColor=white&style=flat-square)](https://www.linkedin.com/in/sofiavalino/)  
[![Gmail](https://img.shields.io/badge/-Gmail-D14836?logo=gmail&logoColor=white&style=flat-square)](mailto:valinosofia@gmail.com)

## Por último pero no menos importante: Mi Blog =^._.^= 📚

Además de los proyectos de este repositorio, también comparto mis apuntes de la facultad y temas relacionados con Data Science y ciencias de la computación en mi blog. En él, encontrarás contenido sobre las materias que estudio, así como detalles sobre los proyectos que realizo y otros temas de interés.

[![Blog](https://affable-valinosofia.wordpress.com/wp-content/uploads/2024/07/site-logo.png?w=88&h=88)](https://affable-valinosofia.wordpress.com/)