MEAN Stack is a combination of the following components:
1.	MongoDB (Document database) – Stores and allows retrieval of data.
2.	Express (Back-end application framework) – Makes requests to Database for Reads and Writes.
3.	Angular (Front-end application framework) – Handles Client and Server Requests
4.	Node.js (JavaScript runtime environment) – Accepts requests and displays results to end user

Task
This project is aimed at implementing a simple "Book Register Web Form" using MEAN-STACK
***

Node.js installed
```
sudo apt install -y nodejs
```
![Image](./images/nodejs.png)
***

Install MongoDB
MongoDB stores data in flexible, JSON-like documents. Fields in a database can vary from document to document and data structure can be changed over time. For our example application, we are adding book records to MongoDB that contain book name, isbn number, author, and number of pages.
mages/WebConsole.gif
```
sudo apt install -y mongodb

```
***
Start mongodb server and verify that the service is up and running  
```
sudo service mongodb start
```````
``````
sudo systemctl status mongodb
``````
![screenshot](./images/mongodbactive.png)

