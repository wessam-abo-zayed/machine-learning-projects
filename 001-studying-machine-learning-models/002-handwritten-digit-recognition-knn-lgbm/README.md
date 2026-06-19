# Handwritten Digit Recognition using kNN and LightGBM (LGBM)

## Overview

This project presents a comparative study of two Machine Learning algorithms for handwritten digit classification:

* **k-Nearest Neighbors (kNN)**
* **Light Gradient Boosting Machine (LightGBM - LGBM)**

The project includes data exploration, visualization, model training, performance evaluation, and a detailed comparison of both models using the Digits dataset from Scikit-learn.

---

## Objectives

* Explore and understand the handwritten digits dataset.
* Visualize digit samples and dataset characteristics.
* Train and evaluate kNN and LGBM models.
* Compare classification performance and computational efficiency.
* Analyze strengths and limitations of both algorithms.

---

## Project Structure

```text
002-handwritten-digit-recognition-knn-lgbm/
│
├── images/
│   └── Figures, plots
│
├── handwritten-digit-recognition-knn-lgbm.ipynb
│   └── Jupyter Notebook containing the complete analysis
│
├── handwritten-digit-recognition-knn-lgbm.html
│   └── Exported HTML report of the notebook
│
└── README.md
```

---

## Dataset

The project uses the Digits dataset available in Scikit-learn.

### Dataset Characteristics

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
* Seaborn
* Scikit-learn
* LightGBM

---

## Machine Learning Models

### 1. k-Nearest Neighbors (kNN)

kNN is a supervised learning algorithm that classifies data points based on the classes of their nearest neighbors.

#### Advantages

* Simple and intuitive
* No training phase required
* Effective for small and medium-sized datasets

#### Limitations

* Computationally expensive during prediction
* Sensitive to feature scaling
* Performance depends on the value of k

---

### 2. Light Gradient Boosting Machine (LGBM)

LightGBM is a gradient boosting framework that uses decision trees and efficient learning techniques to achieve high performance.

#### Advantages

* High accuracy
* Fast training
* Efficient memory usage
* Handles large datasets effectively

#### Limitations

* More complex than kNN
* Requires parameter tuning
* Can overfit if not properly configured

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

The project compares both models based on:

* Classification accuracy
* Prediction performance
* Training and inference efficiency
* Error analysis
* Strengths and weaknesses of each approach

The results demonstrate the trade-off between the simplicity of kNN and the advanced boosting capabilities of LightGBM.

---

## How to Run

### Clone the repository

```bash
git clone https://github.com/your-username/002-handwritten-digit-recognition-knn-lgbm.git
```

### Navigate to the project folder

```bash
cd 002-handwritten-digit-recognition-knn-lgbm
```

### Install dependencies

```bash
pip install numpy pandas matplotlib seaborn scikit-learn lightgbm
```

### Launch Jupyter Notebook

```bash
jupyter notebook
```

Open:

```text
handwritten-digit-recognition-knn-lgbm.ipynb
```

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
