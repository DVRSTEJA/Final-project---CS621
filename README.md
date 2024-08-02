# Final-project---CS621
final project zip file ,ppt ,report and icf


goagri a Django-based web application designed to replicate the library managment system app.


Prerequisites :-

Before you begin, ensure you have ticked all the following requirements:

-Python 3.x installed on your machine
-pip 
-Virtual environment package [optional]



Execution  :-

Follow these steps to set up and run the goAgri project on your local machine. (go to terminal)

Proceed to the path where your project directory is and open the folder containing all the project files reside.

1) setup a virtual envirnoment and activate it.

python -m venv env

For windows ( .\env\Scripts\activate) , for Mac os ( source env/bin/activate)

2)apply the database migration over the app ( update your database schema as the application evolves over time)

  (python manage.py migrate)  

if the migration failed we need to install pillow dependency because we have a need to manage image handling in django app
 so for that ( pip install Pillow )

3) run the deployment server

( python manage.py runserver )

 To access the application copy and paste the link that appears after executing this line over the browser.

and thats it you have successfully executed the application!!!


the users I have used in the video presentation.

librarian :- username - admin , password - library123
user :- username - likith ,password - django123
