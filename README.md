        1. Pasos seguidos durante el proyecto

- Instalación de herramientas

Instalación de PostgreSQL y pgAdmin

Instalación de DBeaver para la ejecución avanzada de consultas

Creación de la base de datos del proyecto

- Importación de la BBDD proporcionada

Se creó una base de datos nueva (Proyecto_SQL_JesusGarrido)

Se importó el archivo .sql entregado por el máster

Se verificaron las tablas, claves primarias y relaciones del modelo

- Configuración del entorno

Ajuste del search_path para trabajar correctamente con el esquema public

Generación del diagrama ER en DBeaver

Creación de un script SQL único donde se resolvieron todas las consultas del proyecto

- Ejecución de las 64 consultas

Se resolvió cada punto del enunciado con consultas en PostgreSQL

Se utilizaron:

JOIN, LEFT JOIN, CROSS JOIN

funciones de agregación (COUNT, AVG, SUM, VAR_POP, STDDEV_POP)

subconsultas

CTE (WITH)

creación de vistas (CREATE VIEW)

tablas temporales

Todas las consultas están incluidas en el archivo principal del repositorio

        2. Informe del análisis realizado

Durante el proyecto se analizaron distintas áreas de la base de datos:

+ Catálogo de películas

Se exploraron los títulos, duración, costes de alquiler y categorías

Se identificaron diferencias entre duración media por clasificación

Se calculó la desviación y varianza del coste de reemplazo

+ Actores y reparto

Actores más frecuentes en el catálogo

Actores que participaron en géneros concretos (Action, Sci-Fi, Music…)

Actores sin participación en ninguna película

+ Inventario y disponibilidad

Cantidad de copias por película

Identificación de películas sin inventario (COALESCE utilizado para asignar 0)

Relación entre disponibilidad y alquileres

+ Alquileres y clientes

Top clientes por gasto

Clientes que más películas han alquilado

Alquileres en cada fecha y duración media real

Películas no devueltas por ciertos clientes

+ Staff y tiendas

Combinaciones de trabajadores y tiendas (CROSS JOIN)

Comparativa entre tiendas

El análisis permitió comprender cómo se relacionan las tablas y qué conclusiones se pueden extraer del catálogo, del comportamiento de los clientes y del inventario.

        3. Esquema de la Base de Datos

Se incluye un diagrama ER (Entity–Relationship) generado desde DBeaver en el repositorio como Proyecto Data Analytics - public.png

