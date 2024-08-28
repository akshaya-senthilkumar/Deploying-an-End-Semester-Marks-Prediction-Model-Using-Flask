
# Deploying an End-Semester Marks Prediction Model Using Flask

This project demonstrates how to deploy a Linear Regression model to predict End-Semester Exam (ESE) marks using Flask. The model is trained to predict ESE marks based on mid-semester exam (MSE) marks and attendance percentage, and the deployment provides a web interface for easy interaction.
## Dataset


The dataset used for training the model is available on [Kaggle](https://www.kaggle.com/datasets/akiwelekar/predictingese).
## Model Development

- **Data Collection:** Gathering historical data on MSE marks, attendance, and ESE marks.

- **Data Preparation:** Preprocessing the data by splitting it into features (MSE marks and attendance) and the target variable (ESE marks). The data is then divided into training and testing sets.

- **Model Training:** Training the Linear Regression model using the training dataset to learn the relationship between the features and the target variable.

- **Making Predictions:** Using the trained model to predict ESE marks on the testing dataset to assess its performance.

- **Saving Results:** Storing the model, predictions, and evaluation metrics in a designated folder for further analysis and reference.
## Deployment

- **Setting Up Flask:** Creating a Flask application to serve as the web interface for the model.

- **Integrating the Model:** Loading the trained Linear Regression model into the Flask application.

- **Building the Web Interface:** Developing web routes to enable users to input data and receive predictions.

- **Running the Application:** Launching the Flask application to make the model accessible via a web browser, facilitating real-time predictions.
## Model Deployment Output

![Screenshot 2024-08-28 222926](https://github.com/user-attachments/assets/fb2806d7-abdd-4597-a37b-4f29065c4749)
