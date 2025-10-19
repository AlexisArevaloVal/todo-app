# todo app - sistema de gestion para tareas

# descripcion del sistema
en este sistema que se nos asigno en la materia de implantacionn de sistemas, podemos crear tipos de tareas para asignar, actualizar y eliminar tambien mediente una interfaz medio simple

# arquitectura de todo app

el sistema de gestion de tareas tiene 3 bases lo que son el frontend, backend y su base de datos

frontend: lleva el Nginx sirviendose de archivos tales como el html, css y js
backend: este nos incluyelo que es el api rest node.js, el Express
la base de datos: postgresSQL,, para ver los get y post utilice el POSTMAN en el que podemos usar el json

# tecnologias que se usaron

backend: node.js 18, express y postgreSQL
frontend: html5, css, javascript puro
servidor web: nginx que se conecta con el front y backend
contenedores: docker y docker compose
control de las versiones: git

# requisitos

docker 20+
docker compose 2+
git

## Instalación y Ejecucion
Clonar repositorio
bash
git clone https://github.com/AlexisArevaloVal/todo-app.git
cd todo-app

# comandos utiles:
# Levantar servicios en segundo plano
docker-compose up -d

# Ver logs en tiempo real
docker-compose logs -f

# Ver logs de un servicio especifico
docker-compose logs -f backend

# Detener servicios
docker-compose down

# Detener y eliminar volumenes (elimina datos)
docker-compose down -v

# Reconstruir imágenes desde cero
docker-compose build --no-cache

# Ver estado de los servicios
docker-compose ps

# Ejecutar comandos dentro de un contenedor
docker-compose exec backend sh

# links

frontend: http://localhost:8080
backend: http://localhost:3000/tasks

# repositorio

https://github.com/AlexisArevaloVal/todo-app.git

# autor
estudiante: Alexis Eduardo Arevalo Valenzuela

# fecha de entrega

18 de octubre del 2025