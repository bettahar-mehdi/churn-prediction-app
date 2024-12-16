Churn Prediction Web Application

This is a web application built using Streamlit that predicts whether a customer will churn based on input data. The prediction is powered by a pre-trained machine learning model.

Features

User-friendly interface for data input.

Predicts customer churn with a trained machine learning model.

Displays the probability of churn alongside the prediction.

Technology Stack

Streamlit: For building the web application.

Scikit-learn: For training and saving the machine learning model.

Pandas: For data processing.

Joblib: For saving and loading the model and preprocessing pipeline.

Project Structure

project-folder/
|-- app.py                # Main Streamlit application
|-- model.pkl             # Pre-trained ML model
|-- pipeline.pkl          # Preprocessing pipeline (optional)
|-- requirements.txt      # Python dependencies
|-- README.md             # Project documentation

How to Run the Application

1. Clone the Repository

Clone this repository to your local machine:

git clone https://github.com/bettahar-mehdi/churn-prediction-app.git
cd churn-prediction-app

2. Install Dependencies

Install the required Python packages:

pip install -r requirements.txt

3. Run the Application

Start the Streamlit app:

streamlit run app.py

This will open the application in your web browser at http://localhost:8501.

4. Input Customer Data

Use the sidebar in the app to input customer details and click Predict to see the churn prediction and probability.

Deployment

You can deploy the app using:

Streamlit Community Cloud

Heroku

AWS/GCP/Azure

Refer to the respective platform’s documentation for deployment steps.

Dependencies

All dependencies are listed in the requirements.txt file. Key dependencies include:

streamlit

pandas

scikit-learn

joblib

Example Input and Output

Input:

Gender: Male

Senior Citizen: 1

Partner: Yes

Tenure: 12 months

Monthly Charges: $50.75

Output:

Prediction: Churn

Probability of Churning: 0.78

Contributing

Contributions are welcome! If you find any bugs or have feature requests, please open an issue or submit a pull request.

License

This project is licensed under the MIT License.

Author

Bettahar Mahdi
Machine Learning Developer

