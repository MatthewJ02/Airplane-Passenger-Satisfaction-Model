# Airplane Passenger Satisfaction Model

## Description
This project is a multilayer perceptron model which predicts an airplane passenger as either satisfied or dissatisfied depending on data pertaining to them and their flight such as flight distance, age, and arrival delay. The project was created using AWS SageMaker and developed in PyTorch with a publicly available dataset from Kaggle. The Jupyter Notebook in this repository documents the full process of data preprocessing, model training, and model deployment.

## Languages and Software Used
- Python
- Pandas
- Scikit-Learn
- PyTorch
- Jupyter Notebooks
- AWS SageMaker
- AWS S3
- Kaggle

## Setup
1. Clone: 'git clone https://github.com/MatthewJ02/Airplane-Passenger-Satisfaction-Model.git'.
2. Install dependencies: 'pip install -r requirements.txt'.
3. Configure credentials in AWS.
4. Instantiate a SageMaker Notebook in AWS.
5. Set up Kaggle API credentials with a 'kaggle.json' file in the notebook environment.
6. Upload the project files and data to the instance.
7. Run the cells in sequential order; this will preprocess data, train the model, and deploy the model.

## Performance
The model classified the testing data set with an overall accuracy of 91.98%. The following report was returned from the notebook's cell for testing accuracy:

Overall Model Accuracy: 91.98%

Classification Report:

| Metric         | Precision | Recall | F1-Score | Support |
| :------------- | :-------: | :----: | :------: | :-----: |
| **Dissatisfied** |   0.92    |  0.94  |   0.93   |  14573  |
| **Satisfied** |   0.93    |  0.89  |   0.91   |  11403  |
| **Accuracy** |           |        |   0.92   |  25976  |
| **Macro Avg** |   0.92    |  0.92  |   0.92   |  25976  |
| **Weighted Avg** |   0.92    |  0.92  |   0.92   |  25976  |

I have included the confusion matrix as a PNG in the repository.
