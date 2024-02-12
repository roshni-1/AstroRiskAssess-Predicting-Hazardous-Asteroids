# AstroRiskAssess-Predicting-Hazardous-Asteroids

The project aims to understand, analyze, and predict the characteristics of asteroids, with a specific focus on identifying potential hazardous ones.

## Loading the Dataset:
The dataset was downloaded from kaggle Nasa Asteroids Dataset[/kaggle/input/nasa-asteroids-dataset/Nasa_Asteroids_Data.csv]. 

## Exploratory Data Analysis (EDA):

- I performed exploratory data analysis to understand the dataset's structure, check for missing values, and explore the distribution of various features.
- Visualization techniques, including histograms, pair plots, radar charts, 3D scatter plots etc, were used to gain insights into the dataset.

## Data Preprocessing:

- Identified the relevant columns for our analysis, including features and the target variable.
- Categorical variables were converted into numerical representations (e.g., using Label Encoding for binary categories).
- Split the dataset into features (X) and the target variable (y) and performed train-test split.

## Scaling the Features:

- Features were scaled using StandardScaler to ensure consistent scales for modeling.

## Model Selection and Training:

- Explored 3 models Logistic Regression, Random Forest, and Gradient Boosting.
- Finalized  Gradient Boosting model for classification.
- The model was trained on the training set using the GradientBoostingClassifier from scikit-learn.

## Model Evaluation:

- Evaluated the model's performance on the test set using various metrics, including accuracy, precision, recall, and F1 score.
- ROC curves and precision-recall curves were plotted for additional insights into model performance.

## Adjusting Threshold for Prediction:
- The threshold for classification was adjusted to find a balance between precision and recall.
- Selected a threshold that aligned with the desired trade-off

## Making Predictions on the Entire Dataset:
 - The final model, with the adjusted threshold, was applied to make predictions on the entire dataset.

## Saving Predictions to CSV:

- The dataset with actual and predicted labels was saved to a CSV file for further analysis or reporting.

## Conclusion 
The AstroRiskAssess project has provided valuable insights into predicting hazardous asteroids using the NASA Asteroids Dataset. Throughout the journey, I performed a comprehensive analysis, explored various machine learning models, and created an interactive visualization dashboard.

