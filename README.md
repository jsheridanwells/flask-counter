# Flask Counter

Stores the number of times a page reloads in a MySql table


To get it to connect to a local MySQL installation, 
create a `.flaskenv` file with the following:
```
FLASK_APP='manage.py'
FLASK_ENV=development
SECRET_KEY='my_secret_key'
DB_HOST=localhost
DB_USERNAME='<WHATEVER DB USERNAME YOUR APP RUNS WI
TH>'
DB_PASSWORD='<WHATEVER DB PASSWORD YOUR APP RUNS WI
TH>'
DATABASE_NAME='counter'
MYSQL_ROOT_PASSWORD='<YOUR MYSQL ROOT PASSWORD, THIS IS FOR THE TEST DB>'

```
 