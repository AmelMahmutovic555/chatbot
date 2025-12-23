# chatbot

LINK OF THE DEPLOYED WEBSITE
https://chatbotfrontend-1588-gtqd85tp9-amels-projects-f7598538.vercel.app/

1. Tech stack?
- Creating this app i used Node JS for the backend React JS for the frontend and PostgreSQL as the database and OpenAI Api as the chat bot for this app.

2. How to run frontend & backend?
- To run backend Node JS the command is nodemon app.js
- To run frontend React JS the commans is npm start

3. How to access the AI?
- I created my personal API KEY which is in the .env file, for the app to run successfully please use your own api key from OpenAI and paste it in the apiKey that currently has process.env.OPEN_AI_KEY
  but i will host the website as well just in case.

4. How this would integrate with a real AI agent?
- When the Frontend sends the information to the backend with the information provided by the user in this case the message, that message is sent via a POST Request to the backend. The backend accepts that
  request first thing it looks for is the request.body which has the information about the message, next thing it does it connects it's server with the OpenAI server, after the connection is established
  that request that the backend server has in this case the message provided from the frontend it sends that message to the OpenAI chatbot. The chatbot gives an answer for the message it sends that answer back
  to the backend server than the backend server sends that message to the frontend and thats how they communicate.
