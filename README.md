# 🚀 Automated Software Fault Detection using Machine Learning and Feature Selection

A comprehensive study integrating **machine learning classifiers** with **feature selection techniques** for efficient and automated **software fault detection** using the NASA MDP dataset. This project also introduces a **custom ensemble approach** to further improve detection accuracy and system robustness.

---

## 📚 Table of Contents

* [Project Overview](#project-overview)
* [Key Features](#key-features)
* [Research Contributions](#research-contributions)
* [Feature Selection Techniques](#feature-selection-techniques)
* [Classifiers Used](#classifiers-used)
* [Tool Implementation](#tool-implementation)
* [Dataset](#dataset)
* [Results and Analysis](#results-and-analysis)
* [Technologies Used](#technologies-used)
* [How to Run](#how-to-run)
* [Challenges and Limitations](#challenges-and-limitations)
* [Future Improvements](#future-improvements)
* [References](#references)

---

## 🧠 Project Overview

This project addresses the persistent issue of **software fault detection** by applying **machine learning techniques** to detect anomalies and bugs automatically. The effectiveness of such techniques depends heavily on selecting the **most relevant features** from large datasets.

We explore various **feature selection techniques** in conjunction with popular **ML classifiers** to determine optimal configurations for fault prediction. Additionally, we develop a **custom ensemble model** to enhance detection accuracy.

---

## ✨ Key Features

* Feature selection using **SelectKBest, Lasso, RFE, Greedy Forward Selection**
* Machine learning classifiers: **XGBoost, SVM, Random Forest, Naive Bayes, ANN**
* Custom ensemble method for improved performance
* Visual comparison of classifier performance (with and without feature selection)
* Interactive Python-based implementation with visualization support
* Easy-to-use custom tool for experimentation

---

## 📌 Research Contributions

* Conducted in-depth experimentation with **feature selection techniques**
* Performed comparative analysis of different **ML classifiers**
* Introduced a **novel ensemble method** for fault detection
* Built a custom tool to automate testing, analysis, and visualization

---

## 🔍 Feature Selection Techniques

* **SelectKBest with f\_classif**
* **Lasso (L1 Regularization)**
* **Recursive Feature Elimination (RFE)**
* **Greedy Forward Selection (GFS)**

---

## 🤖 Classifiers Used

* **XGBoost**
* **Support Vector Machines (SVM)**
* **Random Forest**
* **Naïve Bayes**
* **Artificial Neural Networks (ANN)**

---

## 🛠️ Tool Implementation

The implemented tool allows users to:

* Load and preprocess datasets
* Apply various feature selection techniques
* Run classifiers individually or as part of the ensemble
* Visualize results (accuracy, precision, recall, F1-score)

---

## 📊 Dataset

We use the **NASA Metrics Data Program (MDP)** dataset, a trusted and widely used benchmark for software fault detection research.

---

## 📈 Results and Analysis

* Performance metrics: **Accuracy, Precision, Recall, F1-score**
* Comparison between different feature selection techniques
* Ensemble model outperforms individual classifiers in multiple scenarios

---

## 💻 Technologies Used

* **Python**
* Libraries:

  * `scikit-learn`
  * `xgboost`
  * `numpy`, `pandas`
  * `matplotlib`, `seaborn`
  * `Tkinter` (for UI)

---

## 🧪 How to Run

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/your-repo-name.git
   cd your-repo-name
   ```

2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Run the main script:

   ```bash
   python main.py
   ```

4. Follow the GUI or CLI prompts to load the dataset and start testing.

---

## ⚠️ Challenges and Limitations

* Class imbalance in the dataset
* High-dimensional feature space
* Limited generalizability to non-NASA datasets
* Training time for deep learning models

---

## 🔭 Future Improvements

* Extend to cross-project defect prediction
* Integrate more advanced ensemble strategies
* Deploy as a web-based or cloud application
* Evaluate on additional real-world datasets

---

## 📚 References

* NASA Metrics Data Program (MDP)
* Scikit-learn Documentation
* XGBoost Documentation
* Research papers from IEEE, Springer, and Elsevier on software fault prediction

---

> 💡 This project is developed for academic research and experimentation. Contributions and feedback are welcome!
