ML-Model-Flask-Deployment
This is a demo project to elaborate how Machine Learn Models are deployed on production using Flask API
.

Project Structure

This project has four major parts :


1. model.py - This contains code fot our Machine Learning model to predict selling price based on trainig data in 'cardata.csv' file.

2. app.py - This contains Flask APIs that receives cardata.csv details through GUI or API calls, computes the precited value based on our model and returns it.

3. car_prediction.ipynb - This include the code written in python ( jupyter notebook) to predict future price of cars.
4. templates - This folder contains the HTML template to allow user to enter car detail and displays the predicted selling price.

### 

Running the project



1. Create your own project directory. Open command prompt. 
Ensure that you are in the project home directory. Create the machine learning model by running below command:

>set FLASK_APP=app.py
>flask run


2. Run app.py using below command to start Flask API
. 
By default, flask will run on port 5000.


3. Navigate to URL http://localhost:5000. 

You should be able to view the homepage.