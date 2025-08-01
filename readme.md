## Media Tracker App - Seguimiento de Libros, Series, Películas y Videojuegos (Proyecto en desarrollo)

Gestor personal donde podrás registrar, listar y filtrar el contenido multimedia que consumes (libros, películas, series y videojuegos).

## Tecnologías utilizadas

Backend:
- Java 17
- Spring Boot
- Spring Web (REST API)
- Spring Data JPA
- MySQL

Frontend:
- HTML5 / CSS3
- Bootstrap 5
- JavaScript puro (fetch API)

## Funcionalidades actuales (V 1.0)

📚 Módulo Libros (V 0.1)
🎮 Módulo Videojuegos (V 0.3)
🎬 Módulo Películas (V 1.0)
📺 Módulo Series (V1.0)

CRUD completo:
- Crear  (V 0.1)
- Ver listado (V 0.1)
- Editar  (V 0.1)
- Eliminar  (V 0.1)

Filtros disponibles:
- Por título (V 0.1)
- Por autor (V 0.1)
- Por género (V 0.1)
- Por año de finalización (V 0.1)
- Por mes y año de finalización (V 0.1)

- Funcionalidad de valoración con estrellas (V.02)

## Estructura actual

- LibroController → Endpoints REST
- LibroService → Lógica de negocio
- LibroRepository → Acceso a base de datos
- Libro → Entidad
- LibroDTO → Actualización parcial

## Vista actual (Frontend)

- Barra de filtros combinada encima de la tabla
- Tabla con lista de libros
- Botones de editar y borrar integrados en la tabla
- Interacción vía JavaScript puro (fetch)

## Próximos pasos

- Posible exportación a Android en el futuro

## Cómo ejecutar el proyecto

- Levantar el backend (Spring Boot)
- Crear la base de datos media_tracker en MySQL
- Ejecutar el frontend desde el buscador (http://localhost:8080/)

## Autor - JaviDev707


