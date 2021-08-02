# Pet_Pals
Heroku is a cloud platform which can be used as a database to create app in virtual containers. Here, Heroku Postgres is applied to create a pet database. The pet's name, pet's latitude, and pet's longitude can be input to create pet map.


1.Create Pet_Pals repo

Add all deployment required files into Pet_Pals repo, including app file, models file, templates file, static file, and init file, db file.


2.Configuation



Firts, activate pet_pals_env environment. Then, install gunicorn, psycopg2, flask, flask-sqlalchemy, and pandas. Finally, initialize the database by running python initdb.py, executing run.sh.


3.Create Procfile 


Prockfile is to instruct Heroku to run the app. Add the code of web: gunicorn pet_pals.app:app to the Procfile


4.Create the Heroku App

Sign up a Heroku account and create a new app. In the deployment method, select GitHub and connect to Pet_Pals repo. Navigate to Manual deploy and click deploy Branch. Navigate to Resources, search Heroku Postgres, click Provision.

