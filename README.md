Core Libraries
pandas – Used for data loading and preprocessing

scikit-learn – Provides tools like train_test_split, LabelEncoder, StandardScaler, and resample

catboost – Implements gradient boosting for classification

joblib – Saves and loads the trained machine learning model

Deployment Libraries
streamlit – Builds the interactive web interface

pyngrok – Exposes the local Streamlit app to a public URL for remote access

Installation
Install all required libraries using pip:

bash
Copy
Edit
pip install pandas scikit-learn catboost joblib streamlit pyngrok
How to Run the Project
1. Train the Model
Open the notebook file EMPLOYEE salary PREDICT MODEL.ipynb

Run all cells to:

Clean and encode the dataset

Train the CatBoost classifier

Save the trained model as catboost_model.pkl

2. Launch the Web Interface
Open UI.ipynb or run the Streamlit app from the terminal using:

bash
Copy
Edit
streamlit run app.py
The application will:

Load the saved model

Display a web interface for input and prediction

Note: If running this in Google Colab, use pyngrok to create a public link for accessing the Streamlit app.
