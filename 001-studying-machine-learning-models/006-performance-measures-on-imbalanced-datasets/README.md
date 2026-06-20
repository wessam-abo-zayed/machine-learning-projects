# Performance Measures on Imbalanced Datasets

This project investigates the impact of different data balancing techniques on the performance of a Random Forest classifier when dealing with imbalanced datasets.

The study compares several approaches for handling class imbalance and evaluates their effectiveness using common classification performance metrics.

---

## Project Objectives

- Analyze the challenges of imbalanced datasets.
- Train a baseline Random Forest model on the original dataset.
- Apply different sampling techniques to improve minority class detection.
- Compare model performance using multiple evaluation metrics.
- Identify the most effective approach for handling class imbalance.

---

## Methods Evaluated

### 1. Baseline Model
Random Forest trained on the original imbalanced dataset without any resampling.

### 2. SMOTE Oversampling
Synthetic Minority Over-sampling Technique (SMOTE) generates synthetic samples for the minority class.

### 3. DBSMOTE Oversampling
Density-Based SMOTE creates synthetic minority samples based on dense regions of the feature space.

### 4. Random Undersampling
Reduces the number of majority class samples to balance the dataset.

### 5. Cost-Sensitive Random Forest
Uses class weights to penalize misclassification of minority class samples without modifying the dataset.

---

## Performance Metrics

The following metrics are used to evaluate and compare the models:

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix
- ROC Curve
- ROC-AUC Score

---

## Project Structure

```
project/
│
├── data/
│   └── dataset files
│
├── performance-measures-on-imbalanced-datasets.ipynb
│
├── performance-measures-on-imbalanced-datasets.html
│
└── README.md
```

---

## Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Scikit-Learn
- Imbalanced-Learn (imblearn)
- Matplotlib
- Seaborn

---

## Results

The results provide a comparative analysis of different balancing strategies and their impact on classification performance.

Special attention is given to minority class detection, as traditional accuracy alone may be misleading for highly imbalanced datasets.

---

## Key Learning Outcomes

- Understanding the effects of class imbalance on machine learning models.
- Applying oversampling and undersampling techniques.
- Implementing cost-sensitive learning approaches.
- Evaluating models using appropriate metrics for imbalanced classification problems.

---

## Author

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
