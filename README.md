# Predicting Salaries for Data-Related Jobs

This repository contains the code, data and analysis for my MSc IT in Business Data Analytics project at IBS.

- Topic: Predicting Salaries for Data-Related Jobs
- Student: Behrad KhamenehMohammadi
- Student ID: 1251322633

## GitHub project structure:

- `Data/Raw/` – original datasets
- `Documents/` – additional documents
- `Figures/` – plots and figures for the thesis
- `Notebook/` – main analysis notebooks

## Execution Method

The full analysis for this project was carried out in Google Colab to ensure a stable and reproducible environment.  
All steps of the workflow—from loading the dataset to generating the final figures—are included inside the main notebook located in the `Notebook/` directory.

To reproduce the results:

1. Open the notebook `salary_analysis_main.ipynb` in Google Colab.
2. Mount Google Drive when prompted, so the notebook can access the project files.
3. Run all cells in order.  
   The notebook handles data cleaning, feature engineering, model training, evaluation, SHAP interpretation, and external validation.
4. All figures generated during the run are automatically saved inside the `Figures/` folder.
5. The notebook produces the same outputs on any device, as long as the environment and package versions remain the same.

This structure makes the workflow easy to follow and ensures that every step of the analysis can be repeated without additional configuration.

## Dependencies

The project uses standard Python libraries for data analysis, machine learning, and visualisation.  
All required packages are listed in the `requirements.txt` file in the repository.

Main libraries include:

- **pandas** – data handling and preprocessing  
- **numpy** – numerical operations  
- **scikit-learn** – model training, evaluation, and preprocessing  
- **matplotlib / seaborn** – visualisations  
- **shap** – model interpretation  
- **joblib** – saving preprocessing pipelines and models  





