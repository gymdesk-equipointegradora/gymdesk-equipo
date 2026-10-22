# Casos de prueba: Control de acceso

Ejemplo para que QA continúe con los demás módulos.

- **Versión probada:** 1.14.0
- **Probó:** (pendiente)
- **Fecha:** (pendiente)

| ID | Qué se prueba | Pasos | Resultado esperado | Resultado obtenido | Estado |
|---|---|---|---|---|---|
| ACC-01 | Entrada con membresía vigente | 1. Abrir Acceso. 2. Escanear el código de un socio vigente. | Acceso concedido en verde con el nombre del socio | | Pendiente |
| ACC-02 | Entrada con membresía vencida | 1. Escanear el código de un socio vencido. | Acceso denegado en rojo con la fecha de vencimiento | | Pendiente |
| ACC-03 | Código que no existe | 1. Escribir un código inventado. | Mensaje de socio no encontrado; no se registra la entrada | | Pendiente |
| ACC-04 | Entrada por huella | 1. Poner el dedo registrado en el lector. | Identifica al socio en menos de 3 segundos | | Pendiente |
| ACC-05 | Huella no registrada | 1. Poner un dedo no registrado. | No concede el acceso a un desconocido | | Pendiente |
| ACC-06 | Registro en el historial | 1. Hacer una entrada. 2. Revisar la lista de accesos. | La entrada aparece con fecha y hora | | Pendiente |
