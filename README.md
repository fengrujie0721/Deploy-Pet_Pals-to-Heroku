# Pet_Pals
Heroku is a cloud platform which can be used as a database to create app in virtual containers. Here, Heroku Postgres is applied to create a pet database. The pet's name, pet's latitude, and pet's longitude can be input to create pet map.


1.Configuation



Firts, activate pet_pals_env environment. Then install gunicorn, psycopg2, flask, flask-sqlalchemy, and pandas. Finally, initialize the database by running python initdb.py, executing run.sh.


2.Create Procfile 


Prockfile is to instruct Heroku to run the app. Add the code of web: gunicorn pet_pals.app:app to the Procfile
