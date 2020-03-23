# binder-datasette
Tools to create a datasette for mybinder.org

## Try it

https://binderlytics.herokuapp.com/binder-launches/binder

## Create DB

Run the `create-db.ipynb` to create a new database.

## Publish

Use something like `datasette publish heroku binder-launches.db --extra-options="--config facet_time_limit_ms:35000 --config sql_time_limit_ms:35000" --name=binderlytics` to publish the database to heroku.
