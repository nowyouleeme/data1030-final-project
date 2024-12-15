# Predicting Lethal Outcomes After Myocardial Infarctions Using 24-hour Post-Admission Patient Data
Myocardial infarction (MI) presents one of the most complex challenges in modern medicine due to the significant variability in the manifestation of post-MI lethal complications among patients. Through this project, I hope to develop a binary classification model that can predict whether a patient will experience a lethal complication or not 24 hours after their admission to the hospital for an MI. 
The dataset was compiled by the team of the original paper and sourced from the [UC Irvine Machine Learning Repository](https://archive.ics.uci.edu/dataset/579/myocardial+infarction+complications)

The project is built in Python 3.12.5 and repository organization is as follows:
1. `data/` - Stores all (raw and preprocessed) data files
2. `figures/` - Stores all generated visualizations (EDA, result comparisons)
3. `results/` - Contains all trained model data and comparison results
4. `report/` - Contains report on development pipeline, methodology, and model results.
5. `src/` - Contains all source code (`final-project.ipynb` for all steps of ML pipeline)

The key packages used in this project are the following<sup>*</sup>:
- python 3.12.5
- matplotlib 3.9.2
- plotly 5.23.0
- pandas 2.2.2
- scikit-learn 1.5.1
- numpy 1.26.4
- py-xgboost 2.1.1
- shap 0.45.1
- jupyterlab 4.2.5
- jupyter_client 8.6.2
- jupyter_core 5.7.2
- jupyter_server 2.14.2

<sub>*_Check file environment.yml for complete configuration and package dependencies_</sub>