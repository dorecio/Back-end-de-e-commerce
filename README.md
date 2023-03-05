# Back-end-de-e-commerce
Back-end para sitio web de comercio electrónico que utiliza las últimas tecnologías

## Descripción

COMO propietario de un negocio
QUIERO poder ver y gestionar los departamentos, roles y empleados de mi empresa
PARA poder organizar y planificar mi negocio

## Tabla de contenidos

- [Descripción](#Descrición)
- [Instalación](#Instalación)
- [Uso](#Uso)
- [Contribución](#Contribución)
- [Pruebas](#Pruebas)
- [Preguntas](#Preguntas)

## Instalación

Requisitos

1. Node V16.18.0
2. VSCode (Editor de Codigo)
3. My SQL 
4. Insomnia Core

Enlace al repositorio

https://github.com/dorecio/Back-end-de-e-commerce

Instalación

1. Descargar o clonar el repositorio
2. Instalar dependencias:
   Abrimos la terminal o consola y establecemos la ruta de acceso a la carpeta de la aplicación, 
   estando ahi ejecutamos el siguiente comando:
    npm install
3. Accesar a MySQL
    mysql -u root -p
4. Crear el esquema desde MySQL Shell con el siguiente comando
   source db/schema.sql
5. Salir de MySQL con
    exit
6. Propagar la base de datos desde la línea de comando
    npm run seed
7. Iniciar el servidor de la aplicación
    npm start
    
## Uso

### Instrucciones de uso

Después de completar la instalación e iniciar el servidor, se probaran las rutas para obtener la
información almacenada en la base de datos.

Video demostrativo   https://watch.screencastify.com/v/VqLMrM8F9QAvT0XrSI78 

### Ejemplos de uso

Ruta GET para products

![img](/utils/rutas/get.PNG)

Rutas GET por ID para Tags 

![img](/utils/rutas/getById.PNG)

Rutas POST para Categories

![img](/utils/rutas/post.PNG)



## Contribuciones

1. Hacer un fork de este proyecto, haciendo clic en el botón "fork" en la parte superior del repositorio.
2. Crear tu propia rama con el siguiente comando en consola
   git checkout -b<nombre de rama>
3. Realice algunas adiciones o cambios en el archivo donde desea contribuir y haga un commit de su trabajo
   git add<archivo modificado>
   git commit -m"comentarios contribuciones a la app"
4. Envía cambios a la rama remota
   git push origin<nombre de rama>
5. Vuelve a la pagina del repositorio de "fork" y dá clic en el botón "Compare and Pull Request"
6. Ingrese descripción para ayudar al propietario de este proyecto a entender que es lo que se intenta contribuir
7. Hacer clic en "Create Pull Request"

## Pruebas

Se registran cambios y se reflejan en la base de datos original

Rutas PUT para products, Tags y Categories

![img](/utils/prueba/img1.PNG)
![img](/utils/prueba/img2.PNG)

## Preguntas

[GitHub](https://github.com/dorecio)

Si tienes preguntas adicionales y deseas contactarme puedes hacerlo por medio del siguiente correo electrónico
dorisrecio@gmail.com

