# SHOWCASE API

TO RUN SERVER:
1. FIRST OPEN ANY TERMINAL
2. run  `cd NodeJSApi`          make sure before running the server, we are in the NodeJsApi directory.
3. run `node server.js`      When we node the server, we should be able to see a prompt saying the server and the database are successfully initialized.
4. run the front end repository by running `npm install` and `npm start`



In case the db is not connected, make sure the following connections inside `dbconnection.js` the following information are correct.
    host : "34.83.191.45",
    port : "3306",
    user : "root",
    password : "seng401",
    database : "SHOWCASE",

# ShowCase-FrontEnd

Clone normally and enter the directory afterwards. Then do `npm install && npm start` and give it a minute or so. The website runs on port 3001 while the server runs on port 3000. However, this can be changed through package.json on each respective project.

Due to the nature of this application, it is required to also run the backend server in order to use it. This is because the website sends and recieves data from that server, and thus, has a dependency on it.


Note: For the purpose of the SENG 401 demonstration we elected to demo to a TA rather than host the entire application on the internet.
