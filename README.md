# Credit Repayment Prediction

This project aims to predict whether a credit card user will repay their credit next month using a machine learning model. The project includes data cleaning, model training, and a graphical user interface (GUI) for user input.

## Project Structure

- `credit_repayment_prediction.ipynb`: The Jupyter Notebook that contains all the necessary code for data processing, model training, and the GUI.
- `UCI_Credit_Card.csv`: The dataset file (not included, must be placed in the same directory as the notebook).
- `README.md`: Project documentation.
- `requirements.txt`: Python packages required to run the project.
- `.gitignore`: Specifies files and directories to be ignored by Git.
- `LICENSE`: Project license.

## Getting Started

### Prerequisites

Ensure you have Python 3.x installed.

### Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/yourusername/credit-repayment-prediction.git
    cd credit-repayment-prediction
    ```

2. Install the required packages:

    ```bash
    pip install -r requirements.txt
    ```

### Running the Project

1. Ensure the `UCI_Credit_Card.csv` dataset is in the project directory.

2. Open the `credit_repayment_prediction.ipynb` notebook in Jupyter.

3. Follow the steps in the notebook to run the data processing, model training, and GUI setup.

## Project Description

This project uses an XGBoost model to predict whether a credit card user will default on their payment next month. The prediction is made based on various features such as credit limit, age, gender, education level, marital status, and repayment history.

The GUI allows users to input these features and receive an instant prediction on whether they will repay their credit or not.

## Conclusion

This project provides a complete workflow for predicting credit repayment using machine learning, with an easy-to-use graphical interface for predictions.

---

<p style="text-align: left; font-size: 18px; font-style: italic;">Suheyl Ozdemir</p>
