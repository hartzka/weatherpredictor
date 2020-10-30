worker: FLASK_APP=app.py python -m flask run --host=0.0.0.0 --port=5000
web: gunicorn --preload --worker 1 app:app
heroku ps:scale web=1
