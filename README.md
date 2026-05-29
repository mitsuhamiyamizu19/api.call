UNTAL, BHING MARRIE CLAIRE S.

ELEC 1

API CALL – POSTMAN

SHORT DESCRIPTION

This project is an API system created using Laravel and tested in Postman. It can perform different API requests such as GET, POST, PUT, PATCH, and DELETE for managing student records.

SETUP DESCRIPTION

First, create a new Laravel project using the command:

laravel new "projectname"

Next, create the model, migration, and controller using Artisan commands. Configure the database connection in the .env file and run migrations to create the tables.

After that, add API routes in api.php and create the CRUD functions inside the controller.

Open Postman and create a workspace and collection for the API requests.

Inside the collection, create the following requests:

GET – Retrieves and displays student data in JSON format.

POST – Adds new student information such as name, course, and email.

PUT – Updates the complete student information using the student ID.

PATCH – Updates only selected fields or specific student data.

DELETE – Removes a student record by ID or deletes all records.

URL HTTP: http://127.0.0.1:8000/api/students

GDRIVE LINK FOR VIDEO: 
