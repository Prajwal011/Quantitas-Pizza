# pizza_prediction_system_master

## How to run project?
1. Goes to project base directory and enter below command to start server.
> python manage.py runserver
2. Once start server successfully then enter [http://127.0.0.1:8000/pizza_prediction](http://127.0.0.1:8000/pizza_prediction) URL in the browser.

## How to migrate DBSqlit3 database?
1. First trigger make migrations command. If you hade make any changes in the module class.
> python manage.py makemigrations
2. Then run the migrate command. If ask any default value of created new column please add it.
> python manage.py migrate
