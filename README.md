# Predictive Modeling AI Architecture for Glioblastoma Invasiveness Prediction
**Final Study master Bioinformatic DS Technologie-Nanostring-GeoMx**

## Objective
The objective of this AI architecture is to accurately predict the invasiveness of glioblastomas and stratify these predictions based on different subtypes of the tumor (IDH1/IDH1 WT) and their clinical consequences.

## Methodology Overview
The predictive modeling process involves correlating comparative data obtained through total transcriptomics and spatial transcriptomics from Nanostring, along with data obtained through RIM 7t (lactate and diffusion tensor concentration). The following steps outline the methodology:

1. **Data Acquisition**: Gather transcriptomic data from Nanostring and RIM 7t data.
2. **Preprocessing**: Clean, normalize, and preprocess the data to prepare it for modeling.
3. **Feature Engineering**: Extract relevant features from the data, considering both transcriptomic and spatial characteristics.
4. **Model Selection**: Choose appropriate machine learning algorithms for predictive modeling.
5. **Model Training**: Train the selected models using the preprocessed data.
6. **Evaluation**: Assess the performance of the models using appropriate evaluation metrics.
7. **Deployment**: Deploy the trained models for real-time prediction of glioblastoma invasiveness.

## Proposed AI Architecture
For this predictive modeling task, a combination of traditional machine learning techniques and deep learning models can be employed. Here's a suggested AI architecture:

### Traditional Machine Learning Approach:
1. **Feature Selection**:
   - Use statistical methods (e.g., correlation analysis) to identify relevant features.
2. **Model Selection**:
   - Train classic machine learning models such as Random Forest, Support Vector Machines (SVM), and Gradient Boosting Machines (GBM).
3. **Ensemble Learning**:
   - Combine the predictions of multiple models using techniques like model averaging or stacking to improve accuracy.

