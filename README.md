# Churn Modelling Using SVM

Welcome to the **Churn Modelling Using SVM** project! This repository demonstrates the application of Support Vector Machine (SVM) to predict customer churn based on historical data.

---

## Table of Contents
- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Dependencies](#dependencies)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [Contributing](#contributing)

---

## Project Overview
Customer churn is a significant challenge faced by businesses across various industries. Predicting customer churn can help organizations retain their customers and improve overall business performance. 

In this project, we utilize Support Vector Machine (SVM), a supervised machine learning algorithm, to classify customers into churn and non-churn categories. The project follows the end-to-end machine learning pipeline:

1. Data Preprocessing
2. Feature Engineering
3. Model Training and Evaluation
4. Visualization of Results

---

## Dataset
The dataset used in this project contains customer information such as:
- Credit Score
- Geography
- Gender
- Age
- Tenure
- Balance
- Number of Products
- Has Credit Card
- Is Active Member
- Estimated Salary
- Exited (Target variable)

### Source
The dataset can be found in the `data` directory of this repository. Alternatively, it is derived from publicly available churn datasets.

---

## Dependencies
This project uses the following Python libraries:
- `numpy`
- `pandas`
- `scikit-learn`
- `matplotlib`
- `seaborn`

---

## Installation
1. Clone this repository:
   ```bash
   git clone https://github.com/FaizAbiyyu/Churn-Modelling-Using-SVM.git
   cd Churn-Modelling-Using-SVM
   ```

2. Create a virtual environment (optional but recommended):
   ```bash
   python -m venv env
   source env/bin/activate  # On Windows: env\Scripts\activate
   ```

3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

---

## Usage
1. Run the Jupyter Notebook to execute the project pipeline:
   ```bash
   jupyter notebook churn_modelling_svm.ipynb
   ```

2. Follow the steps in the notebook for:
   - Data exploration and preprocessing
   - Model training and evaluation
   - Visualizing performance metrics

3. View the generated output and adjust parameters as needed.

---

## Results
The project evaluates the performance of the SVM model using metrics such as:
- Accuracy
- Precision
- Recall
- F1-Score

Confusion Matrix and ROC Curve visualizations are also provided to assess the model's performance.

---

## Contributing
Contributions are welcome! Please follow these steps:
1. Fork the repository.
2. Create a new branch (`feature-branch-name`).
3. Commit your changes (`git commit -m "Description of feature"`).
4. Push to the branch (`git push origin feature-branch-name`).
5. Open a Pull Request.

Happy coding! If you have any questions or suggestions, feel free to reach out. 😄
