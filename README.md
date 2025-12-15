# eko-entregables
Descargar el repositorio

Modificar el fichero docker compose con los siguiente parametros:

Servicio "fronteko" --> TARGET_IP debe asignarse el valor de la ip del host donde se ejecuta el compose.

Servicio "apieko" --> DB_HOST debe asignarse el valor de la ip del host donde se ejecuta el compose.

Crear la carpeta pg_data

Ejecutar:

$ docker-compose up -d


Ingresar al navegador a la direccion: http://localhost/

Aqui aparecera un menu con 3 opciones. Las opciones apuntan a la api:

- La primera retorna un mensaje saludo --> "message": "Hola ekoparty hackademy - Advanced Docker y Kubernetes Security"
- La segunda el estado de la base de datos (esta opcion se conecta con la db y devuelve ok si pudo conectarse) --> "status": "OK"
- La tercera la version de la api --> "version": "1.0.0"

