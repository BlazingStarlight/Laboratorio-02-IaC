## LABORATORIO 02
Despliegue con Docker Compose y desarrollo de la actividad propuesta.
Desplegué los tres contenedores para ejecutar la API "nmatsui/hello-world-api" en puertos 3000, 3001 y 3002; cada uno de estos emiten un mensaje propio saludando desde su respectiva API. Se hizo uso de variable de entorno para las credenciales de PostgreSQL (.env). 

## COMANDOS:
Git Commit (Subir commit al repositorio):
```bash
git commit -m "doc:"
```
Docker Compose (Ejecutar el .yaml y desplegar los contenedores)
```bash
docker compose up -d
```
## COMANDOS USADOS PREVIAMENTE
```bash
docker run -d --rm -p 3000:3000 nmatsui/hello-world-api
docker run -d --rm -p 3001:3000 nmatsui/hello-world-api
```
```bash
some-postgres -e POSTGRES_PASSWORD=mysecretpassword -d postgres
```
```bash
docker exec -ti e4c02a838de6 /bin/sh
```

## CRÉDITOS
Moreno Rodríguez Diego Saúl - 000245429

## MENSAJE FINAL
Lamento que los últimos agregados hayan sido fuera del tiempo, tuve que realizar la activad durante las últimas horas del día por una situación familiar. Mis tíos viajaban hoy de vuelta a Lima para irse de nuevo a Canadá y quería pasar algo de tiempo con ellos. No se ha utilizado IA en el desarrollo de esta activad.

## CAPTURAS
<img width="999" height="546" alt="image" src="https://github.com/user-attachments/assets/4a678dda-ed75-4793-bf73-aa5d1a9db4cc" />
