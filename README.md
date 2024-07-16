#  Flaskr - A demo Flask application

Made using following the [Flask tutorial](https://flask.palletsprojects.com/en/3.0.x/tutorial/).

## To run the application

```bash
# Create a virtual environment
python3 -m venv .venv

# Activate the virtual environment
source .venv/bin/activate

# Initialize the database
flask --app flaskr init-db

# Run the application
flask --app flaskr run --debug
```

The application will be available at [http://localhost:5000](http://localhost:5000).

## Running tests

```bash
# Run the tests
pytest

# Run the tests with coverage
coverage report

# Run the tests with coverage and generate an HTML report
coverage html # Open the file htmlcov/index.html in a browser
```