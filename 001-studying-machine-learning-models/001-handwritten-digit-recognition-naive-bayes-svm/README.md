# Handwritten Digit Recognition using Naive Bayes and SVM

## Overview

This project demonstrates the application of Machine Learning techniques for handwritten digit recognition using the popular Digits dataset. Two classification algorithms are implemented and compared:

* **Naive Bayes**
* **Support Vector Machine (SVM)**

The project includes data exploration, visualization, model training, performance evaluation, and statistical comparison of the results.

---

## Objectives

* Explore and understand the handwritten digits dataset.
* Visualize digit samples and dataset characteristics.
* Train and evaluate multiple Machine Learning models.
* Compare the performance of Naive Bayes and SVM classifiers.
* Analyze classification results using statistical metrics.

---

## Project Structure

```text
handwritten-digit-recognition-naive-bayes-svm/
│
├── data/
│   └── Dataset files
│
├── images/
│   └── Figures, plots
│
├── handwritten-digit-recognition-naive-bayes-svm.ipynb
│   └── Jupyter Notebook containing the complete analysis
│
├── handwritten-digit-recognition-naive-bayes-svm.html
│   └── Exported HTML report of the notebook
│
└── README.md
```

---

## Dataset

The project uses the Digits dataset available in Scikit-learn.

**Dataset Characteristics**

* 1,797 handwritten digit images
* Digits from 0 to 9
* Image size: 8 × 8 pixels
* 64 numerical features per image
* Multi-class classification problem

Dataset source:

```python
from sklearn.datasets import load_digits
```

---

## Technologies Used

* Python
* Jupyter Notebook
* NumPy
* Pandas
* Matplotlib
* Scikit-learn

---

## Machine Learning Models

### 1. Naive Bayes

Gaussian Naive Bayes is a probabilistic classifier based on Bayes' theorem with independence assumptions between features.

**Advantages**

* Fast training and prediction
* Simple implementation
* Effective on many classification tasks

---

### 2. Support Vector Machine (SVM)

Support Vector Machines classify data by finding the optimal decision boundary between classes.

**Advantages**

* High classification accuracy
* Effective in high-dimensional spaces
* Strong generalization performance

---

## Evaluation Metrics

The models are evaluated using:

* Accuracy Score
* Confusion Matrix
* Classification Report
* Precision
* Recall
* F1-Score

---

## Results

The project compares the performance of both models and analyzes:

* Prediction accuracy
* Classification errors
* Strengths and weaknesses of each algorithm
* Statistical performance differences

---

## How to Run

### Clone the repository

```bash
git clone https://github.com/your-username/handwritten-digit-recognition-naive-bayes-svm.git
```

### Navigate to the project folder

```bash
cd handwritten-digit-recognition-naive-bayes-svm
```

### Install dependencies

```bash
pip install numpy pandas matplotlib scikit-learn 
```

### Launch Jupyter Notebook

```bash
jupyter notebook
```

Open:

```text
handwritten-digit-recognition-naive-bayes-svm.ipynb
```

---

## Sample Workflow

1. Load the Digits dataset.
2. Explore and visualize the data.
3. Split the dataset into training and testing sets.
4. Train the Naive Bayes classifier.
5. Train the SVM classifier.
6. Evaluate both models.
7. Compare results and draw conclusions.



---
## Autor

<div align="center">

### **Wessam Abo Zayed**

**Automation Engineering | PLC Programming | Data Analyst**
</div>
- Computer Scientist with a focus on Automation Engineering, PLC Programming, and Data Analytics. I combine technical expertise with analytical problem-solving skills to develop practical and efficient solutions for industrial systems and data-driven applications.

## Kontakt

| Kontakt      | Link                                                                            |
| ------------ | ------------------------------------------------------------------------------- |
| **E-Mail**   | [abozayed.wessam@gmail.com](mailto:abozayed.wessam@gmail.com)                   |
| **LinkedIn** | [linkedin.com/in/wessam-abozayed](https://www.linkedin.com/in/wessam-abozayed/) |
| **GitHub**   | [github.com/wessam-abo-zayed](https://www.github.com/wessam-abo-zayed)                   |
| **Tableau Public** | [public.tableau.com/app/profile/wessam3726](https://public.tableau.com/app/profile/wessam3726) |


---

## License

This project is published for educational and portfolio purposes.

