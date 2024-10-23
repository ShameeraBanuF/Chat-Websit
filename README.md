Hello
I am Shameera
Welcome to Coding with Shameera
In this video we are going to create Chat Website
With 
•	Frontend – React js
•	Backend – Express js, Node js
•	Database- MongoDB
Before that make sure you have
•	Visual Studio Code (VS Code)
•	MongoDB 
•	Node js
Installed on your device.
For Complete Coding used in this project, visit my GitHub profile: https://github.com/ShameeraBanuF
For Video visit my Youtube Channel @CodingwithShameera1
Let us start…

BACKEND
First we create Backend with following steps:-
Step 1: Create a folder for Backend, Open it in VS code and also open terminal in it.
Step 2: Type npm init -y in terminal.
Step 3: Install required packages
	npm install express mongoose cors socket.io
Step 4: Create a file named server.js and type the code as shown.
Step 5: Create folder named models and create file named as ChatMessage.js and copy the code as shown

FRONTEND
Its time to create Frontend with below steps:-
Step 1: In terminal, type
	cd .. [to exit from backend folder]
	npx create-react-app chat-frontend 
	again change back to backend folder by
		cd chat-backend 
Step 2: Now open frontend folder in VS code {2 window of VS Code, one for backend another for frontend will ease the execution}
Step 3: Open terminal and install required packages for frontend
	npm install axios react-router-dom socket.io-client
Step 4: Next navigate to src folder where you can see App.css file & App.js file. Open those two files and delete the default code & type the code as shown.
Step 5: Create file named ChatRoom.js in src folder and type the code as shown

EXECUTION
Frontend: npm start
Backend: node server.js
