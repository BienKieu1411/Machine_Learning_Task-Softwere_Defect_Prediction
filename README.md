# 🔍 Software Defect Prediction 🖥️📊

## 🚀 Introduction

- Software defect prediction plays a crucial role in software engineering by identifying potential defects in code before deployment. This project leverages Machine Learning (ML) models to analyze historical software versions and predict the likelihood of defects in new versions.

- We use two well-known datasets:

  - 📂 dataNASA: Contains defect data from NASA's software projects.
  - 📂 dataPROMISE: Consists of defect data from open-source software projects.

- By training models on these datasets, we aim to improve software reliability and quality assurance.

## 🛠️ Technologies Used

- This project is built using:

  - Programming Language: Python 🐍
  - Machine Learning Libraries: Scikit-learn, TensorFlow, PyTorch
  - Data Processing & Visualization: Pandas, NumPy, Matplotlib, Seaborn
  - Notebook Environment: Jupyter Notebook

## 📂 Project Structure

```bash
Software_Defect_Prediction/
│── dataNASA/           # NASA defect datasets
│── dataPROMISE/        # PROMISE defect datasets
│── Software_Defect/    # Jupyter Notebooks for data analysis and model training
│── dataPROMISE_results/# Prediction results and evaluation reports
│── dataNASA_results/   # Prediction results and evaluation reports
│── README.md           # Project documentation
│── requirements.txt    # Dependencies
```

## ⚙️ Installation & Setup

### 1️⃣ Install Dependencies
- Ensure you have Python installed, then run:

```sh
pip install -r requirements.txt
```

### 2️⃣ Run Software Defect Prediction

- Open the Jupyter Notebook to start the analysis:

```sh
jupyter notebook
```

## 📊 Machine Learning Models
- The project explores different supervised learning models to predict software defects:

- Ensemble Learning Approach: The models are combined using stacking to enhance prediction performance.

- Each model is evaluated based on:

  - Accuracy 🎯

  - Precision & Recall 📊

  - F1-score ⚖️

- Experimental Approach:

  - Preprocessing

  - Cross-validation training:

    - For dataPROMISE: Use cross-project training for single-version projects and train on previous versions for multi-version projects.

    - For dataNASA: Use cross-validation for all files.

  - Techniques applied:

    - Sampling

    - Weighted Learning

    - Feature Selection

- Model evaluation by combining different techniques and analyzing their impact on performance.

## 📌 Future Improvements
- 🏗 Feature Engineering: Improve feature extraction for better defect prediction.
- 🔄 Automated Model Selection: Implement hyperparameter tuning for optimal results.
- ☁️ Deploy as a Web App: Build an interactive dashboard for real-time defect analysis.
## 📩 Contact
- ✍️ Authors: Kiều Giang Biên.
- 🌍 GitHub: [BienKieu1411](https://github.com/BienKieu1411)
- 📧 Email: bienkieugiang@gmail.com
