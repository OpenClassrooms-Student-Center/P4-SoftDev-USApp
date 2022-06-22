# LITREVIEW

This repository contains basic code to get you started on the LIT Review platform.

## Structure

The project has two Django applications:
* `reviews`: contains the models for the `Book` and `Review` entities
* `users`: contains the model for the custom user model (see `AUTH_USER_MODEL` in [`settings.py`](litreview/settings.py))

## Setup

Install the dependencies (make sure you are using a virtual environment): `pip install -r requirements.txt`

Make sure the database migrations are applied: `python manage.py migrate`.

You can then run the server with `python manage.py runserver`.

Refer to [Django documentation](https://docs.djangoproject.com/en/) for more information.