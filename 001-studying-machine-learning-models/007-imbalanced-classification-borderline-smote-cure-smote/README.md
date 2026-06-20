# 007 - Imbalanced Classification: Borderline-SMOTE vs CURE-SMOTE

## 📌 Project Overview

This project investigates the challenge of **imbalanced classification** in machine learning by applying and comparing two advanced oversampling techniques:

- Borderline-SMOTE
- CURE-SMOTE

The objective is to improve minority class detection and evaluate the impact of each technique on classification performance.

The project includes data preprocessing, oversampling, model training, evaluation, and statistical comparison of results.

---

## 🎯 Objectives

- Understand the impact of class imbalance on machine learning models.
- Apply Borderline-SMOTE to generate synthetic samples near decision boundaries.
- Apply CURE-SMOTE to generate synthetic samples based on cluster representatives.
- Compare model performance before and after oversampling.
- Evaluate classification metrics and analyze improvements.

---

## 🛠 Technologies Used

- Python
- Jupyter Notebook
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- Imbalanced-Learn (imblearn)

---

## 📂 Project Structure

```text
007-imbalanced-classification-borderline-smote-cure-smote/
│
├── data/
│   └── dataset files
│
├── images/
│   └── plots and visualizations
│
├── imbalanced-classification-borderline-smote-cure-smote.ipynb
├── imbalanced-classification-borderline-smote-cure-smote.html
│
└── README.md
```

---

## 🔍 Workflow

1. Load and explore the dataset.
2. Analyze class distribution.
3. Preprocess the data.
4. Train baseline classification models.
5. Apply Borderline-SMOTE.
6. Apply CURE-SMOTE.
7. Retrain and evaluate models.
8. Compare performance metrics.
9. Visualize and discuss results.

---

## 📊 Evaluation Metrics

The models are evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- ROC-AUC Score
- Confusion Matrix

Special attention is given to **Recall** and **F1-Score**, which are particularly important for imbalanced datasets.

---

## 📈 Results

The comparison demonstrates how oversampling techniques can improve minority class recognition and reduce the bias toward majority classes.

Performance differences between Borderline-SMOTE and CURE-SMOTE are analyzed using statistical and visual evaluation methods.

---

## 🚀 How to Run

1. Clone the repository:

```bash
git clone https://github.com/yourusername/007-imbalanced-classification-borderline-smote-cure-smote.git
```

2. Navigate to the project folder:

```bash
cd 007-imbalanced-classification-borderline-smote-cure-smote
```

3. Install the required libraries:

```bash
pip install -r requirements.txt
```

4. Open the notebook:

```bash
jupyter notebook
```

5. Run all notebook cells.

---

## 📚 Learning Outcomes

This project demonstrates:

- Handling imbalanced datasets
- Synthetic oversampling techniques
- Classification model evaluation
- Data visualization
- Comparative machine learning analysis

---

## 👨‍💻 Author

<div align="center">

### **Wessam Abo Zayed**

**Automation Engineering | PLC Programming | Data Analyst**

</div>

Computer Scientist with a focus on Automation Engineering, PLC Programming, Data Analytics, and Machine Learning. Passionate about developing intelligent solutions that combine industrial automation and data-driven technologies.

---

## Contact

| Contact | Link |
|----------|----------|
| **E-Mail** | [abozayed.wessam@gmail.com](mailto:abozayed.wessam@gmail.com) |
| **LinkedIn** | [linkedin.com/in/wessam-abozayed](https://www.linkedin.com/in/wessam-abozayed/) |
| **GitHub** | [github.com/wessam-abo-zayed](https://github.com/wessam-abo-zayed) |
| **Tableau Public** | [public.tableau.com/app/profile/wessam3726](https://public.tableau.com/app/profile/wessam3726) |

---

## License

This project is published for educational and portfolio purposes.
---
