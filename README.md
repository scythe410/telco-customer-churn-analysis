# IIT ID: 20240835
# RGU ID: 2425473
# CM2604 Machine Learning

## Telco Customer Churn Analysis

This project performs a detailed analysis and modeling to predict customer churn using the Telco Customer Churn dataset.

## Dataset

The dataset used in this project is the [Telco Customer Churn dataset](https://www.kaggle.com/blastchar/telco-customer-churn) from Kaggle. It contains information about a hypothetical telco company that provided home phone and Internet services to 7043 customers in California in Q3.

## Project Structure

The project is organized as follows:

*   **`data/`**: Contains the raw and processed data files.
    *   `raw/`: Original dataset.
    *   `processed/`: Cleaned and transformed data ready for modeling.
*   **`notebooks/`**: Jupyter notebooks for each stage of the analysis.
    *   `exploratory/`:
        *   `01-eda-and-visualization.ipynb`: Exploratory Data Analysis and visualization.
    *   `modeling/`:
        *   `02-preprocessing.ipynb`: Data cleaning and preprocessing.
        *   `03-modeling-decision-tree.ipynb`: Decision Tree model implementation.
        *   `04-modeling-neural-network.ipynb`: Neural Network model implementation.
        *   `05-model-comparison.ipynb`: Comparison of model performance.
*   **`results/`**: Directory for storing output results.

## Dependencies

This project requires the following Python libraries:

*   pandas
*   numpy
*   matplotlib
*   seaborn
*   scikit-learn
*   tensorflow

## Usage

1.  Clone the repository.
2.  Install the required dependencies.
3.  Navigate to the `notebooks/` directory.
4.  Run the notebooks in the following order:
    1.  `exploratory/01-eda-and-visualization.ipynb`
    2.  `modeling/02-preprocessing.ipynb`
    3.  `modeling/03-modeling-decision-tree.ipynb`
    4.  `modeling/04-modeling-neural-network.ipynb`
    5.  `modeling/05-model-comparison.ipynb`
