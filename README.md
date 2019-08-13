# practica Nº 1
## respuesta 1
### Un Sistema de Información Empresarial es un sistema impacto muy 
### importante en el funcionamiento de la organización o negocio y
 ### cuya falla traería graves consecuencias. Normalmente que ofrece
  ### alta calidad de servicio, gestiona con grandes volúmenes de 
  ### datos, disponible de forma continua y es capaz de soportar
   ### cualquier organización grande.
## respuesta 2
- acceso a la base de datos de datos, usualmente a bases de datos.
- operaciones transaccionales, cumple con las propiedades.
- Escalables, permiten escalabilidad vertical y horizontal.
- Disponibles, idealmente prestan servicios de forma continua.
- Seguras, no todos los usuarios acceden con la misma.
- Permiten integración con otras tecnologías.
- Arquitectura multicapa.
## respuesta 3
### ...
## respuesta 4
- Escalabilidad vertical, que se refiere a modernización de componentes existentes
- Escalabilidad horizontal, que se refiere a aumentar el número de componentes.
## respuesta 5
### Servidor web es una computadora que formando red provee ###servicios a otras computadoras denominadas clientes.

### Un servidor de aplicaciones es un dispositivo que proporcionan ###servicios de aplicación a las computadoras cliente.
### Un servidor de aplicaciones generalmente gestiona la mayor ###parte de las funciones de la lógica de negocio y acceso a los 
### datos de la aplicación.
## respuesta 6
![imagen](http://2.bp.blogspot.com/_jUCZth_DkjU/TID-jK9rWcI/AAAAAAAAAAQ/3JNIssF_KeQ/s1600/protocolo.png)
## respuesta 7
- método http protocolo empleado para la transferencia de recursos que componen una web ( la acción a realizar).
- la página para acceder (a url).
-parámetros de formulario (como argumento a un método).
## respuesta 8
- un código de estado (para saber si la solicitud fue exitosa ).
- tipo de contenido.
- el contenido.
## respuesta 9
![imagen](https://image.slidesharecdn.com/jatunandjavaee-110905104600-phpapp02/95/desarrollo-de-aplicaciones-empresariales-con-java-ee-4-728.jpg?cb=1316098712)
## respuesta 10

- Método doDelete: realiza la operación DELETE de http. La operación delete permite al cliente una petición para borrar un URI del servidor.
-  Método doGet: realiza la operación GET de http.
-  Método doHead: realiza la operación POST de http. Por defecto está realizado por la implementación de la operación GET, pero no devuelve datos acerca del cliente, sino tan solo las cabeceras.
-  Método doOptions: realiza la operación OPTIONS de http. La implementación por defecto determina qué opciones de http se soportan. Este método no necesita ser sobrescrito al no ser que el servlet implemente nuevos métodos que no son soportados por el protocolo http.
-  Método doPost: realiza la operación POST de http. Sirve para leer datos desde el request (como parámetros), poner las cabeceras en el response y escribir datos en response usando el output stream. Es decir, Post solamente estará disponible para el tratamiento de formularios.
-  Método doPut: realiza la operación PUT de http. Consiste en enviar un fichero a través del FTP (file transport protocol).
-  Método doTrace: realiza la operación TRACE de http. Devuelve un mensaje que contiene todas las cabeceras enviadas con el trace request.
-  Método getLastModified: Devuelve el tiempo que estuvo el request sin modificarse.
La clase HttpServletRequest:
  
- getAuthTipe(): Devuelve el esquema auténtico del request, o null si no hay.
-  getCookies(): Devuelve un array de cookies.
-  getDateHeader(String): Devuelve el valor del campo de tipo fecha de la cabecera del response.
-  getHeader(String): Devuelve el valor del campo indicado de la cabecera.
-  getHeaderNames(): Devuelve los nombres de las cabeceras.
-  getIntHeader(String): Devuelve un entero correspondiente al campo de la cabecera introducido.
-  getMethod(): Devuelve el método con el que se está haciendo el request.
-  getPathInfo(): Devuelve información a cerca del path del servlet.
-  getPathTranslated(): Devuelve información extra a cerca de un path que ha sido trasladado.
-  getQueryString(): Devuelve la sentencia de consulta del URI.
-  getRemoteUser(): Devuelve el nombre del usuario que hace el request.
-  getRequestSessionId(): Devuelve el identificador de la sesión en este request.
-  getRequestURI(): Devuelve el URI del request.
-  getServletPath(): Devuelve el servlet que ha sido invocado.
-  getSession(): Devuelve o crea la sesión asociada al request.
-  getSession(boolean): Devuelve o crea la sesión asociada al request.
-  isRequestedSessionIdFromCookie(): Devuelve true si el identificador para el request viene de un cookie.
-  isRequestedSessionIdFromURL(): Devuelve true si el identificador para el request es parte del URL.
-  isRequestedSessionIdValid(): Devuelve true si el identificador para el request es válido para esta sesión.
  La clase HttpServletResponse:
Sus métodos son:
-	addCookie(Cookie): Añade un cookie al response actual.
-	containsHeader(String): devuelve true si el nombre del campo que hemos pasado está en el mensaje de cabecera.
-	encodedRedirectURL(String): codifica el URL para usarlo en el método sendRedirect.
-	encodeURL(String): Codifica el URL incluyendo el identificador de la sesión.
-	sendError(int): Envía un error al cliente usando el código de error.
-	sendError(int, String): Envía un error al cliente usando el código de error y el mensaje.
-	sendRedirect(String): reenvía un response al URL indicado o al cliente.
-	setDateHeader(String, long): Añade el campo indicado a la cabecera del response con un valor de tipo fecha.
-	setHeader(String, String): Añade el campo indicado a la cabecera del response con un valor de tipo String. Usaremos este método para forzar al navegador a cargar la página HTML desde el servidor en lugar de desde la caché.
-	setIntHeader(String, int): Añade el campo indicado a la cabecera del response con un valor de tipo entero.
-	setStatus(int): pone el código de estado para el response.


