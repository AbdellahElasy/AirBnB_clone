https://s3.amazonaws.com/alx-intranet.hbtn.io/uploads/medias/2018/6/65f4a1dd9c51265f49d0.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOUSBVO6H7D%2F20240628%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20240628T174844Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=cab99f707397e7483ec8dc045c79e9185e477f89ffdbc5681dba9580da8c363b

Welcome to the AirBnB clone project!
Before starting, please read the AirBnB concept page.

First step: Write a command interpreter to manage your AirBnB objects.
This is the first step towards building your first full web application: the AirBnB clone. This first step is very important because you will use what you build during this project with all other following projects: HTML/CSS templating, database storage, API, front-end integration…

Each task is linked and will help you to:

put in place a parent class (called BaseModel) to take care of the initialization, serialization and deserialization of your future instances
create a simple flow of serialization/deserialization: Instance <-> Dictionary <-> JSON string <-> file
create all classes used for AirBnB (User, State, City, Place…) that inherit from BaseModel
create the first abstracted storage engine of the project: File storage.
create all unittests to validate all our classes and storage engine

Command List
Create Command
Create Command to create a new instance of <Model_name> Example:

(hbnb) create <Model_name>
Update Command
Update Command to Updates an instance based on the Model_name and id by adding or updating attribute. Example:

(hbnb) update <Model_name> <id> <attribute name> <value>
Destroy Command
Destroy Command to deletes an instance and save changes based on the Model_name and id

Example:

(hbnb) destroy <Model_name> <id>
Show Command
Show Command to prints the string representation of an instance based on the Model_name and id

Example:

(hbnb) show <Model_name> <id>       
All Command
All Command to Prints all string representation of all instances based or not on the <Model_name>. Example:

(hbnb) all                
    to print all models
(hbnb) all <Model_name>                
    to print all <Model_name> 
Quit Command
Quit command to exit the program Example:

(hbnb) quit
Proudly written by:
AbdellahElasy
