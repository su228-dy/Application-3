# README



## Data

The dataset used in this project is sourced from the UCI Machine Learning repository and is related to the marketing of bank products over the telephone. It contains information from multiple marketing campaigns conducted by a Portuguese banking institution. This dataset includes various features, such as age, job type, marital status, balance, and previous campaign outcomes.

## Deliverables

The main deliverable of this project is a Jupyter Notebook that contains:

- **Problem Understanding**: Clearly stating the business problem of predicting the likelihood of clients subscribing to a term deposit.
- **Data Understanding and Preprocessing**: Handling missing values, converting categorical features to dummy variables, and selecting features for modeling.
- **Modeling**: Building and comparing the four classifiers (kNN, Logistic Regression, Decision Tree, and SVM) and finding the best parameters for each.
- **Evaluation and Comparison**: Evaluating models using accuracy, classification reports, and confusion matrices, and providing insights into the performance of each classifier.
- **Visualizations**: Using appropriate visualizations to compare model performances, feature correlations, and decision boundaries for the classifiers.
- **Findings and Recommendations**: Summarizing the key findings and providing actionable insights and recommendations.

The Jupyter Notebook is available in this repository and is formatted with headings, code cells, and output results to ensure clarity.

## Project Organization

- **Jupyter Notebook**: The project is presented in a Jupyter Notebook format with appropriate headings and formatting to ensure readability.
- **Directory Structure**: The repository contains only relevant files, including the dataset and the notebook, to avoid clutter.
- **Readability**: The code contains comments to explain each step, and variable names are chosen to be meaningful.

## Modeling

The following classifiers were used for comparison:

1. **K-Nearest Neighbors (kNN)**: A hyperparameter search was conducted for the optimal number of neighbors (`n_neighbors`) to achieve the best accuracy.
2. **Logistic Regression**: A standard logistic regression model was trained and evaluated.
3. **Decision Tree**: A decision tree model was built to classify the target variable.
4. **Support Vector Machines (SVM)**: An SVM model with an RBF kernel was used.

Each model's performance was evaluated using classification metrics such as accuracy, precision, recall, and F1-score. Confusion matrices and visualizations were also provided to facilitate comparison.

## Visualizations

- **Accuracy vs. Hyperparameters**: The accuracy of kNN for different values of `n_neighbors` was plotted to determine the optimal value.
- **Model Performance Comparison**: A bar plot was used to compare the accuracy of all four classifiers.
- **Confusion Matrices**: Confusion matrices were visualized for each model to show the distribution of true positive, true negative, false positive, and false negative predictions.
- **Feature Correlation**: A bar plot showing the correlation of each feature with the target variable was provided.
- **Decision Boundaries**: The decision boundaries of the models were visualized for the top two numerical features to provide insight into how each classifier differentiates between classes. However, to improve the interpretability of decision boundaries, features with the highest variance were selected instead of categorical features.

## Findings

The analysis showed that different classifiers have varying performance levels, and each model's performance depends on the characteristics of the dataset. Some key findings include:

- **kNN** achieved the highest accuracy of 89.9% with 27 neighbors.
- **Logistic Regression** and **SVM** also performed well, achieving accuracies of around 89%.
- **Decision Tree** had slightly lower performance compared to the other classifiers.

Based on the results, the **kNN** classifier is recommended for this specific dataset. However, other models such as **Logistic Regression** or **SVM** could be used depending on the complexity and interpretability requirements.


