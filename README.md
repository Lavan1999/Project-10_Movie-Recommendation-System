# Singapore Housing Resale Value Estimator

This project aims to predict the resale value of HDB flats in Singapore using various input features such as town, block, flat type, flat model, storey range, street name, floor area, and more. The prediction model is built using regression techniques and is deployed as a web application using Streamlit.

## Project Workflow
- 1. Data Collection and Preprocessing
Data Source: The dataset used for this project is obtained from data.gov.sg.
Preprocessing:
Load the dataset.
Encode categorical features using label encoders.
Save the encoders for later use during prediction.
- 2. Model Training
Model Selection: Various regression models are evaluated to select the best-performing one.
Training: The selected model is trained on the preprocessed data.
Model Saving: The trained model is saved using joblib for later use in the web application.
- 3. Web Application Development
Libraries Used: Streamlit, NumPy, Pandas, Pickle, Joblib.
User Input: The web app takes user inputs for various features required for prediction.
Prediction: The app encodes the user inputs using the saved encoders and makes predictions using the trained model.
Output: The predicted resale price is displayed to the user.
- 4. Deployment
Deployment Platform: The application can be deployed on platforms like Heroku or Streamlit Sharing.
Docker: Optionally, a Dockerfile can be created for containerized deployment.
