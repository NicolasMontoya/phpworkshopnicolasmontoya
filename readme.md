# Autor

Desarrollador por Edward Nicolas Montoya Arcila. 04/11/17

## Descipción
La aplicación articles se desarrollo como prueba tecnica para la compañia tres diseño. Su objetivo es servir como un CRUD basico para articulos.

## Lenguajes

- PHP v7 compatible v5.7
- JavaScript ECMAScript 2015

## Dependencias
- Node JS v7.2.1
- npm v3.10.10

## Frameworks
- Codeigniter v3.1.6
- Angular 1.6.6 (ultima versión).

## Librerias
- JQuery v3.2.1
- Font Awesome v4
- Materialize CSS v0.100.2 

## Requerimentos tecnicos

- APACHE 2
- PHP minimo v5.7

# Instalación

## Configuraciones

El despliegue de la aplcación se debe realizar en un servidor apache 2, con la posibilidad de acceder a los permisos apache-apache o que venga por defecto configurado para modificar los archivos .htaccess. 

Se debe configurar los parametros de base de datos en archivo app/application/config/database.php, el script correspondiente de base de datos SQL se encuentra en la raiz del projecto.

> Si se descarga el projecto desde GitHub, se debe usar el comando npm install parados el directorio web, para descargar las dependencias javascript necesarias.

Es de resaltar que la API guarda las imagenes en el directorio app/uploads por lo que si es un servidor de producción es necesario darle permisos de escritura a la carpeta.

### Despliegue

El projecto esta configurado en la dirección phpworkshopnicolasmontoya. Es decir para acceder a la aplicación se debe digitar la dirección:

> http://{servidor personal}/phpworkshopnicolasmontoya/web

La carpeta phpworkshopnicolasmontoya debe ser ubicada en la raiz del servidor en cuestión.

### IDE
- Visual Studio code 1.17.2

## Licencia

Licencia MIT