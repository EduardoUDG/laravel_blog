<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400"></a></p>

### Blog CUCEI

El objetivo de este proyecto es crear un blog autoadministrable con Laravel 8, con la final de poder crear posts de ayuda para alumnos con dudas acerca de la gran variedad de temas y materias dentro del centro **Universitario CUCEI**, ya que no todos aprendemos del mismo ritmo academico que otros.

Entonces para solventar este problema de aprendizaje para los alumnos y dudas de temas especificos, podran consultar este blog para tener una mejor orientación acerca de los temas impartidos de la materia y también puedan profundizar en ella.

### Integrantes:
- ALEJANDRA YAREN FIGUEROA NORIEGA
- CHAVEZ DORADO EDUARDO


---

### Instalación:

-	Clonar el repositorio

- al directorio del proyecto

-	Usar el comando:  `composer install`

-   Usar el comando `npm install`

-   Usar el comando `npm run dev`

-	Crear archivo de variables de entorno: cp .env.example .env

-	Creamos una base de datos con el nombre `_blog`

-	Crear llave:   `php artisan key:generate`

-	Comando: `php artisan storage:link`

-	Comando: `php artisan migrate --seed`

### Nota, al momento de crear las migraciones e iniciar sesión, se creara el...
- usaurio: `admin@gmail.com` y password: `12345678` 

- Colocar en el navegador la URL para abrir el proyecto, por ejemplo : `http://localhost:8080/laravel_blog/public/`  o  `http://localhost/laravel_blog/public/`  | `http://laravel_blog.test`

- Fin de la instalación

### Nota

Si al momento de entrar la página aparece texto blanco con fondo bacio, es normal, ya que laravel por alguna razon no muestra el color de fondo por defecto respecto a los seeders y factories, pero si creamos posts estos si mostraran el fondo que se añada a dicho post y para ver los posts publicados, asegurese de marcar la opción `Publicado` al momento de crear un post 




