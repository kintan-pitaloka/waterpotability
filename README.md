# Evaluating Water Potability with Classification Algorithms
## Overview
This repository focuses on predicting the potability of water using machine learning classifiers. The goal is to develop a model that can determine whether a given water sample is safe for drinking based on various water quality metrics.

## About the Dataset
### Context
Access to safe drinking-water is essential to health, a basic human right, and a key component of effective health protection policies. Safe drinking water is crucial at national, regional, and local levels. Investments in water supply and sanitation can provide significant economic benefits by reducing adverse health effects and healthcare costs.

### Content
The `water_potability.csv` file contains water quality metrics for 3,276 different water bodies. Each record includes various attributes related to water quality, as outlined below:

1. **pH Value**:
   - **Description**: pH is an important parameter for evaluating the acid-base balance of water and its acidity or alkalinity. The WHO recommends a maximum permissible pH range from 6.5 to 8.5. The dataset ranges from 6.52 to 6.83, which is within WHO standards.

2. **Hardness**:
   - **Description**: Hardness is primarily caused by dissolved calcium and magnesium salts. It is defined by the water's capacity to precipitate soap. The hardness of water depends on the time it interacts with hardness-producing materials.

3. **Solids (Total Dissolved Solids - TDS)**:
   - **Description**: TDS measures the concentration of inorganic and some organic minerals or salts dissolved in water. High TDS values indicate high mineralization. The desirable limit for TDS is 500 mg/L, with a maximum limit of 1,000 mg/L for drinking water.

4. **Chloramines**:
   - **Description**: Chloramines are disinfectants formed when ammonia is added to chlorine. Chlorine levels up to 4 mg/L are considered safe in drinking water.

5. **Sulfate**:
   - **Description**: Sulfates are naturally occurring substances found in minerals, soil, rocks, and water. Sulfate concentrations in freshwater range from 3 to 30 mg/L, with higher concentrations in some regions.

6. **Conductivity**:
   - **Description**: Electrical conductivity (EC) measures water's ability to conduct electric current, which is influenced by the concentration of dissolved ions. The WHO standard for EC is up to 400 μS/cm.

7. **Organic Carbon**:
   - **Description**: Total Organic Carbon (TOC) measures the amount of carbon in organic compounds in water. The US EPA recommends TOC levels of <2 mg/L in drinking water and <4 mg/L in source water used for treatment.

8. **Trihalomethanes**:
   - **Description**: THMs are chemicals formed when chlorine reacts with organic material in water. Safe levels of THMs in drinking water are up to 80 ppm.

9. **Turbidity**:
   - **Description**: Turbidity measures the cloudiness of water due to suspended solid matter. The mean turbidity value in the dataset (0.98 NTU) is lower than the WHO recommended value of 5.00 NTU.

10. **Potability**:
    - **Description**: Indicates if water is safe for human consumption, where 1 means potable and 0 means not potable.

## Key Features
- **Dataset**: Contains water quality metrics for 3,276 different water bodies.
- **Classifiers**: Implements various machine learning algorithms including Logistic Regression, Random Forest, Support Vector Machine (SVM), and more.
- **Evaluation Metrics**: Performance evaluated using accuracy, precision, recall, F1 score, confusion matrix, and ROC curve.
- **Visualizations**: Includes heatmaps, bar plots, and other visual tools to interpret data and model results.

## Getting Started
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/yourusername/water-potability-classifier.git
   ```

2. **Install Dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the Notebooks**:
   - Open Jupyter Notebook or JupyterLab.
   - Execute the notebook files (`.ipynb`) located in the `notebooks` folder.

4. **Explore the Code**:
   - Review the `src` folder for code implementations.
   - Check the `scripts` folder for data preprocessing and model training scripts.

