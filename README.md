# Express API Mongoose + MongoDB

<br>

![image](https://user-images.githubusercontent.com/16636086/138952802-f9f8bd82-62d5-4a24-9679-09744b41c92d.png)

---------------------------------------- CONFIG ----------------------------------------

```
npm init
npm install
npm update
npm run dev
npm run start

npm install express mongoose 

#### Mongo DB server
show dbs
use peliculas_db
db.createCollection('users')
db.createCollection('peliculas')
db.createCollection('pedidos')

cadena de conexión mongoDB: mongodb://user:password;@192.168.100.90:27017/geografiaMongo?authSource=admin&readPreference=primary&appname=MongoDB%20Compass&directConnection=true&ssl=false
```

---------------------------------------- END-POINTS ----------------------------------------
#### USERS
GET - localhost:3000

#### PELICULAS
GET - localhost:3000/movie
GET - localhost:3000/movie/:id
GET - localhost:3000/movie/available
POST - localhost:3000/movie
PUT - localhost:3000/movie/:id
DELETE - localhost:3000/movie
DELETE - localhost:3000/movie/:id

#### PEDIDOS
GET - localhost:3000/categorie
GET - localhost:3000/categorie/:id
POST - localhost:3000/categorie
PUT - localhost:3000/categorie/:id
DELETE - localhost:3000/categorie
DELETE - localhost:3000/categorie/id


---------------------------------------- HOSTING ----------------------------------------

En Heroku a traves de github -> https://api-peliculas-pedidos.herokuapp.com/
