### Referencia: https://developer.twitter.com/en/support/twitter-api/error-troubleshooting#http-status-codes

##### 200 - Ok (Solicitud exitosa)
| CODE | NOMBRE               | MENSAJE (ES-US)    |                   DESCRIPCIÓN                               |
| ---- |:--------------------|:------------------   |:------------------------------------------------------------|
| 100  | SuccessfulRequest    | Successful request. | Solicitudes exitosas que no sean creaciones y eliminaciones |
| 102  | ObjectUpdated	      | Object updated. | Actualización exitosa de un objeto. |

##### 201 - Created (Creado)
|CODE|NOMBRE|MENSAJE (ES-US) |DESCRIPCIÓN |
| ---- |:--------------------|:------------------   |:------------------------------------------------------------|
|101 |ObjectCreated	|Object created.|Creación exitosa de un objeto.|
|103|ObjectDeleted|Object deleted.|Eliminación exitosa de un objeto|

##### 204 - No Content (Sin contenido)
|CODE|NOMBRE|MENSAJE (EN-US)|DESCRIPCIÓN|
| ---- |:--------------------|:------------------   |:------------------------------------------------------------|
|103|ObjectDeleted|Object deleted.|Eliminación exitosa de un objeto|

Errores de cliente
---------------------
##### 400 - Bad request (Solicitud incorrecta)
|CODE|NOMBRE|MENSAJE (EN-US)|DESCRIPCIÓN|
| ---- |:--------------------|:------------------   |:------------------------------------------------------------|
|111|InvalidRequest|Request with invalid data.|Los datos de la solicitud no son validos.|
|112|Required|Required.|Un atributo o elemento requerido no ha sido especificado.|
|113|InvalidValue|Invalid value.|Un atributo o elemento especificado contiene datos no válidos.|
|114|InvalidFormat|Invalid format.|Un valor de atributo o elemento especificado no cumple con el formato esperado.|
|115|InvalidLenght|Invalid lenght.|Un valor de cadena no cumple la restricción de longitud de un atributo.|
|116|InvalidRange|Invalid range.|El intervalo de valores no es válido|
|117|InvalidDateRange|Invalid date range.|El intervalo de fechas no es válido|

##### 401 - Unauthorized (No autorizado)
|CODE|NOMBRE|MENSAJE (EN-US)|DESCRIPCIÓN|
| ---- |:--------------------|:------------------   |:------------------------------------------------------------|
|131|AuthenticationFailure|Authentication failure.|Autenticación fallida debido a credenciales de autenticación no válidas.|

##### 403 - Forbidden (Prohibido)
|CODE|NOMBRE|MENSAJE (EN-US)|DESCRIPCIÓN|
| ---- |:--------------------|:------------------   |:------------------------------------------------------------|
|141|NotAuthorized|Not authorized.|El usuario actual no tiene permisos para realizar la acción solicitada.|
|142|InvalidAccessToken|Invalid access token.|El token de acceso proporcionado no es válido.|
|143|ExpiredAccessToken|Expired access token.|La validez del token de acceso provisto ha expirado.|
|144|InvalidRefreshToken|Invalid refresh token.|El token de refresh proporcionado no es válido.|
|145|InvalidEmailToken|Invalid email token.|El token para validación de enlace de email no es válido.|
|146|ExpiredEmailToken|Expired email token.|La validez del token para validación de email provisto ha expirado.|

##### 404 - Not found (No encontrado)
|CODE|NOMBRE|MENSAJE (EN-US)|DESCRIPCIÓN|
| ---- |:--------------------|:------------------   |:------------------------------------------------------------|
|151|ResourceNotFound|Resource not found.|Se refiere a una entidad o elemento que no se pudo encontrar.|
|152|UserNotFound|User not found.|Se refiere a que no se encuentra un usuario.|

##### 405 - Method not allowed (Método no permitido)
|CODE|NOMBRE|MENSAJE (EN-US)|DESCRIPCIÓN|
| ---- |:--------------------|:------------------   |:------------------------------------------------------------|
|156|MethodNotAllowed|Method not allowed.|Una petición fue hecha a una URI utilizando un método de solicitud no soportado por dicha URI|

##### 409 - Conflict (Conflicto)
|CODE|NOMBRE|MENSAJE (EN-US)|DESCRIPCIÓN|
| ---- |:--------------------|:------------------   |:------------------------------------------------------------|
|161|ResourceAlreadyExists|The resource already exists.|Se intentó crear un objeto que ya existe.|


Errores de servidor
---------------------
##### 500 - Internal server error (Error interno del servidor)
|CODE|NOMBRE|MENSAJE (EN-US)|DESCRIPCIÓN|
| ---- |:--------------------|:------------------   |:------------------------------------------------------------|
|166|InternalServerError|Internal server error.|La solicitud ha fallado debido a un error interno en el servidor.|
|167|DatabaseError|Database error.|La solicitud ha fallado debido a un error de base de datos.|
|168|NetworkError|Network error.|La solicitud ha fallado debido a un error de la red.|
|169|OperationTimedOut|Operation timed out.|La operación no pudo completarse dentro del tiempo permitido.|
