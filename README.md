# Laboratorio 02
Hoy utlizaremos docker compose para poder desplegar un servicio web y una base de
datos
STACK Tecnico
API
- Aplicación JAVA dockerizarla (crear la imagen)
- docker pull nmatsui/hello-world-api


- $ docker run -d --rm -p 3000:3000 nmatsui/hello-world-api
-
BD PostgreSQL
docker run --name some-postgres -e POSTGRES_PASSWORD=mysecretpassword -d postgres

COMANDOS
Deben especificar los comandos que voy a ejecutar
```bash
docker compose up -d
```

CONFIGURACIONES
.env
```
VAR=V