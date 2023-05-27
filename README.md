# RESTFull_dockerize
Dockerize a CRUD RESTful API using NodeJS and MongoDB

![image](https://github.com/ChathraNavoda/RESTFull_dockerize/assets/91416868/d5aa9950-5764-47e6-9b9f-ca1291dadf65)

## Steps for Dockerizing

1. Initialize the node js project. package.json
```javascript
npm init
```
2. Install the necessary dependencies
```javascript
npm i body-parser express mongodb mongoose
```
3. Start the server

*Make sure to change the json script as bellow*
```
"scripts": {
    "start": "node app.js"
  },
```
4. Start the server
```javascript
npm start 
```
5. Run this code to build the ocker Compose

```
docker-compose build 
```
6. Run this command to start the container

```
docker-compose up -d 
```
7. To see the running containers

```
docker ps
```
8. Connect to the running Docker container and start mongo db shell

```
docker exec -it a9090a0bd182 mongosh -u "root" -p "example"
```
9. To see the available databases

```
show databases
```
10. To use the database

```
use test
```
11. To get the collection

```
db.getCollectionInfos()
```
12. To get all data (In the products collection)

```
 db.products.find()
 ```
