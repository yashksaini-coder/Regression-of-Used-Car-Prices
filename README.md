<div align="center">
    <img src="https://socialify.git.ci/yashksaini-coder/Regression-of-Used-Car-Prices/image?forks=1&issues=1&language=1&name=1&pulls=1&stargazers=1&theme=Auto" alt="Kaggle Playgorund S4 E9" width="640" height="320" />
</div>
<br><br>

<div align="center">
    <img alt="GitHub Repo Name" src="https://img.shields.io/badge/Regression_of_Used_Car_Prices-e36414">
    <img alt="GitHub Author" src="https://img.shields.io/badge/Author-Yash%20K.%20Saini-a8dadc">
    <img alt="GitHub commit-activity" src="https://img.shields.io/github/commit-activity/t/yashksaini-coder/Regression-of-Used-Car-Prices">
    <img alt="GitHub contributors" src="https://img.shields.io/github/contributors/yashksaini-coder/Regression-of-Used-Car-Prices">
    <img alt="GitHub Created At" src="https://img.shields.io/github/created-at/yashksaini-coder/Regression-of-Used-Car-Prices">
    <img alt="GitHub Last Commit" src="https://img.shields.io/github/last-commit/yashksaini-coder/Regression-of-Used-Car-Prices">
    <img alt="GitHub Repo Size" src="https://img.shields.io/github/repo-size/yashksaini-coder/Regression-of-Used-Car-Prices">
    <img alt="GitHub License" src="https://img.shields.io/github/license/yashksaini-coder/Regression-of-Used-Car-Prices">
    <img alt="GitHub Open Issues" src="https://img.shields.io/github/issues/yashksaini-coder/Regression-of-Used-Car-Prices">
    <img alt="GitHub Closed Issues" src="https://img.shields.io/github/issues-closed/yashksaini-coder/Regression-of-Used-Car-Prices">
    <img alt="GitHub Open PR" src="https://img.shields.io/github/issues-pr/yashksaini-coder/Regression-of-Used-Car-Prices">
    <img alt="GitHub Closed PR" src="https://img.shields.io/github/issues-pr-closed/yashksaini-coder/Regression-of-Used-Car-Prices">
    <img alt="GitHub Forks" src="https://img.shields.io/github/forks/yashksaini-coder/Regression-of-Used-Car-Prices">
    <img alt="GitHub Stars" src="https://img.shields.io/github/stars/yashksaini-coder/Regression-of-Used-Car-Prices">
    <img alt="GitHub Watchers" src="https://img.shields.io/github/watchers/yashksaini-coder/Regression-of-Used-Car-Prices">
    <img alt="GitHub language count" src="https://img.shields.io/github/languages/count/yashksaini-coder/Regression-of-Used-Car-Prices">
</div>
<br>

