web: gunicorn cre:app --log-file=-
init: FLASK_APP=cre.py flask db init
migrate: FLASK_APP=cre.py flask db migrate
upgrade: FLASK_APP=cre.py flask db upgrade