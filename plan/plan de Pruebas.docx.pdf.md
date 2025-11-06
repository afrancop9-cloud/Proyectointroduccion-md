# Criterio de aceptación

· El usuario puede registrarse, iniciar sesión y cerrar sesión sin errores

· Las operaciones CRUD funcionan correctamente

· Las citas se muestran en lista y calendario

· Los recordatorios se activan según configuración

· Las acciones responden en menos de 2 segundos.


| ID | Tipo | Asociado | Datos de<br>entrada | Resultado<br>esperado | Resultado<br>obtenido |
| --- | --- | --- | --- | --- | --- |
| 1. | Unitario | Requerimiento Funcional | Email valido | usuario creado | Correcto |
| 2. | Unitario | Requerimiento funcional | Email invalido | Rechazado | Correcto |
| 3, | Unitario | Requerimiento funcional | Credenciales<br>validas | Acceso | Correcto |
| 4. | Unitario | Requerimiento funcional | Cita válida | Cita creada | Correcto |
| 5. | Validación | Requerimiento no funcional | Medir tiempo<br>de respuesta | 2 segundos | Correcto |
| 6. | Validación | Requerimiento funcional | Cerrar sesión | Sesión<br>terminada | Correcto |


