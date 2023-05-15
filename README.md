# Writing-tracker
To run the app locally, you can clone the GitHub repository (https://github.com/kibo-web-app-dev-jan-23/final-project---crud-app-meta-verse-1) and download all the dependencies in the requirement.txt: pip install -r requirements.txt

The app is deployed on: https://writing-tracker2.onrender.com/

What our app does:
Every author or student needs to keep track of whatever it is they are working on, and they also need to be time conscious of their writing. The writing tracker enables you to add the title of your write-up and the due date. The app provides every user with a library that contains their writeups and how many days they have left to the deadline. The user is also able to update, edit and delete this information.

Explain the tables in your schema:
It is consistent formatting for all data entries
Has unique keys for all entries and database objects
Each column in a table has a name and data type

The User Table contains the user's id, first name, last name, email and password
The Writeup table, contains the user's id as a foreign key to identify each writer. It also has columns for each writeup's id, the date it was created, the due date, content and its status(complete).
