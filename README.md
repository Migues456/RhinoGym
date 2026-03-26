# E-Business Gym - Proyecto Rhino Gym

Proyecto \& Laboratorio de E-business.



## Estructura del Proyecto

Este repositorio contiene el despliegue de una pagina y tienda virtual en \*\*WordPress + WooCommerce\*\* utilizando \*\*Docker\*\*.



## Requisitos

* Docker \& Docker Compose instalado.



## Instalacion y Despliegue

1\. Clonar el repositorio.

2\. Ejecutar el comando en la dirección de la carpeta:

&#x20;  `docker-compose up -d`

3\. Importar la base de datos:

&#x20; - He agregado una linea en compose para que la base de datos se importe de forma automática, en caso de que no suceda:

&#x20;  - Acceder a phpMyAdmin en `localhost:8081`. ( Usuario y Contraseña: wpuser - wppassword )

&#x20;  - Importar el archivo `rhinogym_wordpress.sql` incluido en la raiz.

&#x20;  - Tambien puede usar el comando `docker exec -i wordpress_db mysql -u wpuser -pwppassword wordpress < rhinogym_wordpress.sql` luego del compose.

4\. El sitio estara disponible en `localhost:8080`.



## Herramientas Utilizadas

* Docker

* MySQL 8.0

* WordPress

* phpMyAdmin

* WooCommerce

* Github