<div align='center' style=" display: grid;">

  [![Gmail](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:ys3853428@gmail.com)
  [![Github](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/yashksaini-coder)
  [![Medium](https://img.shields.io/badge/Medium-12100E?style=for-the-badge&logo=medium&logoColor=white)](https://medium.com/@yashksaini)
  [![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/yashksaini/)
  [![Bento](https://img.shields.io/badge/Bento-768CFF.svg?style=for-the-badge&logo=Bento&logoColor=white)](https://bento.me/yashksaini)
[![Instagram](https://img.shields.io/badge/Instagram-%23FF006E.svg?style=for-the-badge&logo=Instagram&logoColor=white)](https://www.instagram.com/yashksaini.codes/)
  [![X](https://img.shields.io/badge/X-%23000000.svg?style=for-the-badge&logo=X&logoColor=white)](https://twitter.com/EasycodesDev) 
</div>

---

## 🛠️ Regression of Used Car Prices - Kaggle Playground Series (Season 4, Episode 9) 🔮

### **Objective** 🎯

The objective of this competition is to predict the price of used cars based on various attributes. The dataset provided for this competition includes various features related to used cars, such as the car's model, year of manufacture, mileage, fuel type, transmission type, and engine power. The target variable for this competition is the price of the used car.

## ⚙️ Built With

- [Python](https://www.python.org/)
- [Pandas](https://pandas.pydata.org/)
- [NumPy](https://numpy.org/)
- [Matplotlib](https://matplotlib.org/)
- [Seaborn](https://seaborn.pydata.org/)
- [Scikit-learn](https://scikit-learn.org/stable/)
- [XGBoost](https://xgboost.readthedocs.io/en/latest/)
- [LightGBM](https://lightgbm.readthedocs.io/en/latest/)

## Dataset 📦

The dataset for this competition (both train and test) was generated from a deep learning model trained on the Used Car Price Prediction Dataset. Feature distributions are close to, but not exactly the same, as the original. Feel free to use the original dataset as part of this competition, both to explore differences as well as to see whether incorporating the original in training improves model performance.

**Explore the [dataset](https://www.kaggle.com/competitions/playground-series-s4e9/data), develop your machine learning models, and submit your predictions through the Kaggle [competition](https://www.kaggle.com/competitions/playground-series-s4e9/overview) platform before the deadline.**

## Files 📄

- **train.csv**: Training dataset containing the different variables where; price is the continuous target.
- **test.csv**: Test dataset for which your objective is to predict the value of price for each row
- **sample_submission.csv**: A sample submission file demonstrating the correct format for predictions.

## **Evaluation** 📊

### Root Mean Squared Error (RMSE)

In this project, we evaluate the performance of our predictive model using the **Root Mean Squared Error (RMSE)** metric. RMSE is a widely used measure of the differences between predicted values and the actual observed values. It provides insight into the accuracy of our model by quantifying how closely our predictions match the original data.

### Formula

The RMSE is calculated using the following formula:

The root mean squared error (RMSE) is calculated using the following formula:

\[ \text{RMSE} = \sqrt{\frac{1}{N} \sum_{i=1}^{N} \left( y_i - \hat{y}_i \right)^2} \]

Where:
- ***N*** is the total number of instances.
- ***yi*** represents the actual value for the ***i*** instance.
- ***yˆi*** represents the predicted value for the ***i*** instance.

### Interpretation

- **Low RMSE**: A lower RMSE value indicates that the predicted values are close to the actual values, signifying better model performance.
- **High RMSE**: A higher RMSE value suggests a larger discrepancy between predicted and actual values, indicating that the model may not be accurately capturing the underlying data patterns.

### Importance of RMSE:- 

RMSE is particularly important because:
- It penalizes large errors more than smaller ones, making it sensitive to outliers.
- It is easy to interpret, as it provides the error in the same units as the original data.
- It is a useful measure when comparing the accuracy of different models or algorithms.
--- 

## Installation & Usage 💻

Follow these simple steps to get started:

1. **Clone the Repository**: 
    ```bash
    git clone https://github.com/yashksaini-coder/Regression-of-Used-Car-Prices
    ```

2. **Navigate to the Repository Directory**:
    ```bash
    cd Regression-of-Used-Car-Prices
    ```

3. **Install Dependencies**:
    ```bash
    pip install -r requirements.txt
    ```
---

## 🌟Contributing Guide

You are welcome to contribute to this project! To ensure a smooth workflow, please follow these steps:

### 1. Fork the Project

- Go to the project repository on GitHub.
- Click on the [Fork]("https://github.com/yashksaini-coder/Regression-of-Used-Car-Prices/fork") button in the upper right corner of the page.
- This will create a copy of the repository in your GitHub account.

### 2. Create Your Feature Branch

- Clone the forked repository to your local machine:
  ```bash
  git clone https://github.com/yashksaini-coder/Regression-of-Used-Car-Prices.git
  ```
- Navigate to the project directory:
  ```bash
  cd Regression-of-Used-Car-Prices
  ```
- Create a new branch for your feature:
  ```bash
  git checkout -b feature/AmazingFeature
  ```

### 3. Commit Your Changes

- Make your changes to the code.
- Stage your changes:
  ```bash
  git add .
  ```
- Commit your changes with a descriptive message:
  ```bash
  git commit -m 'Add some AmazingFeature'
  ```

### 4. Push to the Branch

- Push your changes to your forked repository:
  ```bash
  git push origin feature/AmazingFeature
  ```

### 5. Open a Pull Request

- Go to the original repository on GitHub.
- Click on the "Compare & pull request" button.
- Ensure the base repository is the original repository and the base branch is the branch you want to merge into (e.g., `main`).
- Provide a descriptive title and detailed description of your changes.
- Click on the "Create pull request" button.

---

Thank you for your contributions! Your efforts help make this project better for everyone. If you have any questions or need assistance, feel free to open an issue or contact the maintainers.

---
## 📝 Conclusion

---

### License
Distributed under the MIT License. See [LICENSE](LICENSE) for more information.

---
# TODO 📝 

- [X] Use LightGBM model
- [X] Use XGBoost model
- [X] Add the project report
- [X] Add the PDF of the code
- [X] Add the project conclusion