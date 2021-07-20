# SimpleFlaskApp

#create myproject and a venv folder within

mkdir myproject
cd myproject
py -3 -m venv venv

#activate the environment

venv\Scripts\activate

#install Flask 

pip install Flask

#App set up
set FLASK_APP=hello
flask run

Note** -- To enable all development features, set the FLASK_ENV environment variable to development before calling flask run.
set FLASK_ENV=development
flask run



