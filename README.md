# ML Final Project – How to Run the Code

This repository contains source code and prediction outputs for our Machine Learning final project:

- **Part 1 – Multi-Dataset Classification**
- **Part 2 – Spam Email Detection**

Both parts are implemented in Jupyter Notebooks and produce the required `.txt` prediction files for submission.

---

## Folder Structure

```
ML PROJECT/
├── classification/
│   ├── TestData1.txt
│   ├── TestData2.txt
│   ├── TestData3.txt
│   ├── TestData4.txt
│   ├── TrainData1.txt
│   ├── TrainData2.txt
│   ├── TrainData3.txt
│   ├── TrainData4.txt
│   ├── TrainLabel1.txt
│   ├── TrainLabel2.txt
│   ├── TrainLabel3.txt
│   ├── TrainLabel4.txt
│   ├── classification.ipynb
│   ├── NguyenClassification1.txt
│   ├── NguyenClassification2.txt
│   ├── NguyenClassification3.txt
│   ├── NguyenClassification4.txt
│
├── Spam Email Detection/
│   ├── spam_test.csv
│   ├── spam_train1.csv
│   ├── spam_train2.csv
│   ├── NguyenSpam.txt
│
├── spam_detection.ipynb
├── Final_Report_3Pages.docx
└── README.md   (this file)
```

---

## Requirements

You need:

- Python 3.x  
- Jupyter Notebook  
- Install required libraries:

```bash
pip install numpy pandas scikit-learn nltk
```

If using Anaconda:

```bash
conda install scikit-learn nltk pandas numpy
```

---

## 🏁 How to Run Part 1 — Classification

1) Open the terminal and launch Jupyter:

```bash
jupyter notebook
```

2) Open:

```
classification/classification.ipynb
```

3) Ensure dataset files are already located inside the `classification/` folder.

4) Run all cells:

```
Kernel → Restart & Run All
```

5) At the end, prediction output files appear automatically:

```
NguyenClassification1.txt
NguyenClassification2.txt
NguyenClassification3.txt
NguyenClassification4.txt
```

---

## How to Run Part 2 — Spam Detection

1) Launch:

```bash
jupyter notebook
```

2) Open:

```
spam_detection.ipynb
```

3) Ensure dataset files are inside:

```
Spam Email Detection/
    spam_train1.csv
    spam_train2.csv
    spam_test.csv
```

4) Run all cells:

```
Kernel → Restart & Run All
```

5) Output generated:

```
NguyenSpam.txt
```

---

## Final Submission Files

Submit:

```
NguyenClassification1.txt
NguyenClassification2.txt
NguyenClassification3.txt
NguyenClassification4.txt
NguyenSpam.txt
Final_Report_3Pages.docx
```

---

## ✔ Author
Son Nguyen, Harry Cao, Maria Ferdous
