# CardioPredict: Heart Disease Prediction System 🚑💖

## Overview

Heart disease is one of the leading causes of death worldwide. Timely detection through data analysis and machine learning can significantly reduce risks and improve patient outcomes. This project explores the **Heart Disease Prediction** problem using machine learning to predict the likelihood of heart disease based on various health parameters.

### 🎯 Project Objectives:
- **Identify Key Predictive Features**: Pinpoint significant factors that contribute to heart disease risk.
- **Evaluate Predictive Models**: Build, compare, and evaluate machine learning models for heart disease prediction.

## 🚀 Dataset

The data for this project comes from the **UCI Machine Learning Repository**:  
[Heart Disease Data](https://archive.ics.uci.edu/ml/datasets/Heart+Disease).

### Key Features:
- **Age**: The individual's age.
- **Sex**: Gender of the individual.
- **Chest Pain Type**: Type of chest pain experienced.
- **Resting Blood Pressure**: Blood pressure at rest.
- **Cholesterol**: Serum cholesterol level.
- **Max Heart Rate**: Maximum heart rate achieved during exercise.
- **Exercise-induced Angina**: Angina experienced during exercise.
- **Number of Major Vessels**: Number of colored vessels observed by fluoroscopy.
- **Thallium Stress Test**: Results from thallium stress test.

## 🛠 Installation

### 1. Clone the Repository

Start by cloning this repository to your local machine:

```bash
git clone https://github.com/Astrolaboratory/Portfolio.git
```

### 2. Set Up Python Environment

It is recommended to use a **virtual environment**:

```bash
python -m venv venv
```

Activate it:

- **Windows**:
  ```bash
  venv\Scripts\activate
  ```
- **macOS/Linux**:
  ```bash
  source venv/bin/activate
  ```

### 3. Install Dependencies

Install the required libraries:

```bash
pip install -r requirements.txt
```

## 🔍 Project Workflow

### 1. Data Collection
We used the **Heart Disease Data** from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Heart+Disease).

### 2. Data Cleaning and Preprocessing
The dataset was preprocessed as follows:
- **Renamed Columns** for better understanding.
- **Handled Missing Data** via imputation/removal.
- **Encoded Categorical Variables** using numeric values.

### 3. Exploratory Data Analysis (EDA)
Key insights from EDA:
- **Age**: Older individuals are more likely to have heart disease.
- **Sex**: Males tend to have a higher risk than females.
- **Chest Pain**: Individuals with certain types of chest pain have a higher likelihood of heart disease.
- **Maximum Heart Rate**: Those with heart disease often have lower maximum heart rates during exercise.

### 4. Data Visualizations

#### 📊 Age Distribution vs Heart Disease

Age Distribution vs Heart Disease Sex Distribution vs Heart DiseaseResting Blood Pressure Distribution vs Heart DiseaseCholesterol Distribution vs Heart DiseaseMaximum Heart Rate Distribution vs Heart DiseaseCorrelation Heatmap

![Age vs Heart Disease](https://github.com/user-attachments/assets/04c47b57-754a-4fdd-848f-800201460283)

#### 📊 Sex Distribution vs Heart Disease
![Sex vs Heart Disease](https://github.com/user-attachments/assets/d38cb64c-7b15-4542-8ac7-40264fc35537)

#### 📊 Resting Blood Pressure Distribution vs Heart Disease
![Sex vs Heart Disease](https://github.com/user-attachments/assets/6832ac39-8af5-461a-8040-030e927df5eb)

#### 📊 Cholestrol Distribution vs Heart Disease
![Cholestrol Distribution vs Heart Disease](https://github.com/user-attachments/assets/4b4c7f45-3607-407e-86ce-83f93e6888b2)

#### 📊 Maximum Heart Rate Distribution vs Heart Disease
![Max Heart Rate vs Heart Disease](https://github.com/user-attachments/assets/1313296a-7de4-47dd-93c8-b10c8ecacd62)

#### 🧠 Correlation Heatmap
![Correlation Heatmap](https://github.com/user-attachments/assets/40a8e710-1a6c-4d7d-ac2d-e177a2526e8b)

### 5. Predictive Modeling

We built and evaluated the following models:
- **Logistic Regression**: A linear model for binary classification.
- **Decision Tree Classifier**: A decision tree-based approach for classification.

| Model               | Accuracy | Precision | Recall | F1-Score |
|---------------------|----------|-----------|--------|----------|
| Logistic Regression | 88.33%   | 0.89      | 0.83   | 0.85     |
| Decision Tree       | 83.33%   | 0.86      | 0.79   | 0.83     |

### 🏆 Conclusion

- **Key Findings**: Age, sex, chest pain type, and exercise-induced angina are significant predictors of heart disease.
- **Top Performing Model**: Logistic Regression achieved slightly better performance in terms of accuracy and precision.

## 🔮 Next Steps

1. **Explore Advanced Models**: Implement Random Forests, Support Vector Machines, and Gradient Boosting.
2. **Hyperparameter Tuning**: Use GridSearchCV to optimize model parameters.
3. **Cross-Validation**: Implement K-fold cross-validation to improve model generalization.
4. **Model Interpretability**: Use SHAP or LIME for better explainability of model predictions.
5. **Deployment**: Build a web app to allow healthcare professionals to use the predictive model.

## 👨‍💻 Acknowledgments

- **Dataset**: [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Heart+Disease).
- **Libraries**:
  - Python
  - Pandas
  - NumPy
  - Matplotlib & Seaborn
  - Scikit-learn
  - Jupyter Notebook

## 📜 License

This project is licensed under the **[Creative Commons Attribution 4.0 International License](https://creativecommons.org/licenses/by/4.0/)**. Feel free to share and adapt the project with appropriate attribution.

---

## 📞 Contact Information

Feel free to reach out with any questions, feedback, or collaboration ideas. I am always open to new opportunities and discussions! 💬

---

### 👨‍💻 Ketan N  
📧 [Astronix@protonmail.com](mailto:Astronix@protonmail.com)  
🔗 [LinkedIn Profile](https://www.linkedin.com/in/ketannirpagare/)  
🌍 [GitHub Profile](https://github.com/Astrolaboratory/Portfolio)

---

### 📍 Let's Connect:
- 💼 **Open to job opportunities and freelance projects**!
- 🌱 Always learning new technologies and exploring innovative ways to leverage data for real-world solutions.

---

### 🔥 Fun Fact:
> **"I believe that the intersection of healthcare and technology will drive the future of data science, and I'm passionate about using data to improve patient outcomes."**

---

### 💬 How Can I Help You?
If you're looking for someone with hands-on experience in:
- **Data Science & Machine Learning** 🧠
- **Predictive Modeling** 📊
- **Healthcare Data Analysis** 💉
- **Artificial Intelligence (AI)** 🤖

I’d love to discuss how we can collaborate and create impactful solutions!

---
