# Documentación para prueba técnica desarrollador Full Stack | Avera

1.- Se realizó un clon del repositorio indicado, creando un branch con nombre "AlejandroRuiz"

2.- Se realizó la instalación de WordPress en el directorio del proyecto

3.- Se fusionó el Branch AlejandroRuiz con el master del proyecto, debido a que primeramente se eligiò a Heroku como plataforma para el despliegue de la aplicación, y heroku solo puede trabajar con los masters de Git 

![Git Log](https://alexestudio86.github.io/avera-test/assets/gitLog.PNG "Git Log")

4.- Se creó una app en heroku con el nombre avera-test (http://avera-test.herokuapp.com), para realizar el despliegue de la aplicación de WordPress en vivo, sin embargo, ya que WordPress utiliza un contenedor similar a Docker, no se puede continuar la instalación, ya que los cambios realizados no son multisesión (esto también ya que Heroku está pensado para utilizarse en entornos de nodeJS y por ende trabaja mejor con bases de datos no relacionales como mongoDB, en lugar de bases de datos relacionales como MySQL)

5.- Al no poder proseguir con la instalación de WordPress a través de Heroku, se tomó la decisión de montar el proyecto en 1&1

6.- Una vez que se instaló WordPress, se añadio un dominio para pruebas y un certificado de seguridad

7.- Se instaló y activó el plugin woocommerce para la visualización de los productos, en conjunto con el carrito de compras acorde a las indicaciones del ejercicio

8.- Se implementó la división de precios por usuario acorde a la instrucción del ejercicio, para ver la diferencia de precios, es necesario acceder a la sección de cuenta con los siguientes datos:
https://avera-test.com/mi-cuenta
user: guest
pass: averaTesting2022

9.- El resultado final puede ser consultado en https://avera-test.com/tienda


## Observaciones:

Se omitió un poco el diseño del sitio indicado para seguir el ejercicio, ya que el mismo cuenta con elementor instalado, y por ende, se tiene mucho mayor control en el diseño del sitio
