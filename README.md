# ML-model_Drug_analysis.
End-to-end ML pipeline demonstrating data preparation, model training, evaluation, and interpretability for drug expression datasets.
Step 1: Data Preparation

Load dataset (.csv format).

Separate features (X) and target variable (y).

Encode categorical target (e.g., High = 1, Low = 0).

Handle missing values and check class distribution.

Step 2: Train-Test Split

Split the dataset into training and test sets using train_test_split (80/20 split).

Step 3: Model Training

Base model: RandomForestClassifier.

Hyperparameter tuning using GridSearchCV or RandomizedSearchCV.

Selected best model using cross-validation accuracy.

Step 4: Model Evaluation

Accuracy, precision, recall, F1-score.

Confusion matrix and classification report.

ROC curve and AUC score.

Step 5: Feature Importance

Extract feature importances from tuned RandomForest model.

Plot ranked features to identify top contributors.

Step 6: PCA Visualization

Standardize features using StandardScaler.

Apply PCA (2D) for dimensionality reduction.

Scatter plot to visualize clustering of drug classes (e.g., Upregulated vs Downregulated).

Step 7: Final Outputs

Feature importance bar chart showing top predictors.

PCA plot visualizing data separability.

Saved model (best_model.pkl) for reproducibility.

Tech Stack

Language: Python 3.11+

Core Libraries:

pandas, numpy (data manipulation)

scikit-learn (ML models, tuning, evaluation, PCA)

matplotlib, seaborn (visualization)
