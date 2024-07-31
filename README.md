# Heart Disease Prediction and Interpretability

This project demonstrates the use of machine learning techniques to predict heart disease and explores advanced interpretability methods using SHAP (SHapley Additive exPlanations) and LIME (Local Interpretable Model-agnostic Explanations). The goal is to provide a comprehensive analysis of the model's predictions and insights into the importance of various features.

## Project Overview

- **Data Source**: The dataset used is the Cleveland Heart Disease dataset from the UCI Machine Learning Repository.
- **Model**: Logistic Regression
- **Interpretability Methods**: SHAP and LIME

## Project Structure

- `data/`: Directory to store datasets.
- `notebooks/`: Jupyter notebooks containing the analysis.
- `models/`: Directory to save trained models.
- `results/`: Directory to save results and plots.
- `README.md`: Project overview and instructions.

## Setup Instructions

### Prerequisites

- Python 3.x
- Jupyter Notebook
- Required libraries (see `requirements.txt`)

### Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/heart-disease-prediction-interpretability.git
    cd heart-disease-prediction-interpretability
    ```

2. Install the required libraries:
    ```bash
    pip install -r requirements.txt
    ```

3. Start Jupyter Notebook:
    ```bash
    jupyter notebook
    ```

4. Open and run the notebook:
    ```bash
    notebooks/heart_disease_prediction.ipynb
    ```

## Data Preprocessing

The dataset is preprocessed to handle missing values and encode categorical variables. Features are standardized to improve model performance.

## Model Training and Evaluation

A Logistic Regression model is trained on the preprocessed dataset. The model's performance is evaluated using accuracy, precision, recall, and F1-score.

## Interpretability Analysis

### SHAP Analysis

SHAP values are computed to explain the model's predictions. The SHAP summary plot and dependence plots provide insights into feature importance and interactions.

### LIME Analysis

LIME is used to generate local explanations for individual predictions, highlighting the contributions of each feature.

## Results

The project provides a comprehensive analysis of the model's performance and interpretability. The results and plots are saved in the `results/` directory.

## Contributions

Contributions are welcome! Please fork the repository and submit a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

