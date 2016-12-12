### Setup:
* Assumes MYSQL server is setup and data provided is loaded. 
    
    **Below configuration is used in the server code for MYSQL server:**
    * host     : 'localhost',
    * user     : 'root',
    * password : 'mysql',
    * database : 'got'


----------


### Attached code has two folders:
* server - node/Express
* client - Reactjs
    
    **Code also uploaded to github:**
    * https://github.com/skc-garimella/adp-hack-got-server.git
    * https://github.com/skc-garimella/adp-hack-got-client.git

----------

###Server Instructions:

* cd server
* npm install 
* npm start

    **server has 3 rest apis:**
    * [http://localhost:8070/api/all][1]  - returns all the server data in JSON format
    * [http://localhost:8070/api/ratings][2]  - returns the ELo rating for kings
    * http://localhost:8070/api/:king  - Example [http://localhost:8070/api/Joffrey%2FTommen%20Baratheon][3] - retuns all the battles fought by the King.

----------

###Client Instructions
* cd server
* npm install 
* npm start
* go to [http://localhost:8080/][4]


  [1]: http://localhost:8070/api/all
  [2]: http://localhost:8070/api/ratings
  [3]: http://localhost:8070/api/Joffrey%2FTommen%20Baratheon
  [4]: http://localhost:8080/
