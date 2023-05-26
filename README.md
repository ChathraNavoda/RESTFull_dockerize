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
