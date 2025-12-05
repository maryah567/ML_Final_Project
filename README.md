<div id="top">

<div align="center">

<img src="https://shiftasia.com/community/content/images/2025/06/ml.png" width="30%" alt="Project Logo"/>

# ML_FINAL_PROJECT

**Machine Learning Final Project – Multi-Dataset Classification & Spam Email Detection**

</div>
<br>

---

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Project Structure](#project-structure)
- [Getting Started](#getting-started)
- [Roadmap](#roadmap)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgments](#acknowledgments)

---

## Overview

This project implements two major machine learning tasks:

### 🔹 1) Multi-Dataset Classification  
We classify unseen test samples from **four unique datasets** with different:
- Dimensions  
- Numbers of classes  
- Samples vs. features imbalance  

Pipeline includes:
- Missing value imputation  
- Scaling and normalization  
- Dimensionality reduction (SelectKBest / PCA)  
- Optimal model selection per dataset  

**Best results:**
- Dataset 1 → **96%**
- Dataset 2 → **91%**
- Dataset 3 → ~72%
- Dataset 4 → ~53% (feature-limited dataset)

---

### 🔹 2) Spam Email Detection  
Goal: classify messages as **Spam** or **Ham** using NLP.

Pipeline includes:
- Text cleaning
- TF-IDF vectorization (20,000 features)
- Model benchmarking (NB, DT, NN, SVM)
- Hyperparameter tuning

**Best tuned model:** **SVM**
- **AUC: 0.9965**
- **F1 Score: 0.943**
- **Precision: 0.951**
- **Recall: 0.936**

---

## Features

✔ Adaptive preprocessing  
✔ SelectKBest & PCA  
✔ RandomForest / KNN / SVM / Ensembles  
✔ TF-IDF NLP text modeling  
✔ Cross-validation + tuning  
✔ Prediction outputs for submission  

---

## Project Structure

```sh
└── ML_FINAL_PROJECT/
    ├── classification.ipynb     # Multi-dataset classification pipeline
    ├── spam_detection.ipynb     # NLP spam filtering pipeline
    ├── Final_Report_3Pages.docx # Project report
    └── README.md
Project Index
<details open> <summary><b><code>C:\USERS\GITHUB\ML_FINAL_PROJECT/</code></b></summary> <blockquote> <table> <thead> <tr> <th>File Name</th> <th>Summary</th> </tr> </thead> <tr> <td><b>classification.ipynb</b></td> <td>Classification using imputation, scaling, PCA/SelectKBest, tuned models</td> </tr> <tr> <td><b>spam_detection.ipynb</b></td> <td>TF-IDF text processing, multiple ML models, SVM tuning</td> </tr> </table> </blockquote> </details>
Getting Started
Prerequisites
Python 3.x

Jupyter Notebook

scikit-learn, pandas, numpy, nltk

Installation
sh
Copy code
git clone <REPO-URL>
cd ML_FINAL_PROJECT
pip install -r requirements.txt
Usage
sh
Copy code
jupyter notebook
Open notebooks:

classification.ipynb

spam_detection.ipynb

Testing
All validation/testing done inside notebook execution.

Roadmap
 Classification pipeline implementation

 Spam detection pipeline implementation

 Automated hyperparameter search

 Deploy via REST API

 Dashboard reporting

Contributing
Contributions are welcome.

<details closed> <summary>Contributing Guidelines</summary>
Fork repository

Create new feature branch

Implement and test locally

Push and submit PR

</details>
License
Distributed under the MIT License.
See LICENSE for more information.

Acknowledgments
Team: Harry Cao, Maria Ferdous, Son Nguyen

Machine Learning Course Project

Scikit-learn & NLP toolkits

<div align="right">


</div>
