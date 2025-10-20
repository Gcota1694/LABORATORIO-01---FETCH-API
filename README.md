🧪 Laboratorio 01 – Consumo de APIs con JavaScript
Descripción

En este laboratorio exploramos cómo conectar nuestras aplicaciones web con APIs externas usando Fetch y Promesas en JavaScript.
El objetivo principal fue entender el flujo completo de una petición HTTP: enviar la solicitud, recibir la respuesta, convertir los datos a JSON, procesarlos y manejar posibles errores, todo dentro de una página web interactiva.

Se desarrollaron cuatro ejercicios de complejidad creciente para practicar diferentes técnicas de consumo de APIs y manipulación del DOM.

Objetivos del Laboratorio

Realizar solicitudes GET a APIs públicas con fetch().

Manejar la asincronía con Promesas (.then() y .catch()).

Extraer y procesar datos JSON de manera dinámica.

Mostrar estados de carga y errores en la interfaz.

Construir URLs dinámicas para búsquedas y filtros.

Encadenar múltiples peticiones para obtener y mostrar información relacionada.

Ejercicios
Ejercicio 1 – Listado de Usuarios

API: JSONPlaceholder
Nivel: Básico
Qué se hizo: Se obtuvo una lista de 10 usuarios desde la API. Se validó la respuesta con response.ok y se mostraron los datos directamente en la página. Fue el primer acercamiento a fetch() y promesas.

Ejercicio 2 – Buscador de Pokémon

API: PokéAPI
Nivel: Básico-Intermedio
Qué se hizo: Se construyó un buscador donde el usuario puede ingresar el nombre o ID de un Pokémon.

Se construyó la URL dinámicamente.

Se manejó el error 404 cuando el Pokémon no existe.

Se mostraron propiedades detalladas como imagen, tipos y estadísticas.

Ejercicio 3 – Explorador de Países

API: REST Countries
Nivel: Intermedio
Qué se hizo: Se desarrolló un explorador de países con filtros por nombre o región.

Se limitó la visualización a 12 resultados.

Se extrajeron datos anidados: capital, idiomas, monedas y banderas.

Se aplicó lógica condicional para construir la URL según el filtro elegido.

Ejercicio 4 – Blog con Posts y Comentarios

API: JSONPlaceholder
Nivel: Intermedio-Avanzado
Qué se hizo: Se creó una mini aplicación de blog que:

Carga usuarios en un select al iniciar la página.

Realiza peticiones encadenadas para obtener posts y contar comentarios.

Permite cargar los comentarios al hacer clic sobre un post.

Controla la visibilidad de los comentarios usando JavaScript.

APIs Utilizadas

JSONPlaceholder: Datos de prueba (usuarios, posts, comentarios).

PokéAPI: Información de Pokémon (nombre, imagen, tipos).

REST Countries: Datos geográficos y demográficos de países.

Cómo Ejecutar

Descargar o clonar el repositorio.

Abrir el archivo HTML del ejercicio que quieras probar (ejercicio1.html, ejercicio2.html, etc.) en un navegador moderno.

Interactuar con la página y observar cómo se muestran los datos obtenidos de la API.
