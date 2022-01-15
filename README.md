# Corona-Chatbot

This chatbot is created to be able to answer queries and doubts realted to Corona Virus.
The app is built using the ChatterBot that makes it easy to generate automated responses to a user’s input.
ChatterBot’s training process involves loading example dialog into the chat bot’s database. This either creates or builds upon the graph data structure that represents the sets of known statements and responses.You can also create your own training class. Therefore we create a set of training data where we will give input some of the queries that are related to Corona Virus and associated answers to it.

ChattererBot comes with built in adapter classes that allow it to connect to different types of databases.Here we will be using the SQLStorageAdapter which allows the chat bot to connect to SQL databases.The database parameter is used to specify the path to the database that the chat bot will use. For this example we will call the database sqlite:///database.sqlite3. this file will be created automatically if it doesn’t already exist.

Once we have completed the chatbot file then we will design a flask app that will be use the chatbot file. In the app there is a section of gwtting the user's input which will be redirected to the chatbot file to get the desired answer.

![Screenshot (159)](https://user-images.githubusercontent.com/76935226/147967298-a0d0ba3d-22a9-4802-9752-4464e81cf14e.png)
![Screenshot (160)](https://user-images.githubusercontent.com/76935226/147967141-5892238a-9a88-495a-8f04-ac4337060672.png)
