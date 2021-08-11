# Employee-Managment-System

Emplyee Managment System using Python, HTMLl, PostgreSQL, Flask, Flask-SQLAlchemy.

Create Employees and Department table in PostgreSQL by and perform various operations like insert, show_table, update, delete, sort, select using Python, Flask, Flask_SQLAlchemy.

Flask used as an API to connect backend code with HTML webpage, FlaskSQLAlchmy module used to connect database and run query with PostgreSQL.


Note: 
1. Before running code on your system install all modules by run this commands in terminal: pip install -r requirements.txt

2. app.config['SQLALCHEMY_DATABASE_URI'] = 'postgresql://postgres:password@localhost/Employee_Management'
    In this PostgreSQL connectivity statement use your use your PostgreSQL username, password and database name otherwise this will give you error.
    
3. fill your database connectivity information and use this:
    app.config['SQLALCHEMY_DATABASE_URI'] = 'postgresql://<username>:<password>@localhost/<database_name>'
  
 4. If after running code localhost URL not appear in terminal then paste this URl in Browser : http://127.0.0.1:5000/
  

For better experiance use crome as default browser and Pycharm as IDE.
