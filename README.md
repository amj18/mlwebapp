# Naive bayes classifier for Youtube comments

Update July 2019: New link to app: https://am189.pythonanywhere.com/

~~**Link to live web app on AWS Elastic beanstalk server:**~~

~~http://mlspamapp.eu-west-2.elasticbeanstalk.com~~

This is a simple naive bayes classifier trained on structured data to detect spam in YouTube comments. The front-end is designed in HTML and CSS, while the back-end is written in the Python Flask web framework with Jinja2 templating.

Model accuracy: 91.95%

## Screenshot of GUI:

![ML web app GUI](https://raw.githubusercontent.com/amj18/mlwebapp/master/screenshots/mlwebapp_1.PNG)

**Requirements:**
Python 3.7

## Instructions:

**Step 1:**

Clone this project and set up a virtual environment
https://docs.python.org/3/tutorial/venv.html

**Step 2:**

Install all relevant packages:

pip install flask

pip install flask_sqlalchemy

pip install pandas

pip install numpy

pip install scikit-learn

**Step 3:**

To run, open command line in folder and type:

python webapp.py

Go to localhost:5000 on your web browser to view and interact with app.

## Things to do
* ~~Deploy flask app to cloud server~~
* Add database functionality to store user input and retrain model - *in progress*
