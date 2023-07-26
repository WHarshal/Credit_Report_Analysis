# Credit_Report_Analysis
This repository contains the code and data for a credit scoring project that aims to predict credit risk using machine learning models. The project compares the performance of three different classifiers: Decision Tree, Logistic Regression, and Random Forest. The models are evaluated using various metrics, including accuracy, precision, recall, and F1-score.

### Project Structure
The repository is structured as follows:
- data/                  # Directory to store the dataset
- notebooks/             # Jupyter notebooks for data exploration, modeling, and evaluation
- README.md              # Project documentation

#### Dataset
The dataset used for this project contains historical data of borrowers. It includes various features such as income, age, credit history, loan amount, and other relevant attributes. The target variable is the credit risk category, divided into three classes: Good, Bad and Average.

#### Models
We will be employing the following machine learning models for credit scoring:
- Decision Tree: A tree-based model that splits the dataset into branches based on feature values to make predictions.
- Logistic Regression: A linear regression-based model used for binary classification tasks, extended for multiclass classification through one-vs-rest or multinomial approaches.
- Random Forest: An ensemble model that combines multiple decision trees to improve predictive accuracy and reduce overfitting.

#### Requirements
To run the code and replicate the results, you will need the following dependencies:

- Python 
- matplotlib
- scikit-learn 
- numpy 
- pandas

#### Model Evaluation
The models' performance is evaluated using standard metrics like accuracy, precision, recall, and F1-score. We aim to identify the model with the best predictive capabilities for credit risk assessment.

#### Instructions
To replicate the results or make further improvements:
- Clone this repository to your local machine.
- Install the required libraries by running pip install -r requirements.txt.
- Run the Jupyter notebooks in the notebooks/ directory in the specified order.

#### Conclusion
This credit scoring project aims to assist credit institutions in making more informed lending decisions and mitigating financial risks. By comparing the performance of different classifiers and leveraging hyperparameter tuning, the models aim to predict credit risk accurately.

#### Contributing
Contributions to this project are welcome! If you find any issues or have suggestions for improvements, feel free to open a GitHub issue or submit a pull request.
