# Personality Prediction: Introvert vs Extrovert

A comprehensive machine learning project that predicts whether a person is an introvert or extrovert based on their social behavior and personality traits. This project was developed for the 2025 Kaggle Playground Series competition.

## 🎯 Results

- **Final Score**: 0.974089
- **Best Algorithm**: Logistic Regression
- **Validation Accuracy**: 97%
- **Competition Rank**: 2025 Kaggle Playground Series

## 📊 Project Overview

Using a dataset of personality traits and social behaviors, this project systematically evaluates multiple classification algorithms to build an accurate personality type predictor. The analysis demonstrates the effectiveness of logistic regression for binary classification tasks in psychological data.

## 🔧 Technical Approach

### Data Preprocessing
- Handled missing values in categorical and quantitative columns
- Binary encoding of target variable (Extrovert=1, Introvert=0)
- Proper train-validation splits for model evaluation

### Model Selection
Evaluated 6 different classification algorithms:
- Logistic Regression ✅ (Best Performer)
- Random Forest
- AdaBoost (SAMME algorithm)
- K-Nearest Neighbors
- Gaussian Naive Bayes
- Decision Tree

### Evaluation Methodology
- Cross-validation for robust performance assessment
- Confusion matrices for detailed classification analysis
- Classification reports with precision, recall, and F1-scores
- Consistent random states for reproducible results

## 📁 Repository Structure

```
personality-prediction/
├── README.md
├── predict_introvert_extrovert.ipynb    # Complete analysis and model development
├── data/
│   ├── train.csv          # Training dataset
│   └── test.csv           # Test dataset
├── submissions/
│   └── submission.csv     # Final competition submission
└── requirements.txt       # Python dependencies
```

## 🚀 Getting Started

### Prerequisites
```bash
pip install -r requirements.txt
```

### Usage
1. Clone the repository
```bash
git clone https://github.com/yourusername/personality-prediction.git
cd personality-prediction
```

2. Install dependencies
```bash
pip install -r requirements.txt
```

3. Run the notebook
```bash
jupyter notebook predict_introvert_extrovert.ipynb
```

## 📋 Requirements

```
pandas
numpy
scikit-learn
jupyter
```

## 🔍 Key Findings

- **Simple beats complex**: Logistic regression outperformed ensemble methods
- **Data quality matters**: Proper preprocessing was crucial for model success
- **Linear relationships**: Personality traits showed strong linear separability
- **Balanced performance**: High precision and recall for both personality types

## 🏆 Competition Performance

This systematic approach to machine learning, combined with proper data handling and model evaluation, achieved excellent results in the personality prediction task with a final score of **0.974089**.

## 📈 Future Improvements

- Feature engineering from personality trait combinations
- Hyperparameter tuning for ensemble methods
- Cross-validation with stratified sampling
- Model interpretability analysis

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🤝 Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

---

**Note**: This project was developed as part of the 2025 Kaggle Playground Series competition focusing on personality prediction from behavioral data.
