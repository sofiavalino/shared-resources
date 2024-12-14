
# Shared Resources 🛠️

This repository centralizes reusable tools to facilitate development and maintain consistency across projects. To read the README in Spanish, click [README_ESP.md](https://github.com/sofiavalino/shared-resources/blob/main/README_ESP.md).

## Contents 📚

1. **Data Preprocessing**
2. **Log Management**
3. **Timers and Metrics**
4. **Visualization**
5. **General Configuration**
6. **Machine Learning**
7. **Documentation and Examples**

### 1. Data Preprocessing `shared_resources/data_preprocessing/`
- **Common data cleaning functions**:
  - Remove outliers.
  - Impute missing values (mean, median, forward-fill).
  - Normalize/standardize columns.
  - Categorical encoding (One-Hot, Label Encoding, etc.).
- **Transformations**:
  - Logarithmic or Min-Max scaling.
  - Add derived columns (e.g., interactions or polynomials).

### 2. Log Management `shared_resources/logging/`
- **Logging configuration**:
  - Function to set up a logger with different levels (`DEBUG`, `INFO`, `ERROR`).
  - Log formatting with timestamps and severity levels.
  - Write logs to files or the console.

### 3. Timers and Metrics `shared_resources/timing/`
- **Time measurement decorators**:
  - Decorator to measure the execution time of a function.
  - Class or function to perform code profiling.
- **Performance metrics calculations**:
  - Accuracy, Precision, Recall, F1-Score (for ML).
  - Distribution analysis (mean, median, percentiles).

### 4. Visualization `shared_resources/visualizations/`
- **Preconfigured plots with Matplotlib/Seaborn/Plotly**:
  - Line charts, bar plots, box plots, and heatmaps.
  - Custom style configurations (colors, fonts).

### 5. General Configuration `shared_resources/utils/`
- **File and path management**:
  - Functions to load and save files in common formats (CSV, JSON, Parquet).
  - Validate paths and file names.
- **Global parameters and configuration**:
  - Central file to define constants (e.g., data paths).
  - Configuration loaded from JSON or YAML files.

### 6. Machine Learning `shared_resources/ml`
- **Reusable pipelines**:
  - Preprocessing, data splitting, and model selection.
- **Model evaluation**:
  - Functions to create ROC, PR curves, and confusion matrices.
  - Automatic reporting with key metrics.

### 7. Documentation and Examples `shared_resources/examples/`
- **Examples or notebooks to explain resource usage**:
  - Interactive notebooks demonstrating the functions.
  - README files for each category.

## Repository Structure 📂

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

## Contributions 🤝

If you have suggestions to improve the projects or encounter any issues, feel free to open an issue or submit a pull request. You can also leave your feedback on the projects you're interested in.

## License 📜

This project is under the [MIT License](https://github.com/sofiavalino/template-datascience-project/blob/main/LICENSE). If you want to use or modify the code, make sure to review the license terms.

## Contact 📧

Explore the projects, and if you have any questions or suggestions, don't hesitate to reach out!

[![LinkedIn](https://img.shields.io/badge/-LinkedIn-0077B5?logo=linkedin&logoColor=white&style=flat-square)](https://www.linkedin.com/in/sofiavalino/)  
[![Gmail](https://img.shields.io/badge/-Gmail-D14836?logo=gmail&logoColor=white&style=flat-square)](mailto:valinosofia@gmail.com)

## Last but not least: My Blog =^._.^= 📚

In addition to the projects in this repository, I also share my university notes and topics related to Data Science and Computer Science on my blog. You'll find content about the subjects I'm studying, as well as details about the projects I'm working on and other topics of interest.

[![Blog](https://affable-valinosofia.wordpress.com/wp-content/uploads/2024/07/site-logo.png?w=88&h=88)](https://affable-valinosofia.wordpress.com/)
