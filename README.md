# Proyecto Backend
Proyecto de prueba técnica para posición backend

## Objetivo

Crear una API con FastAPI que sirva los datos insertados previamente en una base de datos de PostgreSQL.

## Instrucciones

1) Hacer Fork del repositorio de la prueba
2) Desarrollar el proyecto
3) Crear un pull request al repositorio del proyecto

## Requerimientos

1) Importar los datos proporcionados en una base de datos en PostgreSQL mediante un script que haga la inserción

2) Crear la estructura del proyecto con FastAPI incluyendo el archivo de requirements y los archivos con los cuales se hizo la importación de los datos a la base de datos de PostgreSQL

3) Crear un endpoint que sirva la información en formato json de los sitios cargados, la respuesta se tiene que ver de la siguiente forma
```
{
    "points": [
        {
            "name": "Frambuesa",
            "total": 120,
            "state": "cdmx",
            "lat": 19.4695601654942
            "lon": -99.1668338701129
        },
        ...
    ]
}
```
4) Crear un endpoint que haga las agregaciones del totales por ciudad
```
{
    "cdmx": 452,
    "jalisco": 199,
    ...
}
```

Bonus:
1) Dockerizar el API y la base de datos para poder levantarlos con algun orquestador de  contenedores.
2) Agregar archivo de migraciónes de datos para automatizar la inserción de los datos proporcionados


## Entregables

Se tomará el pull request del fork del repositorio como entregable de la prueba con un tiempo máximo de 5 días a partir del envío de la prueba 

Se tomará en cuenta la estructura del código así como las buenas prácticas y la forma en generar el pull request al repositorio.

## Recursos

[Python](https://www.python.org/doc/)
[PostgreSQL](https://www.postgresql.org/docs/13/index.html)
[FastAPI](https://fastapi.tiangolo.com/tutorial/first-steps/)
[FastAPI-SQL](https://fastapi.tiangolo.com/tutorial/sql-databases/)
[Docker](https://docs.docker.com/)