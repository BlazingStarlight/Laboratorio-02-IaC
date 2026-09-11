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
<img width="1169" height="277" alt="image" src="https://github.com/user-attachments/assets/8a26c773-3133-4153-be79-a973d08a1ca2" />
<img width="743" height="147" alt="image" src="https://github.com/user-attachments/assets/859eb4df-1cb2-4105-9eca-d69c768587cb" />
<img width="704" height="149" alt="image" src="https://github.com/user-attachments/assets/c3f96bf6-6d35-40d1-95e7-2212f5f8c7fe" />
<img width="432" height="131" alt="image" src="https://github.com/user-attachments/assets/19789114-b59f-41a0-abc4-8c5fe2a64c77" />
<img width="1920" height="1040" alt="image" src="https://github.com/user-attachments/assets/52d18867-d4f6-400a-9f4e-18c928c60338" />


