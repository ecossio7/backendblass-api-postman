## Endpoints Probadas

![image](https://github.com/user-attachments/assets/83cf93b1-68b4-4249-838d-029abe4cda3d)

### Auth

#### POST /login
- Autentica usuarios y proporciona un token de acceso para sesiones autorizadas.

### Participantes

#### GET /ObtenerTodosParticipantes
- Obtiene la lista completa de participantes registrados.

#### GET /BuscarParticipantes
- Busca participantes según criterios específicos (nombre, estado, etc.).

#### GET /OrdenarParticipantes
- Devuelve participantes ordenados según un campo específico (nombre, fecha, etc.).

#### GET /FiltrarParticipantes
- Filtra participantes según parámetros personalizados (estado, rango de edad, etc.).

#### GET /ObtenerParticipante
- Obtiene los detalles de un participante específico por ID.

#### GET /ObtenerParticipante - 404
- Simula error de "No encontrado" cuando el participante no existe.

#### GET /ObtenerParticipante - 401
- Simula error de "No autorizado" para acceso sin permisos.

#### POST /CrearParticipante
- Crea un nuevo participante con los datos proporcionados.

#### POST /CrearParticipante - 400
- Simula error de "Solicitud inválida" cuando los datos de creación son incorrectos.

#### PUT /ActualizarParticipante
- Actualiza completamente los datos de un participante existente.

#### PATCH /ActualizarParcialmenteParticipante
- Actualiza parcialmente los datos de un participante.

#### DELETE /EliminarParticipante
- Elimina un participante específico de la base de datos.

### Videojuegos

![image](https://github.com/user-attachments/assets/297f1551-14be-479c-bbca-1704dac8e492)

#### GET /ObtenerTodosVideojuegos
- Obtiene la lista completa de videojuegos disponibles.

#### GET /BuscarVideojuegos
- Busca videojuegos según criterios específicos (título, género, etc.).

#### GET /OrdenarVideojuegos
- Devuelve videojuegos ordenados según un campo específico (nombre, fecha de lanzamiento, etc.).

#### GET /FiltrarVideojuegos
- Filtra videojuegos según parámetros personalizados (género, plataforma, etc.).

#### GET /ObtenerVideojuego
- Obtiene los detalles de un videojuego específico por ID.

#### GET /ObtenerVideojuego - 404
- Simula error de "No encontrado" cuando el videojuego no existe.

#### GET /ObtenerVideojuego - 401
- Simula error de "No autorizado" para acceso sin permisos.

#### POST /CrearVideojuego
- Crea un nuevo videojuego con los datos proporcionados.

#### POST /CrearVideojuego - 400
- Simula error de "Solicitud inválida" cuando los datos de creación son incorrectos.

#### PUT /ActualizarVideojuego
- Actualiza completamente los datos de un videojuego existente.

#### PATCH /ActualizarParcialmenteVideojuego
- Actualiza parcialmente los datos de un videojuego.

#### DELETE /EliminarVideojuego
- Elimina un videojuego específico de la base de datos.

#### Enlace de la documentacion generaada desde postman
https://documenter.getpostman.com/view/29548111/2sB2qXn3yM
