# ChatGPT-ChatBot
Developed a full-stack web application based AI Chatbot application, inspired by ChatGPT, by using MERN Stack and OpenAI. It's a customized chatbot where each message of the user is stored in DB and can be retrieved and deleted. It's a completely secure application using JWT Tokens, HTTP-Only Cookies, Signed Cookies, Password Encryption, and Middleware Chains.

# YouTube Demo:
I have created a YouTube video showing the Demo of the project and explaining the build and how it focuses on the value it brings to our day-to-day life and how it could possibly be combined with Google search or chatGPT to be our ancillary resource that’s trained on our most personal and valuable private and public data. 

https://youtu.be/cqPhwt7iJtw

# Screenshots
## Landing Page
![Screenshot (211)](https://github.com/Brothin/ChatGPT-ChatBot/assets/78947331/b94afd02-3f55-4c92-bb02-5179f7421170)
## Chat Page
![Screenshot (212)](https://github.com/Brothin/ChatGPT-ChatBot/assets/78947331/60e7898e-9de9-4fe4-ae2c-2b898478d481)

# Getting started

## Clone the repository
```
git clone https://github.com/Brothin/ChatGPT-ChatBot.git
```
```
cd ChatGPT-ChatBot
```

## You need
• Node

• MongoDB or Mongo Atlas

• NPM

## Create your MongoDB account and database/cluster
• Create your own MongoDB account by visiting the MongoDB website and signing up for a new account.

• Create a new database or cluster by following the instructions provided in the MongoDB documentation. Remember to note down the "Connect to your application URI" for the database, as you will need it later. Also, make sure to change with your own password.

• Add your current IP address to the MongoDB database's IP whitelist to allow connections (this is needed whenever your ip changes).

## Get your API Credentials
Get OPEN_AI_SECRET and OPENAI_ORAGANIZATION_ID from https://platform.openai.com/ to store them in .env file in the backend folder.

## Create .env file
Create a .env file in the backend folder to store your credentials. This file will store environment variables for the project to run.
```
OPEN_AI_SECRET=
OPENAI_ORAGANIZATION_ID=
MONGODB_URL=
JWT_SECRET=
COOKIE_SECRET=
PORT=
```

## Installation
To install and run this project-

Install dependencies using npm in frontend folder and run client side of application.
```
cd frontend
npm install
npm run dev
```
Install dependencies using npm in backend folder and run server side of application.
```
cd backend
npm install
npm start
```
