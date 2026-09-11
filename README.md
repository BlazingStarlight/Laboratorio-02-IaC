## LABORATORIO 02
Despliegue con Docker Compose y desarrollo de la actividad propuesta.
Desplegué los tres contenedores para ejecutar la API "nmatsui/hello-world-api", cada uno de estos emiten un mensaje propio saludando desde su respectiva API. 

## COMANDOS:

```bash
git commit -m "doc:"
```
```bash
docker compose up -d
```
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

## CAPTURAS
<img width="999" height="546" alt="image" src="https://github.com/user-attachments/assets/4a678dda-ed75-4793-bf73-aa5d1a9db4cc" />
