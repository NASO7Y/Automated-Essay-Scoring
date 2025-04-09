# 📝 Automated Essay Scoring 

This project presents a **Machine Learning and NLP-based solution for Automated Essay Scoring (AES)**. It simulates the grading of essays written in natural language, using a range of linguistic and statistical features to predict scores — closely mimicking human evaluation.

🔗 [View the Notebook](https://github.com/NASO7Y/Automated-Essay-Scoring/blob/main/Automated-Essay-Scoring-NLP-ML.ipynb)

---

## 📌 Project Overview

Automated Essay Scoring (AES) refers to the use of machine learning and NLP techniques to automatically grade essays. In this project, we create a **synthetic dataset** that mimics real student essays, complete with scores, grammar mistakes, and varying writing styles.

The notebook:
- Generates a dataset of artificial essays.
- Extracts linguistic, statistical, and readability features.
- Trains machine learning models to predict scores.
- Evaluates the models using standard metrics.

---

## 🚀 Technologies Used

- **Python 3.9**
- **Pandas, NumPy** – data handling
- **NLTK, TextStat** – NLP and readability analysis
- **Scikit-learn** – model training and evaluation
- **Matplotlib, Seaborn** – visualizations

---

## 📂 Dataset

Unlike traditional AES projects that rely on external datasets (like those from Kaggle), this project **generates a synthetic dataset** of essays directly within the code. Each generated essay includes:

- Essay text  
- A synthetic score (based on quality metrics)  
- Artificial errors (spelling, grammar, etc.)

This allows flexibility and full control over feature distribution and label generation for experimentation.

---

## 🔍 Key Features Extracted

- **Grammatical Features**: Parts-of-speech tagging, grammar errors  
- **Lexical Richness**: Word diversity, sentence structure  
- **Readability Scores**: Flesch Reading Ease, Gunning Fog Index  
- **Spelling Errors**: Introduced intentionally for training  
- **Essay Length & Structure**: Number of sentences, words, characters

---

## 🤖 Models Used

- **Linear Regression**
- **Random Forest Regressor**
- **Gradient Boosting Regressor**
- **Support Vector Regressor (SVR)**

### Evaluation Metrics:
- **Mean Squared Error (MSE)**
- **R² Score**

---

## 🧪 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/NASO7Y/Automated-Essay-Scoring.git
   cd Automated-Essay-Scoring
   ```

2. Install the required packages:
   ```bash
   pip install -r requirements.txt
   ```

3. Launch the notebook:
   ```bash
   jupyter notebook Automated-Essay-Scoring-NLP-ML.ipynb
   ```

### ⚠️ Notes:
- Make sure to download required **NLTK resources** before running:
  ```python
  import nltk
  nltk.download('punkt')
  nltk.download('averaged_perceptron_tagger')
  nltk.download('stopwords')
  ```

- Download **spaCy English model** if not already installed:
  ```bash
  python -m spacy download en_core_web_sm
  ```

  
---

## 📬 Contact

📧 [LinkedIn](linkedin.com/in/nos7y/)  
🔗 [GitHub](https://github.com/NASO7Y)
