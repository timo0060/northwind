# northwind

a [Sails](http://sailsjs.org) application
I have included a sample sails server, which interfaces with the northwind database, to get sails installed, install node, and npm into the system. once install you can install node with:
```
npm install -g sails
```
Once installed you can restore the two sample databases i have generated, one with single document classical archetecture of mongodb, and one with restful, relational structure generated through sails. Assuming mongodb is installed on the system and you have cd'd into the directory loaction, you can restore the two databases with:
```
mongorestore dump/
```
then spin up the sails server with
```
sails lift
```
From there you can test the server by navigating to [here](http://localhost:1337/employees), the final address line, defines which table to query, so it could be employees, or products, or orders, or whatever data you need, and is all based off of restful design standards for interaction
