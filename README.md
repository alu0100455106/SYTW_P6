# Practica 6 - SYTW

## Despliege en Heroku de Rock, Paper & Scissors.
![](http://rubyskyepi.com/wp-content/uploads/2012/07/rock-paper-scissors-620x350.jpg)

***

### Descripción

   Esta práctica consiste en despliegar en Heroku nuestra aplicación Rock, Paper & Scissors.

### Pasos seguidos
   
   1. Crear una cuenta en Heroku
   2. Descargar Heroku Toolbelt
   3. Loguearnos mediante `heroku login`
   4. Crear un fichero Procfile que contenga "web: bundle exec rackup config.ru -p $PORT"
   5. Crear la aplicación con `heroku create`
   6. Introducimos `git push heroku master` para hacer el despliegue.
   7. Introducimos `heroku open` para abrir la aplicación.

### Visualización
 
 Se lleva a cabo accediendo a la URL [http://possessed-lowlands-9237.herokuapp.com/] (http://possessed-lowlands-9237.herokuapp.com/) en un explorador preferiblemente mediante navegación privada. 
 Aunque una vez introducido `heroku open` ya debe abrir el navegador automáticamente.

*** 

#### ETSII - Universidad de La Laguna
