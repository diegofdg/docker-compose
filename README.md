Ejercicio docker-compose:

* Crear un repositorio de github asegurándose de crear el README.md inicial
* Clonar el repositorio
* Crear el archivo docker-compose.yml
* Agregar un contenedor de nginx (https://hub.docker.com/_/nginx):
    * Mapeando el puerto 80 al puerto 80 (80:80)
    * Crear un volumen apuntando la carpeta actual (.) a la carpeta "/usr/share/nginx/html" del contenedor
* Inicializar el contenedor usando docker compose up
* Crear un archivo index.html. Puede tener un contenido básico `<h1>Hola mundo</h1>`
* Validar que al ir a http://localhost se ve el archivo index.html que creamos
* Si todo está bien, crear un commit con los archivos creados y hacer push