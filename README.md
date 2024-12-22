# Unemployment Analysis Project

This project aims to analyze and visualize unemployment data using various data analysis and machine learning techniques. The project is implemented using Python and Streamlit for interactive visualizations.

## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [Data Analysis](#data-analysis)
- [Clustering](#clustering)
- [Regression](#regression)
- [Factor Analysis](#factor-analysis)
- [Chi-square Test](#chi-square-test)
- [Principal Component Analysis (PCA)](#principal-component-analysis-pca)
- [Support Vector Machine (SVM)](#support-vector-machine-svm)
- [Summary Statistics](#summary-statistics)
- [Missing Data](#missing-data)
- [Correlation](#correlation)

## Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/Sri-Krishnan007/Unemployment-analysis.git
    ```
2. Navigate to the project directory:
    ```sh
    cd unemployment-analysis
    ```
3. Install the required dependencies:
    ```sh
    pip install -r requirements.txt
    ```

## Usage

1. Run the Streamlit application:
    ```sh
    streamlit run unem.py
    ```
2. Open your web browser and go to `http://localhost:8501` to interact with the application.

## Data Analysis

The project performs various data analysis tasks on the unemployment dataset, including:

### Clustering

- **KMeans Clustering**: This technique is used to partition the data into `k` clusters. The optimal number of clusters is determined using the silhouette score.
- **Agglomerative Clustering**: This hierarchical clustering method groups data points into clusters based on their similarity.

### Regression

- **Linear Regression**: This technique is used to predict future unemployment rates based on historical data.

### Factor Analysis

- **Factor Analysis**: This technique is used to identify underlying relationships between variables in the dataset.

### Chi-square Test

- **Chi-square Test**: This statistical test is used to determine if there is a significant association between two categorical variables.

### Principal Component Analysis (PCA)

- **PCA**: This technique is used to reduce the dimensionality of the dataset while retaining most of the variance.

### Support Vector Machine (SVM)

- **SVM**: This machine learning model is used to classify data points based on their features.

### Summary Statistics

- **Summary Statistics**: This section provides descriptive statistics for the dataset, including mean, median, standard deviation, etc.

### Missing Data

- **Missing Data Visualization**: This section visualizes the missing data in the dataset using a heatmap.

### Correlation

- **Correlation Matrix**: This section visualizes the correlation between different variables in the dataset using a heatmap.

## Dataset

The dataset used in this project is an Excel file containing unemployment data. The file is loaded and preprocessed in the `unem.py` script.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.
