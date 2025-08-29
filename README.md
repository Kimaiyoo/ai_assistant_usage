# 📊 AI Assistant Usage in Student Life – EDA & Machine Learning

This project explores how students interact with AI assistants (like ChatGPT) for academic tasks such as coding, writing, research, and brainstorming. Using a synthetic dataset of 10,000 sessions, I performed Exploratory Data Analysis (EDA), created visualizations, engineered new features, and built several machine learning models to predict:

- Whether a student will reuse the AI assistant (UsedAgain).
- The FinalOutcome of a session.

The goal is to demonstrate a complete data science workflow: from dataset exploration to building, tuning and comparing machine learning models.

## 📂 Dataset

- Synthetic dataset with 10,000 rows × 24 columns
- Captures student–AI interactions (level, discipline, task type, session length, satisfaction, outcomes, reuse behavior)
- Clean and ready-to-use (no missing values)

## 🛠️ Project Workflow
**1. Exploratory Data Analysis (EDA)**  
- Checked dataset structure, datatypes, distributions  
- Explored session patterns (levels, disciplines, tasks)  
- Visualized outcomes, satisfaction, and correlations  

**2. Feature Engineering**  
- Encoded categorical features (Label & One-Hot Encoding)  
- Extracted date features (Year, Month, Day)  
- Created new features (e.g., Prompts per Minute, Session Bins)  

**3. Machine Learning Models**  

Trained and evaluated multiple classifiers:  
- Logistic Regression  
- Decision Tree & Random Forest  
- Naive Bayes  
- K-Nearest Neighbors (KNN)  
- Gradient Boosting & XGBoost  

**4. Model Evaluation & Tuning**  
- Train/test split and cross-validation  
- Metrics: Accuracy, Precision, Recall, F1-score  
- Hyperparameter tuning with GridSearchCV  
- Compared model performance on predicting `UsedAgain`
  
## 📊 Example Results

- Logistic Regression: balanced but slightly lower accuracy
- Decision Tree: high variance, moderate performance
- Random Forest: better generalization with tuning
- KNN: biased towards majority class
- Gradient Boosting & XGBoost: best overall performance for UsedAgain

## 🚀 Possible Use Cases

1. Educational analytics
2. Modeling student engagement with AI
3. Practicing EDA, feature engineering and ML pipelines
4. Benchmarking model performance across algorithms

## 📌 How to Run the Project

1. Clone the repository:
``` bash
git clone https://github.com/yourusername/ai-assistant-student-life.git
cd ai-assistant-student-life
```

2. Install dependencies:
```bash
pip install -r requirements.txt
````

3. Open Jupyter Notebook / Colab and run the notebooks step by step.

## 📦 Tech Stack

- Python (Pandas, NumPy, Matplotlib, Seaborn)
- Scikit-learn (EDA, preprocessing, ML models, evaluation)
- XGBoost (boosted trees for classification)

## 📜 License

MIT License – free to use, modify and distribute.

## 👤  Author

👩‍💻 Developed by [Kimaiyoo](https://github.com/Kimaiyoo) – as part of a data science practice project.
