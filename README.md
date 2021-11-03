# Express API Mongoose + MongoDB

<br>

![image](https://user-images.githubusercontent.com/16636086/138952802-f9f8bd82-62d5-4a24-9679-09744b41c92d.png)

## CONFIG

```
npm init
npm install
npm update
npm run dev
npm run start

npm install express mongoose 


cadena de conexión mongoDB:
    "mongodb+srv://usuario:password.@cluster0.l3ts1.mongodb.net/pelisMongo?retryWrites=true&w=majority"

```

## END-POINTS 
```
---------------------------------------- USERS ----------------------------------------

post -> '/signup' -> EndPoint de crear usuario
post -> '/signin' -> EndPoint de logear usuario
get -> "/:id" -> EndPoint buscar perfil de usuario
delete -> "/:id" -> EndPoint de borrar usuario

---------------------------------------- PELICULAS ----------------------------------------
post  -> "/" -> EndPoint de crear una pelicula
get  -> "/" -> EndPoint de buscar todas las peliculas
get -> "/:id" ->  EndPoint de buscar una pelicula por id
get" -> /titulo/:titulo" -> EndPoint de buscar una pelicula por titulo
get ->"/genero/:genero" -> EndPoint de buscar una pelicula por genero
get-> "/actor/:actor" ->  EndPoint de buscar una pelicula por actor
get -> '/ciudad/:ciudad'  -> EndPoint de buscar una pelicula por ciudad


---------------------------------------- PEDIDOS ----------------------------------------
post -> "/" -> EndPoint de crear pedido
get -> "/" -> EndPoint de buscar todos los pedidos

```
## HOSTING 

En Heroku a traves de github -> https://api-tmc-pelis.herokuapp.com/
