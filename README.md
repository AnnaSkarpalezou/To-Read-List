# My To-Read Book List !

This is a to-read book list web app that relies upon a MongoDB database. It stores information such as a book's ```title```, ```author```, ```genre``` and a short ```description``` that are directly inputed by the user. Then it showcases that information in the ```All the books I have yet to read``` tab. The user is able to edit the listings and delete them. However, when a user decides to delete a listing, they are prompted to rate the book and/or provide additional information as that book will now be listed in a seperate collection and shown in the archives tab.

## Here is a link to a [deployed copy of my app](https://i6.cims.nyu.edu/~as11304/web-app-anula/flask.cgi/)

```https://i6.cims.nyu.edu/~as11304/web-app-anula/flask.cgi/```

I worked on this repository on my own.

### Meeting the Basic requirements

1. It is written in Python, using [flask](https://flask.palletsprojects.com/en/1.1.x/) and [pymongo](https://pymongo.readthedocs.io/en/stable/index.html).
2. It is deployed (i.e. published) to NYU CS Department's web server and MongoDB server, **i6**.cims.nyu.edu and **class-mongodb**.cims.nyu.edu, respectively.
3. (I like to think that) it allows the user to interact with data from the database in an intuitive and effortless manner, not requiring the user to understand any technical details of computer programming or databases.
4. It involves each of the basic operations of **CRUD** on documents in the database, triggered by user interactions.

Specifically:
- Create: performed in 2 seperate places. Firstly, when the user is prompted to add a book, alongside its info to the to-read list. Secondly, when the user deletes that book, she is prompted to provide additional information to create a new listing in a seperate collection under ```archives```.
- Read: performed in 2 seperate places. Firstly on the main to read list, where all books that have been added to the list are listed under  ```All the books I have yet to read```. Secondly in the ```Archives``` section, which stores information about the books that have been deleted from the to read list.
- Update: performed in the ```edit``` option under each listing in the main to read list.
- Delete: performed in the ```delete``` option under each listing.


