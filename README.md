# Colección API: Gestión de Participantes y Videojuegos

Esta colección agrupa los endpoints de la API para la gestión de participantes y videojuegos, además del módulo de autenticación.

## Funcionalidades principales

- **Auth:**  
  Manejo de autenticación con el endpoint para iniciar sesión (`POST login`).

- **Participantes:**  
  Operaciones CRUD (Crear, Leer, Actualizar, Eliminar) para la gestión de participantes.  
  Incluye funcionalidades para obtener todos los participantes, buscar, ordenar, filtrar y actualizar tanto completamente como parcialmente.

- **Videojuegos:**  
  Operaciones CRUD similares para la gestión de videojuegos, incluyendo obtención, búsqueda, ordenamiento, filtrado, creación, actualización y eliminación.

---

## Repositorio

[https://github.com/calvario31/BackendBlassAcademy](https://github.com/calvario31/BackendBlassAcademy)

---

## Endpoints de ejemplo

- **No Auth:**  
  `http://127.0.0.1:3000/`

- **Basic Auth:**  
  `http://127.0.0.1:3000/basic`

- **Bearer Auth:**  
  `http://127.0.0.1:3000/auth`

---

## Recursos útiles

- Schema JSON: [https://www.jsongenerator.io/schema](https://www.jsongenerator.io/schema)  
- Datos aleatorios para pruebas: [https://learning.postman.com/docs/tests-and-scripts/write-scripts/variables-list/](https://learning.postman.com/docs/tests-and-scripts/write-scripts/variables-list/)

---

## Enunciado de la Tarea

[https://github.com/calvario31/BackendBlassAcademy](https://github.com/calvario31/BackendBlassAcademy)

---

# Ejecutar pruebas API desde la línea de comandos

### 1. Instalar Newman y el generador de reportes HTML

Abre Git Bash y ejecuta:

```bash
npm install -g newman
newman -v
npm install -g newman-reporter-htmlextra
newman-reporter-htmlextra -v
```

### 2. Ejecutar pruebas desde la línea de comandos y abrir el reporte generado

```bash
newman run <collection>.json -e <environment>.json
newman run <collection>.json -e <environment>.json -r htmlextra
start newman/newman_htmlextra-.html
```

# API BlassAcademyTarea

![image](https://github.com/user-attachments/assets/83cf93b1-68b4-4249-838d-029abe4cda3d)

## Auth

### POST /login
- Autentica usuarios y proporciona un token de acceso para sesiones autorizadas.

## Participantes

### GET /ObtenerTodosParticipantes
- Obtiene la lista completa de participantes registrados.

### GET /BuscarParticipantes
- Busca participantes según criterios específicos (nombre, estado, etc.).

### GET /OrdenarParticipantes
- Devuelve participantes ordenados según un campo específico (nombre, fecha, etc.).

### GET /FiltrarParticipantes
- Filtra participantes según parámetros personalizados (estado, rango de edad, etc.).

### GET /ObtenerParticipante
- Obtiene los detalles de un participante específico por ID.

### GET /ObtenerParticipante - 404
- Simula error de "No encontrado" cuando el participante no existe.

### GET /ObtenerParticipante - 401
- Simula error de "No autorizado" para acceso sin permisos.

### POST /CrearParticipante
- Crea un nuevo participante con los datos proporcionados.

### POST /CrearParticipante - 400
- Simula error de "Solicitud inválida" cuando los datos de creación son incorrectos.

### PUT /ActualizarParticipante
- Actualiza completamente los datos de un participante existente.

### PATCH /ActualizarParcialmenteParticipante
- Actualiza parcialmente los datos de un participante.

### DELETE /EliminarParticipante
- Elimina un participante específico de la base de datos.

## Videojuegos

![image](https://github.com/user-attachments/assets/297f1551-14be-479c-bbca-1704dac8e492)

### GET /ObtenerTodosVideojuegos
- Obtiene la lista completa de videojuegos disponibles.

### GET /BuscarVideojuegos
- Busca videojuegos según criterios específicos (título, género, etc.).

### GET /OrdenarVideojuegos
- Devuelve videojuegos ordenados según un campo específico (nombre, fecha de lanzamiento, etc.).

### GET /FiltrarVideojuegos
- Filtra videojuegos según parámetros personalizados (género, plataforma, etc.).

### GET /ObtenerVideojuego
- Obtiene los detalles de un videojuego específico por ID.

### GET /ObtenerVideojuego - 404
- Simula error de "No encontrado" cuando el videojuego no existe.

### GET /ObtenerVideojuego - 401
- Simula error de "No autorizado" para acceso sin permisos.

### POST /CrearVideojuego
- Crea un nuevo videojuego con los datos proporcionados.

### POST /CrearVideojuego - 400
- Simula error de "Solicitud inválida" cuando los datos de creación son incorrectos.

### PUT /ActualizarVideojuego
- Actualiza completamente los datos de un videojuego existente.

### PATCH /ActualizarParcialmenteVideojuego
- Actualiza parcialmente los datos de un videojuego.

### DELETE /EliminarVideojuego
- Elimina un videojuego específico de la base de datos.

