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
│── notebooks/          # Jupyter Notebooks for data analysis and model training
│── models/             # Trained ML models
│── results/            # Prediction results and evaluation reports
│── README.md           # Project documentation
│── requirements.txt    # Dependencies
│── main.py             # Main script to run the predictions
```

## ⚙️ Installation & Setup

### 1️⃣ Install Dependencies
- Ensure you have Python installed, then run:

```sh
pip install -r requirements.txt
```

### 2️⃣ Run Software Defect Prediction
- Use the following command to execute the main script:

```sh
python main.py
```

### 3️⃣ Data Analysis & Visualization
- For detailed analysis and visualization, open the Jupyter Notebook:

```sh
jupyter notebook
```

## 📊 Machine Learning Models
- The project explores different supervised learning models to predict software defects:

  - ✅ Random Forest 🌳
  - ✅ Support Vector Machine (SVM) 📈
  - ✅ Neural Networks (MLP, LSTM) 🤖
  - ✅ Gradient Boosting (XGBoost, LightGBM, CatBoost) 🚀
- Each model is evaluated based on:

  - Accuracy 🎯
  - Precision & Recall 📊
  - F1-score ⚖️
  - ROC-AUC Score 📈
  - 🔬 Results & Insights
- Our experiments show that ensemble methods (Random Forest, XGBoost) and deep learning models (MLP, LSTM) perform well on defect prediction tasks. The results are saved in the results/ folder for further analysis.

## 📌 Future Improvements
- 🏗 Feature Engineering: Improve feature extraction for better defect prediction.
- 🔄 Automated Model Selection: Implement hyperparameter tuning for optimal results.
- ☁️ Deploy as a Web App: Build an interactive dashboard for real-time defect analysis.
## 📩 Contact
- ✍️ Authors: Kiều Giang Biên.
- 🌍 GitHub: [BienKieu1411](https://github.com/BienKieu1411)
- 📧 Email: bienkieugiang@gmail.com
