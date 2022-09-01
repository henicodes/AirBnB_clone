# AirBnB clone - The console
This is a project managmant and tracking file used to build an AirBnB clone named hbnb for ALX SE program.
*The goal of the project is to deploy on your server a simple copy of the [ AirBnB website.](https://www.airbnb.com/)*
After 4 months, you will have a complete web application composed by:
- A command interpreter to manipulate data without a visual interface, like in a Shell (perfect for development and debugging)
- A website (the front-end) that shows the final product to everybody: static and dynamic
- A database or files that store data (data = objects)
- An API that provides a communication interface between the front-end and your data (retrieve, create, delete, update them)
## FINAL PRODUCT EXPECTED TO LOOK LIKE  
![Final Product](https://github.com/henicodes/AirBnB_clone/blob/master/hbnb%20final%20look.png)

## PROJECT OVERVIEW
This hbnb clone will be like the AirBnB website that contains listing of privately owned properties avalible for rent.
The user can sort through the listings by location and amenities.
In this case by states and city contain location data like chicago, newyork state names, etc and
as well as amenities avaliable at each airbnb like TV, air conditioning, etc
- when you first load it mainly pupulate with every airbnb avalible. you will be looking at the data which isn't efficient if you are just looking for to find one airbnb in particular location or amenities.
- so inorder to avoid the above issue at the top of the screen there are fileters you can search for that particular interste.
- This isn't a hard coded website all this airbnbs are pulled form a data base and each entry does have this data being generated form the data in the database. 
- The user will only be able to sort and parase through the data and find airbnbs that are avalible. but as a developer you will need to be able to modify and edit data very quikly and very effiently this is where we undertake the first part of this project: to create a console a command line tool to acess and munipulate data 
## The Console
This command line tool is good because its like a shell comand line tool to edit and modify data on your comupter we are going to create a shell or a consol to access and modify the data for this site(hbnb site), this console will be able to store data both in a JSON file as well as mysql database stroage engines.
*[The consloe in action holberton school video demo](https://www.youtube.com/watch?v=jeJwRB33YNg)*
- create your data model
- manage (create, update, destroy, etc) objects via a console / command interpreter
- store and persist objects to a file (JSON file)
The console is a command interpreter to manage objects abstraction between objects and how they are stored.
The console will perform the following tasks:
- Create a new object (ex: a new User or a new Place)
- Retrieve an object from a file, a database etc…
- Do operations on objects (count, compute stats, etc…)
- Update attributes of an object
- Destroy an object
### Files and Directories
- models directory will contain all classes used for the entire project. A class, called “model” in a OOP project is the representation of an object/instance.
- tests directory will contain all unit tests.
- console.py file is the entry point of our command interpreter.
- models/base_model.py file is the base class of all our models. It contains common elements:
- attributes: id, created_at and updated_at
- methods: save() and to_json()
- models/engine directory will contain all storage classes (using the same prototype). For the moment you will have only one: file_storage.py.
