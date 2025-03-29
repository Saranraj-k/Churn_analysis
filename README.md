create env --> conda create -p venv python==3.11 -y
Activate vencv --> conda activate venv/
Install requirements -- pip install -r requirements.txt
Build the model along with creating the logs, also create the pickle files for feature engineering
Save the model and log the parameters.
Using the Saved model create a prediction notebook for testing
Then create app file to develop the UI using streamlit and runusing 'streamlit run app.py'
Deploy the app in streamlit using github repo.
