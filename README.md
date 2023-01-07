# Welcome to the finchat-banking-bot repository!

This chatbot server is built using Express.js and is designed to assist with various banking tasks. The chatbot can be integrated with platforms such as Slack and Facebook Messenger, providing a convenient way for users to interact with their bank.

The server connects to a database to store and retrieve user information and uses natural language processing (NLP) techniques to understand the intent of the user's message and determine how to respond.

To get started with the chatbot, clone this repository and follow the instructions below.

+ Make sure you have Node.js and npm installed on your system. If you don't have them installed, you can download them from the official website: https://nodejs.org/en/download/

+ Clone the finchat-banking-bot repository to your local machine.

+ Navigate to the root directory of the repository and install the dependencies by running the following command:

```
npm install
```

+ Create a new file called .env in the root directory of the repository. This file will store environment variables that the chatbot server needs to run.
In the .env file, add the following lines:

```
PORT=3000
```
This sets the port number that the chatbot server will listen on. You can change the port number to any number you like, as long as it is not already in use on your system.

+ Start the chatbot server by running the following command:

```
npm start
```
This will start the chatbot server and make it listen for incoming messages on the port number you specified in the .env file.

+ Test the chatbot by sending it a message through the chat platform you have integrated it with (such as Slack or Facebook Messenger).

