# 🪨 Sonar Data Classification

This project implements a **Logistic Regression** model to classify sonar signals as either **Rocks** or **Mines** based on their frequency-based energy features.

## 📂 Dataset

The dataset used is the **Sonar Dataset**, consisting of **208 instances**. Each instance includes:

-   **60 numerical features**: Representing the energy of sonar signals at different frequencies.
-   **1 target label**:
    -   `'R'` for **Rock**
    -   `'M'` for **Mine**

📥 You can download the dataset from [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/connectionist+bench+(sonar,+mines+vs.+rocks)) or use the provided `sonar data.csv` file.

---

## 📁 Project Structure

├── sonar data.csv                # Sonar dataset file
├── sonar_classification.ipynb   # Jupyter notebook for model training and evaluation
└── README.md                    # Project documentation (you are here)


---

## 📦 Dependencies

Ensure the following Python libraries are installed:

-   `numpy`
-   `pandas`
-   `scikit-learn`

You can install them using pip:

```bash
pip install numpy pandas scikit-learn
🚀 How to Run
Open the Jupyter notebook sonar_classification.ipynb.

Run each cell to load the data, preprocess it, train the model, and evaluate the results.

✅ Model Output
The logistic regression model will output predictions indicating whether the sonar signal was reflected by a rock or a mine, along with evaluation metrics such as accuracy and a confusion matrix.

🧠 Goal
This project demonstrates the application of a simple logistic regression model to a real-world binary classification problem, focusing on signal-based pattern recognition.
