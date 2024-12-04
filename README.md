# Glioma Classification with Machine Learning

This repository is part of a group project aimed at improving the classification of gliomas (brain tumors) into two categories: **Lower-Grade Glioma (LGG)** and **Glioblastoma Multiforme (GBM)**. The project leverages clinical data and genetic mutations to build machine learning models that can help reduce the time and cost associated with traditional diagnostic methods.

The dataset used is sourced from the [Glioma Grading Clinical and Mutation Features Dataset](https://archive.ics.uci.edu/dataset/759/glioma+grading+clinical+and+mutation+features+dataset), which includes 20 gene mutation features and additional clinical parameters.

## Goals
- **Primary Objective**: Develop a machine learning pipeline that achieves high accuracy (target F1 Score: ≥ 0.90) in predicting tumor types.
- **Secondary Objective**: Demonstrate insights through feature importance and visualization techniques.

## Highlights
- **Data Preparation**: Extensive cleaning, encoding, and stratified train-test splitting to address class imbalances.
- **Algorithm Development**: Testing various models, including Decision Trees, Random Forest, Support Vector Machines, and ensemble methods, with optimized hyperparameters.
- **Innovation**: Implementing an ensemble model combining Logistic Regression, Random Forest, and SVM, achieving significant performance improvements.
- **Documentation**: Detailed analysis and methodologies documented to ensure reproducibility.

## Repository Structure
- `/notebooks`: Contains Jupyter Notebooks detailing data cleaning, model development, and results.
<!-- - `/reports`: Insights and findings documented for presentation. -->
- `/data`: Original and preprocessed datasets.

## Results
- Random Forest achieved the best F1 Score of **0.90**, meeting the project’s target.
- Ensemble voting methods demonstrated robust performance across varying metrics.

## Usage
1. Clone this repository: `git clone git@github.com:whellcome/MLGliomaClassification.git`
2. Install dependencies: `pip install -r requirements.txt`
3. Explore the notebooks and scripts to understand the data pipeline and modeling process.

## About the Author
As part of the team, I focused on:
- Data stratification and cleaning to address imbalanced features like race and gender.
- Testing and optimizing models like Decision Trees and Random Forests.
- Developing an ensemble approach combining Logistic Regression, Random Forest, and Support Vector Machines for improved performance.

*For further information or collaboration opportunities, feel free to contact me or support the repository using the Buy Me a Coffee link!*

