# Página Oficial de Grupo Ecoquintas

Este repositorio contiene la información y configuración necesaria para la página oficial de **Grupo Ecoquintas**. Está gestionado por el **Departamento de Tecnologías de Información**.

## Autor

**Juan Miguel Fernandez Araya**
**Guadalupe Gonzalez Pérez**  
**Luis Roberto Zúñiga Sánchez**  
**Lisbeth Vazquez Serrano**  
Departamento de Tecnologías de Información  
Grupo Ecoquintas

## Requisitos

- Docker
- Docker Compose

## Instalación

1. Clona el repositorio:
   git clone https://github.com/GrupoEcoquintas/Wordpress-EQ.git
2. Navega al directorio del proyecto:
    cd tu-repositorio
3. Construye y despliega los contenedores:
   docker compose up --build -d
4.Accede a la página web desde tu navegador en http://localhost:3000.

## Servicios
WordPress: Se ejecuta en el puerto 3000.
MySQL: La base de datos se ejecuta en el puerto interno 3306.

## Notas
Si encuentras un error de permisos en Apache ("Forbidden"), elimina la carpeta wordpress, ejecuta:
   docker compose down
   rm -rf wordpress
   docker compose up --build -d
## Contacto
Para cualquier duda o consulta, puedes contactar a Juan Miguel Fernandez Araya, por medio de la extension 146  o al correo jfernandez@ecoquintas.com, Departamento de Tecnologías de Información en Grupo Ecoquintas.

- Este archivo ahora incluye las partes relevantes en formato de código, como el `docker-compose.yml`, las configuraciones de entorno y los comandos que necesitas ejecutar.

