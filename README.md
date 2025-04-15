# 🍄 Mushroom Classification - Edible vs. Poisonous

This project uses a large mushroom dataset to build classification models that predict whether a given mushroom is **edible** or **poisonous**, based on its physical characteristics. The dataset contains approximately 60,000 entries with various categorical features.

Dataset source:  
🔗 [Kaggle - Mushroom Dataset](https://www.kaggle.com/datasets/dhinaharp/mushroom-dataset)  
🔗 [Kaggle - UCI Mushroom Classification (Feature Descriptions)](https://www.kaggle.com/datasets/uciml/mushroom-classification)

## 📁 Contents

- `mushrooms.csv`: Dataset used for training and evaluation.
- `mushroom_classification.ipynb`: Jupyter Notebook containing data preparation, model training, evaluation, and results.
- `README.md`: Project overview and documentation.

## 🎯 Objective

The main goal is to build and evaluate machine learning models that can accurately classify mushrooms as either **edible** or **poisonous**, based solely on their attributes.

The following components are included:

1. 🔍 **Data Preparation**
   - Handle missing values
   - Encode categorical features (e.g., via one-hot encoding)
   - Perform sanity checks and exploratory analysis

2. 🤖 **Classification Models**
   - Logistic Regression (**required** baseline)
   - Additional model (e.g., Random Forest, Decision Tree, SVM, etc.)

3. 📈 **Evaluation**
   - Discuss and justify the **most relevant performance metric** (e.g., F1-score for imbalanced classes, precision/recall tradeoff, etc.)
   - Generate and interpret **confusion matrices**

4. 🛠️ **Model Validation**
   - Apply two distinct **hyperparameter tuning methods**:
     - Grid Search with Cross-Validation (e.g., `GridSearchCV`)
     - Train/validation/test split or stratified K-Fold

## 🧪 Tools & Libraries

- Python 3.x
- Jupyter Notebook
- pandas, numpy
- scikit-learn
- seaborn, matplotlib

## ✅ Getting Started

1. Clone the repository or download the notebook and data manually:
   ```bash
   git clone https://github.com/nural7h/mushroom-foraging-ml
