# Jupyter Notebook: Data Cleaning and Model Development

This notebook focuses on key aspects of the glioma classification project, showcasing advanced techniques for handling imbalanced datasets and developing robust machine learning models.

## Notebook Highlights

### 1. **Data Preprocessing**
- Addressed missing values in clinical data, including:
  - Age normalization.
  - Gender and race encoding using OneHotEncoder.
- Created a custom stratified train-test split to ensure balanced representation of minority groups.

### 2. **Feature Engineering**
- Visualized feature importance using correlation heatmaps and pair plots.
- Handled multicollinearity by identifying and excluding highly correlated features.

### 3. **Model Training and Evaluation**
- Tested and tuned multiple machine learning models:
  - **Decision Tree**:
    - Optimal depth and splitting criteria achieved using GridSearchCV.
  - **Random Forest**:
    - Achieved the best F1 Score of **0.91** with 100 estimators and `entropy` criterion.
  - **Ensemble Voting**:
    - Combined Logistic Regression, Support Vector Machines (SVM), and Decision Tree.
    - Demonstrated superior performance on imbalanced datasets.
- Evaluated models using metrics such as Accuracy, Precision, Recall, and F1 Score.

### 4. **Insights**
- Identified key features driving classification performance.
- Highlighted the impact of balancing techniques like stratified sampling.

## How to Use the Notebook
1. Install required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
2. Launch the notebook:
   ```bash
   jupyter notebook MLGliomaClassification.ipynb
   ```
3. Explore sections:
   - **Data Cleaning**: See how missing values and imbalances are addressed.
   - **Model Development**: Review the steps taken to optimize classifiers.

## Key Results
- **Random Forest**:
  - Criterion: `entropy`
  - Max Depth: `7`
  - Number of Estimators: `100`
- **Ensemble Model**:
  - Combined classifiers boosted overall F1 Score to **0.92** on the test set.
- **Stratification**:
  - Custom logic ensured meaningful evaluation on imbalanced data.

---