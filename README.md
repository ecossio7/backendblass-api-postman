# Colección API: Gestión de Participantes y Videojuegos

Esta colección agrupa los endpoints de la API para la gestión de participantes y videojuegos, además del módulo de autenticación.

## Funcionalidades principales que se trabajaron en Postman

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

## Endpoints de ejemplo autenticacion

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
