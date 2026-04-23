Las credenciales necesarias de tener en el .env para poder levantarlo:

· MYSQL_ROOT_PASSWORD=root

· MYSQL_DATABASE=empresa

· MYSQL_USER=user

· MYSQL_PASSWORD=pass

· MYSQL_HOST=db

Para levantar la contenedor con imagen predefinida

· docker compose up

· En el compose.yaml cambiar "build: ." por  "ivantriasgonzalez/docker_trias"

Para levantar el contenedor y construir la imagen

· docker compose up --build
 
 · En el compose.yaml cambiar "ivantriasgonzalez/docker_trias" por "build: ."

Para ver el proyecto levantado entra en esta url
  
· http://localhost:8080

Para parar el proyecto
  
· docker compose down -v
