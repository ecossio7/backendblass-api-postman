# Ejercicios Propuestos

*Blass Academy*

---

## Temas

- Postman

## Indicaciones

- Todo lo que se necesita está en el PDF y en el video, NO es necesario visitar otras bibliografías
- Todo lo hecho debe ser explicado por el alumno
- No olvidar las buenas prácticas explicadas en clase
- Repositorio: [https://github.com/calvario31/BackendBlassAcademy](https://github.com/calvario31/BackendBlassAcademy)
- El link de la documentación está dentro del repositorio

---

## Ejercicio 1

- Documentar todos los APIs de Participantes

## Ejercicio 2

- Documentar todos los APIs de Videojuegos

## Ejercicio 3

- Agregar 3 environment
  - No Auth
  - Basic Auth
  - Bearer Token

## Ejercicio 4

- Declarar los siguientes tests para todos los requests
  - Status code correcto
  - Response time menor que 500ms

## Ejercicio 5

- Hacer un schema validation para los tests:
  - Obtener un recurso por ID
  - Crear un recurso
  - Editar un recurso
  - Editar parcialmente un recurso

## Ejercicio 6

- En el test de obtener el participante con ID = 20
- Verificar que:
  - nombre: David
  - correo: David_Goy@yahoo.com
  - likes: 210
  - dislikes: 1533
  - plataforma: youtube

## Ejercicio 7

- En el test de obtener el videojuego con ID = 25
- Verificar que:
  - nombre: Astro Bot
  - duración: 7
  - paginaWeb: https://winding-zebra.net/likes: 210
  - codigoPostal: 64902-8286
  - latitud: 108.22

## Ejercicio 8

- Declarar con data aleatoria los request body de crear un videojuego y participante

## Ejercicio 9

- Crear 1 request para cada caso de unhappy path, tanto para videojuego como para participante
  - Request body vacío (400)
  - No Auth (401)
  - Elemento inexistente (404)
- En total serían 6 request de un happy, 3 de participantes y 3 de videojuegos

## Ejercicio 10

- Exportar la colección con el ambiente de bearer token
- Ejecutarlo con Newman
- Mostrar el reporte
