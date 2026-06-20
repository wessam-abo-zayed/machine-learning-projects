
# Handwritten Digit Recognition using Logistic Regression and XGBoost

## Overview

This project demonstrates handwritten digit classification using the famous MNIST dataset. The notebook explores the complete machine learning workflow, including data loading, preprocessing, visualization, model training, and performance evaluation.

Two supervised machine learning algorithms are implemented and compared:

- Logistic Regression
- XGBoost Classifier

The objective is to analyze their effectiveness in recognizing handwritten digits and compare their prediction performance.

---

## Dataset

### MNIST Dataset

The MNIST dataset contains:

- 70,000 grayscale images
- Image size: 28 × 28 pixels
- 10 classes (digits 0–9)

Dataset split:

- Training samples: 60,000
- Test samples: 10,000

Each image is represented as a flattened vector of pixel values.

---

## Project Structure

```text
handwritten-digit-recognition-logistic-regression-xgboost/
│
├── data/
│   └── MNIST dataset files
│
├── images/
│   └── Project screenshots and visualizations
│
├── handwritten-digit-recognition-logistic-regression-xgboost.ipynb
├── handwritten-digit-recognition-logistic-regression-xgboost.html
└── README.md
```

---

## Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-Learn
- XGBoost
- Jupyter Notebook

---

## Machine Learning Workflow

### 1. Data Loading

- Load the MNIST dataset
- Inspect data dimensions
- Verify labels and image structure

### 2. Data Exploration

- Display sample handwritten digits
- Analyze class distribution
- Understand dataset characteristics

### 3. Data Preprocessing

- Feature scaling and normalization
- Train-test splitting
- Preparing data for model training

### 4. Model Training

#### Logistic Regression

A linear classification algorithm commonly used as a baseline model for image classification tasks.

#### XGBoost

An advanced gradient boosting algorithm known for high predictive performance and efficient learning.

### 5. Model Evaluation

Models are evaluated using:

- Accuracy Score
- Confusion Matrix
- Classification Report
- Prediction Visualization

---

## Results

The notebook compares the predictive performance of:

| Model | Description |
|---------|-------------|
| Logistic Regression | Fast and interpretable baseline classifier |
| XGBoost | Powerful ensemble learning algorithm with high accuracy |

The comparison highlights the strengths and limitations of both approaches when applied to handwritten digit recognition.

---

## Learning Outcomes

Through this project, the following concepts are demonstrated:

- Image classification fundamentals
- Data preprocessing techniques
- Supervised machine learning
- Logistic Regression implementation
- XGBoost implementation
- Model evaluation and comparison
- Working with the MNIST dataset

---

## How to Run

1. Clone the repository:

```bash
git clone https://github.com/your-username/handwritten-digit-recognition-logistic-regression-xgboost.git
```

2. Navigate to the project folder:

```bash
cd handwritten-digit-recognition-logistic-regression-xgboost
```

3. Install required libraries:

```bash
pip install numpy pandas matplotlib seaborn scikit-learn xgboost
```

4. Launch Jupyter Notebook:

```bash
jupyter notebook
```

5. Open:

```text
handwritten-digit-recognition-logistic-regression-xgboost.ipynb
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
