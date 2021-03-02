# Mern App Backend
Una aplicacion backend REST API donde los usuario pueden compartir lugares, con imagenes y ubicacion, con otros usuarios. Cuenta las operaciones CRUD para los distintos lugares, subir imagenes, registro de usuarios, autenticacion, autorizacion. 

Fue desarrollada utilizando:

* Node js
* Express
* Axios 
* Javascrip ES6 async/await
* Multer
* Jsonwebtoken, Bcrypt
* Mongo DB, Mongoose
* Mongo DB Atlas  
* Postman para las pruebas de los HTTP request a los distintos endpoints 
* Heroku

La aplicacion se encuentra actualmente en : 
[MERN-Api](https://fernandez-mern-app.herokuapp.com/)

## API Endpoint
| Metodo | Endpoint              | Descripcion   |
| ------ | --------------------- | ------------- |
| GET    | /api/users            | Retorna una lista de todos los usuarios |
| POST   | /api/users/signup     | Crear un nuevo usuario + log in |
| POST   | /api/users/login      | Iniciar Sesion |
| GET    | /api/places/user/:uid | Retorna una lista de todos los lugares para un determinado user id (uid) |
| GET    | /api/places/:pid      | Mirar un lugar especifico por place id (pid) |
| POST   | /api/places           | Crear un nuevo lugar |
| PATCH  | /api/places/:pid      | Actualizar un lugar por place id (pid) |
| DELETE | /api/places/:pid      | Eliminar un lugar place id (pid) |

## FrontEnd
El repositorio del codigo front-end se encuentra en:
[Front-End](https://github.com/fernandezniko/mern-app-frontend)
