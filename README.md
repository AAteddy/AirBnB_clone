## AirBnB clone - The console
This is the console application of the AirBnB web application clone.

### Description
<p>This ALX project is a complete web application, integrating database storage, a back-end API, and front-end interfacing in a clone of AirBnB.</p>
<p>Right now the project currently only implements the back-end console.</p>

### Storage
<p>All classes are handled by the abstracted storage engine defined in the FileStorage class </p>
<p>Here the storage format used is JSON. Data is stored in a JSON format to a file.</p>
<p>Every time the backend is initialized, HolbertonBnB instantiates an instance of FileStorage called storage. The storage object is loaded/re-loaded from any class instances stored in the JSON file file.json. As class instances are created, updated, or deleted, the storage object is used to register corresponding changes in the file.json.</p>

### How to start the console
To start the console application use the command
 > ./console.py

### How to use the console
The console works with commands.
The following commands are currently handled by it.
`all`, `create`, `update`, `destroy`, `show`.

#### example
In order to print all the data stored in the storage engine
 > all
or 
 > all 'class name' 
to print objects of a particular class

In order to create and object and store it in the storage engine
 > create 'class name'

In order to update and save an existing object in the storage engine
 > update 'class name' 'id of object' 'attribute' 'value'

To destroy an object
 > destroy 'id of object'

To print an object
 > show 'class name' 'id of object'
