# Casos de Prueba - AduanaFlow

| ID | Descripción | Datos de entrada | Salida esperada | Evidencia |
|---|---|---|---|---|
| CP-01 | Validar registro de usuario | RUT, nombre, apellido, correo y contraseña válidos | Usuario registrado correctamente y mensaje de confirmación | Captura de pantalla del registro exitoso |
| CP-02 | Validar inicio de sesión correcto | Usuario/RUT y contraseña válidos | Acceso al dashboard correspondiente al rol | Captura del dashboard |
| CP-03 | Validar inicio de sesión incorrecto | Contraseña incorrecta | Mensaje de error y acceso denegado | Captura del mensaje de error |
| CP-04 | Validar carga de documento permitido | Archivo PDF o JPG válido | Documento cargado y asociado a un trámite | Captura de carga exitosa |
| CP-05 | Validar carga de archivo inválido | Archivo con formato no permitido | Mensaje indicando formato no válido | Captura de validación |
| CP-06 | Consultar estado de trámite | ID de trámite existente | Estado visible del trámite: pendiente, en revisión, aprobado o rechazado | Captura de consulta |
| CP-07 | Validar notificación de cambio de estado | Trámite actualizado por funcionario | Notificación visual para el usuario | Captura de notificación |
| CP-08 | Validar generación de reportes | Rango de fechas | Reporte con métricas del sistema | Captura de pantalla del reporte |
| CP-09 | Gestionar usuario como administrador | Búsqueda por RUT | Usuario encontrado y opciones de gestión visibles | Captura del panel administrador |
