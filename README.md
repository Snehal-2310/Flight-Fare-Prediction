# Flight-Fare-Prediction

Link: https://flight-travelprice-prediction.herokuapp.com/

The project created is a Flask web app which predicts fare of Flight ticket based on the details entered by the users. 

Training and model validation are done in the Jupyter Notebook and deployed on Heroku. 

## Technologies used

![](https://forthebadge.com/images/badges/made-with-python.svg)[<img target="_blank" src="https://flask.palletsprojects.com/en/1.1.x/_images/flask-logo.png" width=170>](https://flask.palletsprojects.com/en/1.1.x/) [<img target="_blank" src="https://number1.co.za/wp-content/uploads/2017/10/gunicorn_logo-300x85.png" width=280>](https://gunicorn.org) [<img target="_blank" src="https://scikit-learn.org/stable/_static/scikit-learn-logo-small.png" width=200>](https://scikit-learn.org/stable/) 

## Methodology
<img src="https://github.com/Snehal-2310/Flight-Fare-Prediction/blob/main/Images/flowchart.jpg" align="centre" alt="Methodolgy" width=400 height=800/> 

## After model fitting results
I used random forest for regression and the score obtained is 79%. The graphs below also proves the gaussian distribution formed and the scatter plot itself depicts that the results are pretty much satisfying.

![image](https://user-images.githubusercontent.com/62506140/137600258-291e62d2-dbfb-494b-8465-381c49eddd2a.png) ![image](https://user-images.githubusercontent.com/62506140/137600281-4e163afb-5b3a-4890-88ab-016b138ab43d.png)

## After hyperparameter tuning
I used randomized search CV using 5 fold cross validation for hyperparameter tuning. Below graphs show the final results.

<img src="https://user-images.githubusercontent.com/62506140/137600295-eaf2b7ea-7475-42db-9112-613c7fe9f615.png" width=450 height=250/> <img src="https://user-images.githubusercontent.com/62506140/137600303-1d3491fe-b353-44d0-abfe-da6982f716f3.png" width=450 height=250/>

## Web Application
Frontend is created using HTML and CSS and backend developed using Flask in Python and the app is deployed using Heruku.

An input form was created using a simple HTML template and a CSS style sheet. CSS describes an efficient method to keep your application's layout under control. Background colour, font size and colour, margins, positon of elements and other variables are all included in style sheets.

The Flask framework is used to create the back-end of a web application. It employs Jinja2, a templating language for creating HTML, XML, and other markup forms that are returned to the user via an HTTP request.

### Input
<img src="https://github.com/Snehal-2310/Flight-Fare-Prediction/blob/main/Images/Capture.JPG" alt="Input"/> 

### Output




