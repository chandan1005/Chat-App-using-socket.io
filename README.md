# Chat-App-using-socket.io
using NodeJS and Socket io libary to build bidirectional communication
only as group
# about Socket io
Socket IO is an event-driven framework used for bidirectional communication between a client and a server. It is mainly used for broadcasting messages to all connected clients in a particular server just like WhatsApp group chats. This framework is event-driven, which means that the client and server will respond to events sent by each other. In this article, we will see how to build a chat app using socket.io and Node JS. As Node JS can handle events, socket.io serves as a great framework for integration with Node JS.

# Step 1: 
We will start off by creating a new folder called Chat-app-socket.io . Open your command prompt and navigate to the folder we just created.
>mkdir Chat-app-socket.io
>cd Chat-app-socket.io

# Step 2: 
Now, Initialize the node package by typing in the following command in the terminal:
> npm init -y

# Step 3: 
This will create a package.json file for us so that we can install the necessary libraries. Now type in the command:
>npm install express socket.io

# Step 4:
 Now, in the Chat-app-socket.io folder, create two files – index.html and index.js:
 >index.html 
 >index.js

# Implementation:
 creating a real-time chat application using socket.io and NodeJs:

 # index.html:
  Inside index.html, we are simply creating a form with two inputs. The user’s name and his message. Inside the script tag, we are using the socket instance to send the user message to our express server and also listen for incoming events from the server to display the username and message on the browser.

  # index.js:
   Inside the index.js file, we are creating an express app and serving our HTML file on the server. We are also creating a socket io instance that listens for the incoming event from index.html and emits events to index.html.

   # to run the code use command line and below commands
   >node index.js
   then open browser and open this below url
   # http://localhost:7000