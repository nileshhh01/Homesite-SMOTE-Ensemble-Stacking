# SMOTE & Ensemble Stacking for Kaggle Insurance Quote Prediction 📈🏠

This project tackles the *Homesite Quote Conversion* Kaggle competition using advanced machine learning techniques including **SMOTE for handling class imbalance** and **stacked ensemble learning** with multiple classifiers.

## 🎯 Objective
Predict the probability that a customer will purchase a quoted insurance plan using:
- SMOTE to address class imbalance
- Ensemble stacking of 5 classifiers
- Kaggle leaderboard evaluation

## 📂 Files
- `SMOTE ENSEMBLE PREDICTION.ipynb`: Main notebook with all code and analysis
- `RevisedHomesiteTrain1.csv` / `NewHomesiteTrain.csv`: Preprocessed training data
- `RevisedHomesiteTest1.csv` / `NewHomesiteTest.csv`: Preprocessed test data
- `README.md`: Project summary
- `.gitignore`: System and environment file ignore list
- `requirements.txt`: All dependencies

## ⚙️ Methods Used
- **SMOTE (Synthetic Minority Over-sampling Technique)**
- **Stacking** with:
  - Decision Tree
  - Random Forest
  - SVM
  - Multilayer Perceptron
  - K-Nearest Neighbors
- **Hyperparameter Tuning** (for the stacked model)
- **Kaggle submission** with leaderboard evaluation

## 🛠️ Libraries
- `imbalanced-learn`
- `scikit-learn`
- `pandas`, `numpy`
- `vecstack` (optional for stacking)
- `matplotlib`, `seaborn`
- `jupyter`

## 📊 Results
- SMOTE improved minority class F1-score significantly
- Ensemble stacking improved accuracy and ROC AUC
- Final Kaggle score: [Insert your score here]
- Detailed results in submission table (Excel)

## 🚀 Running the Project

```bash
# Clone the repo
git clone https://github.com/yourusername/homesite-smote-ensemble-stacking.git

# Install dependencies
pip install -r requirements.txt

# Launch notebook
jupyter notebook
