# flight-price-prediction
![alt text](https://github.com/GK884/flight-price-prediction/blob/main/static/photos/Book-Flights-Indigo-759.jpg)
* Created a tool that estimates Flight Prices to help users look for best prices when booking flight tickets.
* Engineered features from the Departure Time, Date of Journey, to quantify the data and make it more understandable.
* Optimized multiple Regression models using RandomForest to reach the best model.
* Built a client facing API using flask

Dataset: https://www.kaggle.com/nikhilmittal/flight-fare-prediction-mh

![alt text](https://github.com/GK884/flight-price-prediction/blob/main/git%20picture/f_name%20vs%20price.PNG)

![alt text](https://github.com/GK884/flight-price-prediction/blob/main/git%20picture/f_nme%20count.PNG)



# RandomForest :-
RMSE : 1985.8131350560936
R2score :  0.8171114225806749

# Demo:

![alt text](https://github.com/GK884/flight-price-prediction/blob/main/git%20picture/arriv.PNG)

![alt text](https://github.com/GK884/flight-price-prediction/blob/main/git%20picture/deptime.PNG)

![alt text](https://github.com/GK884/flight-price-prediction/blob/main/git%20picture/stop.PNG)

![alt text](https://github.com/GK884/flight-price-prediction/blob/main/git%20picture/pred.PNG)

## How to run on your local:<br>
step1: fork and clone this repository
```sh
git clone 'https://github.com/GK884/Cotton-Disease-Prediction.git'
```
step2: Make a new Environment
```sh
conda create -n envname
```
step3: Install requirements.txt 
```sh
pip install -r requirements.txt
```
step4: run app.py

# steps for Deployment on Heroku:

  1. download heroku cli first from this link https://devcenter.heroku.com/articles/heroku-cli
  2. check heroku is installed in our system do open 'Anaconda prompt' or 'Terminal' and just type 'heroku' in there for confirmation.
  3. type "heroku login"
  4. login on heroku or do sign up
  5. go to your heroku dashboard and create a new app and give name
  6. in your conda terminal create a new environment "conda create -n python=3.6" put your environment name in place of
  7. go to the file location
  8. 'git init'
  9. 'heroku git:remote -a check on your dashboard
  10. 'git add .'
  11.git commit -am "first-commit"
  12. 'git push heroku master'
  
you will get the link on the terminal of your deployed app.

Always welcomes you all to make changes.


