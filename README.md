# Documentación para prueba técnica desarrollador Full Stack | Avera


1.- Se realizó un clón del repositorio indicado, creando un branch con nombre "AlejandroRuiz"

2.- Se realizó la instalación de wordpress en el directorio del proyecto

3.- Se creó una app en heroku con el nombre avera-test (http://avera-test.herokuapp.com), para realizar el despligue de la aplicación de wordpress en vivo, sin embargo, ya que wordpress utiliza un contenedor similar a docker, no se puede continuar la instalación, ya que los cambios realizados no son multiseción (esto también ya que heroku está pensado para utlizarse con bases no realaciones como mongoDB, en lugar de interactuar con base relaicones como mySQL)

4.- se fucionó el branch AlejandroRuiz con el master del proyecto, debido a que heroku solo puede traajar con masters de git
![Git Log](https://alexestudio86.github.io/avera-test/assets/gitLog.PNG "Git Log")

5.- Al no poder proseguir con la instalación de wordpress a través de heroku, se tomó la desición de montar el proyecto en 1&1

6.- Una vez que se instaló wordpress, se añadió un certificado de seguridad

7.- Se implementó la división de precios por usuario, para ver la diferencia es necesario acceder a la sección de cuenta con los siguientes datos:
https://avera-test.com/mi-cuenta
user: guest
pass: averaTesting2022

8.- El resultado final puede ser consultado en https://avera-test.com/tienda

## Observaciones:

Se omitió un poco el diseño del sitio indicado para seguir el ejercicios, ya que el mismo cuenta con elementor instalado, y por ende, se tiene mucho mayor control en el diseño del sitio
