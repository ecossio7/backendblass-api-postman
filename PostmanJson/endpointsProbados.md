## 🚀 Endpoints Probados y Documentados

![image](https://github.com/user-attachments/assets/83cf93b1-68b4-4249-838d-029abe4cda3d)

### Auth

#### <span style="color:#22863a;">GET</span> /login
- Autentica usuarios y proporciona un token de acceso para sesiones autorizadas.

### Participantes

#### <span style="color:#22863a;">GET</span> /ObtenerTodosParticipantes
- Obtiene la lista completa de participantes registrados.

#### <span style="color:#22863a;">GET</span> /BuscarParticipantes
- Busca participantes según criterios específicos (nombre, estado, etc.).

#### <span style="color:#22863a;">GET</span> /OrdenarParticipantes
- Devuelve participantes ordenados según un campo específico (nombre, fecha, etc.).

#### <span style="color:#22863a;">GET</span> /FiltrarParticipantes
- Filtra participantes según parámetros personalizados (estado, rango de edad, etc.).

#### <span style="color:#22863a;">GET</span> /ObtenerParticipante
- Obtiene los detalles de un participante específico por ID.

#### <span style="color:#22863a;">GET</span> /ObtenerParticipante - 404
- Simula error de "No encontrado" cuando el participante no existe.

#### <span style="color:#22863a;">GET</span> /ObtenerParticipante - 401
- Simula error de "No autorizado" para acceso sin permisos.

#### <span style="color:#FFD700;">POST</span> /CrearParticipante
- Crea un nuevo participante con los datos proporcionados.

#### <span style="color:#FFD700;">POST</span> /CrearParticipante - 400
- Simula error de "Solicitud inválida" cuando los datos de creación son incorrectos.

#### <span style="color:#005cc5;">PUT</span> /ActualizarParticipante
- Actualiza completamente los datos de un participante existente.

#### <span style="color:#9370DB;">PATCH</span> /ActualizarParcialmenteParticipante
- Actualiza parcialmente los datos de un participante.

#### <span style="color:#8B0000;">DELETE</span> /EliminarParticipante
- Elimina un participante específico de la base de datos.

### Videojuegos

![image](https://github.com/user-attachments/assets/297f1551-14be-479c-bbca-1704dac8e492)

#### <span style="color:#22863a;">GET</span> /ObtenerTodosVideojuegos
- Obtiene la lista completa de videojuegos disponibles.

#### <span style="color:#22863a;">GET</span> /BuscarVideojuegos
