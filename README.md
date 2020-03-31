# BlogApp_Tornado

Blogging website using python framework tornado

To Run the application:

$ pip install -r requirements.txt

$ sudo apt-get update

$ sudo apt-get install mysql-server

$ sudo -i

Inside the mysql cli
$ ALTER USER 'root'@'localhost' IDENTIFIED WITH mysql_native_password BY '<any-password>'; 

Now just import the `Dump202000401.sql` database file in MySql WorkBench and start the service.

Service can be stopped by `sudo service mysql stop`

Finally after starting the mysql service, run 
(Also check your root mysql password from app.py, it should be same as your sql pass word)
$ python app.py

Now open localhost:8000 and the blog is running, register yourself as a new user and get started.

