# 🌸 Iris Flower Classification

A Machine Learning classification project that predicts the species of an Iris flower using **Logistic Regression** and **K-Nearest Neighbors (KNN)**. The project includes EDA, model evaluation, and a **Streamlit web application**.

## 📌 Project Overview

The system classifies Iris flowers into:

* Iris Setosa
* Iris Versicolor
* Iris Virginica

Using four features:

* Sepal Length
* Sepal Width
* Petal Length
* Petal Width

## 🧠 Machine Learning Workflow

```text
                    ┌─────────────────────┐
                    │   Iris Dataset      │
                    └──────────┬──────────┘
                               │
                               ▼
                    ┌─────────────────────┐
                    │ Data Preparation    │
                    │ & Exploration       │
                    └──────────┬──────────┘
                               │
                               ▼
                    ┌─────────────────────┐
                    │ Exploratory Data    │
                    │ Analysis (EDA)      │
                    └──────────┬──────────┘
                               │
                               ▼
                    ┌─────────────────────┐
                    │ Train/Test Split    │
                    │       80 / 20       │
                    └──────────┬──────────┘
                               │
                    ┌──────────┴──────────┐
                    ▼                     ▼
          ┌─────────────────┐   ┌─────────────────┐
          │ Logistic        │   │ K-Nearest       │
          │ Regression      │   │ Neighbors       │
          └────────┬────────┘   └────────┬────────┘
                   │                     │
                   └──────────┬──────────┘
                              ▼
                    ┌─────────────────────┐
                    │ Model Evaluation    │
                    │ Accuracy            │
                    │ Confusion Matrix    │
                    │ Classification      │
                    │ Report              │
                    └──────────┬──────────┘
                               │
                               ▼
                    ┌─────────────────────┐
                    │ Streamlit Web App   │
                    └─────────────────────┘
```

---

## 📊 Dataset

Built-in **Iris dataset from Scikit-learn**:

* 150 samples
* 4 numerical features
* 3 classes
* 50 samples per class
* Stratified 80/20 train-test split

## 🔍 EDA

The project includes:

* Dataset inspection
* Missing-value analysis
* Descriptive statistics
* Class distribution
* Pairplot
* Feature box plots

## 🤖 Models

### Logistic Regression

```python
LogisticRegression(random_state=42, max_iter=200)
```

### K-Nearest Neighbors

```python
KNeighborsClassifier(n_neighbors=5)
```

## 📈 Evaluation

Models are evaluated using:

* Accuracy
* Confusion Matrix
* Precision
* Recall
* F1-score

## 🌐 Streamlit App

The application provides four sections:

1. **Prediction** — Enter flower measurements and predict its species.
2. **Dataset** — View dataset information and statistics.
3. **EDA** — Explore pairplots, box plots, and missing values.
4. **Model Evaluation** — Compare model performance.

## 🛠️ Technologies

* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* Seaborn
* Streamlit

## 📁 Project Structure

```text
Iris-Classification/
├── app.py
├── Iris_Classification_Project.ipynb
├── requirements.txt
├── README.md
└── venv/
```

> Add `venv/` to `.gitignore` before pushing to GitHub.

## ⚙️ Installation

```bash
git clone https://github.com/yourusername/iris-classification.git
cd iris-classification

python -m venv venv
venv\Scripts\activate       # Windows

pip install -r requirements.txt
```

## ▶️ Run

```bash
streamlit run app.py
```

Open:

```text
http://localhost:8501
```

## 💡 Key Learning Outcomes

* Supervised Machine Learning
* Multi-class Classification
* EDA & Data Visualization
* Train-Test Splitting
* Logistic Regression
* KNN
* Model Evaluation
* Streamlit Deployment

## 🚀 Future Improvements

* Add Random Forest, SVM, Decision Tree, and Naive Bayes
* Hyperparameter tuning
* Cross-validation
* Feature-scaling pipelines
* Model persistence
* Automated testing
* Docker & CI/CD
* Cloud deployment

## 👨‍💻 Author

**Sarfraz Ali Katpar**
Computer Science Student | AI/ML

**Areas:** AI, Machine Learning, Deep Learning, NLP, Generative AI, LLMs, Data Science

## 📚 Academic Information

**Course:** Data Science
**University:** Sukkur IBA University
**Instructor:** Dr. Muhammad Ismail
**Semester:** BSCS-V

## 📄 License

For educational and academic purposes.

## ⭐ Acknowledgements

Thanks to **Scikit-learn, Pandas, NumPy, Matplotlib, Seaborn, and Streamlit**.
