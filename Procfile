worker: FLASK_APP=app.py python -m flask run --host=0.0.0.0 --port=$PORT
web: gunicorn application:app
heroku ps:scale web=1
