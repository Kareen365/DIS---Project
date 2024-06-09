# Task Manager

To set up this project you have to install the `requirements.txt`:
```bash
pip install -r requirements.txt
```

And then create a database in your local postgres called `dis`, and run the `init.py` file:
```bash
python init.py
```
This will create the necessary tables.

(The app assumes that your username and password for PostgreSQL is `postgres:postgres`).

To open the web-app you will have to use the following command:
```bash
flask --app app run
```
This will open the web-app on its default site.

You will start by registering a new user so that you can login to the site. After this, you will be able to add new tasks and so on.
This task manager is not meant to be like the one you find on Windows OS but as a means of keeping track of what to do.

We are aware of some missing functionality that brings the quality of the app down. The main issue consists of the table not showing up when tasks has been added. 
Because of this, we are not able to showcase DELETE and UPDATE. The INSERT works fine but since the table does not show up, it can only be seen if the QUERY tool is used in the database. All other functionality should work if we would be able to show the table on the web-app.


