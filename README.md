# symfony2-lando
Drupal 8 Ready to Use Project with Lando

Descripción
----------------
Proyecto Drupal 8 de Ejemplo, ideal para comenzar a trabajar con Lando.

#Contenido:

1.- Todos los archivos de un proyecto Drupal 8 Base, listo para funcionar
2.- Los archivos para un tema personalizado, basado en Bartik, para que puedas comenzar a jugar con los CSS
3.- La base de datos de un proyecto Drupal nuevo
4.- Los módulos principales activados y configurados: (Admin Toolbar, Pathauto)
5.- El archivo de Lando, para que puedas poner en marcha en pocos minutos tu proyecto y además podrás ejecutar lando drush y lando composer, entre otros.

Video y documentación de Instalación
----------------
Puedes ver el video y la documentación

Visitando la web www.drupaladicto.com

o Viendo el video en este enlace: https://bit.ly/3LXHmnG

Instalación
----------------
1.- Clonar el repositorio


2.- Arrancar el lando, con el comando

    lando start


3.- Descargar las dependencias conel Composer

    lando composer update
	

4.- Configurar el archivo settings.php


5.- Importar la base de datos

    lando db-import drupal8_lando.sql


6.- Acceder a la web
	
## Para corregir posibles fallos, ejecutar el comando:

	lando rebuild
