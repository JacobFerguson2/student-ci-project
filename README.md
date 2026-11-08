# Student CI Project

A simple Python application used to demonstrate Continuous Integration with Jenkins and GitHub webhooks (CMSC 426, In-Class Activity 3).

## Project Structure
- `app.py` - application code (`add_numbers` function)
- `tests/test_app.py` - unit tests
- `tests/__init__.py` - marks tests as a package

## Requirements
- Python 3.x

## Run the application
    python app.py

## Run the tests
    python -m unittest discover -s tests -v

## Continuous Integration
Every push to `main` triggers a Jenkins build via a GitHub webhook. The build runs the unit tests and fails if any of the tests fails.