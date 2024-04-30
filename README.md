# CRUD Laravel + Vue + Inertia + ChartJS (Library)

## Doble CRUD con login en Laravel 11 y Vue3

Doble CRUD con relación de muchos a muchos y relación de muchos a uno, se usa el sistema de autenticación Laravel Breeze. Se utiliza un Dashboard con <b>Laravel 11</b> y <b>Vue 3</b> con <b>Inertia.js</b>.

- Crud tradicional con paginación y subiendo imágenes para  <b>Libros</b>

- Crud en una sola vista para <b>Autores</b>

- Dashboard con estadística y Graficas de autores por paises y Libros por autor utilizando <b>ChartJS</b>

- Se crea un componente para el select y otro para botón de editar.

- Se utiliza Factory para crear 50 registros de paises, 25 autores, 50 libros y se vincula un autor por libro.


Instalación:

1) Crear una base de datos mysql

2) Clonar o descargar el proyecto en el directorio de tu servidor web

3) Acceder mediante terminal a la carpeta del proyecto

4) Ejecutar:  <b>Composer install</b>

5) Crear el archivo .env con los comandos: <b> cp .env.example .env</b>

6) Generar la API key ejecutando: <b> php artisan key:generate </b>

7) En el archivo .env colocar el nombre de la base de datos

8) Para ejecutar las migraciones: <b>php artisan migrate --seed</b>

9) Ejecutar <b>npm install</b> para las dependencias de node.js

10) Ejecutar <b>npm run build</b> y <b>php artisan serve</b> para visualizarlo en el navegador o puedes usar Laragon, xammp, etc.

## Tabla Countries
- id 
- country

## Tabla Authors
- id 
- name
- last name
- country_id


## Tabla Books
- id
- isbn
- title
- description
- publisher
- release_date
- pages
- imagen

## Tabla Author_book
- id
- book_id
- author_id


## Video de explicación

Si quieres ver el video en donde se explica el ejercicio paso a paso  [te comparto el siguiente enlace](https://youtu.be/sQwDLrleegA)