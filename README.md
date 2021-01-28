# Introduction
- Socket.IO is a JavaScript library for real-time web applications. 
- It enables real-time, bi-directional communication between web clients and servers. 
- It has two parts:- 
1) a client-side library that runs in the browser 
2) a server-side library for node.js. Both components have an identical API.

# Socket.IO - Environment Setup
- To get started with developing using the Socket.IO, you need to have Node and npm (node package manager) installed. 
- If you do not have these, then first install node on your local system.   
- Confirm that node and npm are installed by running the following commands in your terminal.
1. node --version
2. npm --version
- Open your terminal and enter the following in your terminal to create a new folder and enter the following commands.
1. $ mkdir test-project
2. $ cd test-proect
3. $ npm init
- It will ask you some questions; answer them in the following way 

![alt text](https://www.tutorialspoint.com/socket.io/images/environment_setup.jpg)

- This will create a ‘package.json node.js’ configuration file.Now we need to install Express and Socket.IO. To install these and save them to package.json file, enter the following command in your terminal, into the project directory.

1. npm install --save express socket.io

- One final thing is that we should keep restarting the server. When we make changes, we will need a tool called nodemon. To install nodemon, open your terminal and enter the following command 

1. npm install -g nodemon

- Whenever you need to start the server, instead of using the node app.js use, nodemon app.js. This will ensure that you do not need to restart the server whenever you change a file. It speeds up the development process.
