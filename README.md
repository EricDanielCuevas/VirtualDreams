# VirtualDreams
## trabajo practico consultor salesforce
## Evaluación Práctica


#### Punto 2

1- 	Un servidor HTTP es un software informático 
	que se encarga de procesar las aplicaciones del lado del servidor.
	Gestionando las conexiones, el ingreso de peticiones 
	y dando respuesta al cliente.

2-	Los verbos HTTP son los distintos tipos de peticiones que existen 
	y que podemos hacer hacia el mismo servidor.
	Los más conocidos son GET POST PUT DELETE Y OPTIONS.

3-	En una comunicación HTTP el request es la peticion realizada del lado del cliente,
	response es la respuesta a esa peticion realizada del lado del servidor 
	Y Los headers son la parte central de estos. Los headers sirven para transmitir información 
	acerca del navegador del cliente, de la página solicitada y del servidor.
 
4-	Es la parte de una URL que interactúa con la base de datos del servidor,
	esta contiene parámetros y datos que se envian 
	para efectuar consultas ,inserciones y actualizaciones.

5-	El response code indica si se ha completado satisfactoriamente o no un request. 
	Las respuestas se agrupan en cinco clases:

	Respuestas informativas (100–199),
	Respuestas satisfactorias (200–299),
	Redirecciones (300–399),
	Errores de los clientes (400–499),
	Errores de los servidores (500–599).

6-	La diferencia entre los métodos get y post radica en la forma de enviar los datos a la página cuando se hace submit en un formulario.
	Mientras que el método GET envía los datos usando la URL, el método POST los envía de forma que no podemos verlos en el body.

7-	Cuando accedemos a una pagina el navegador utiliza el verbo http GET.

8-	Las estructuras JSON y XML se utilizan para la transferencia de datos entre cliente y servidor web.
	un ejemplo de estructura JSON sería :
	
	{
       		"direccion" : 
                         {
                            "calle":"San Juan",
                            "altura":2501, 
                            "ciudad":"CABA"
                         };
	}

	mientras que XML sería: 
	
	<direccion>
    		<calle>San Juan</calle> <altura>2501</altura> <ciudad>CABA</ciudad>
  	</direccion>

9-	SOAP es un tipo de web service estandarizado que utiliza xml para el intercambio de datos,
	trabajando con el protocolo de comunicación http.

10- 	La arquitectura REST Full también bajo el protocolo de comunicación http,
	utiliza además de  xml archivos de tipo JSON para el intercambio de datos entre cliente - servidor.
	tambien tenemos a disposición métodos para poder operar en el servicio. GET, POST, PUT,  DELETE.

11-	Los headers en un request son valores que viajan hacia el servidor para proporcionar informacion adicional acerca de ese request que se esta enviando.
	Cada header esta compuesto por una clave y un valor.
	La key Content-Type es para aclarar de que tipo/formato es el contenido que envío en mi solicitud o respuesta.


#### Punto 3

La diferencia se encuenta en el ultimo registro del body , ya que en el punto 1 me traía los registros existentes ![punto 1](https://github.com/EricDanielCuevas/VirtualDreams/blob/f39f48161d68a83830d004d9f4c70573cc1ecdf6/punto%203%20item%201.PNG?raw=true)  , y en el punto 3 además me trae el registro que se generó con mi peticion realizada por POST en el punto 2. ![punto 3](https://github.com/EricDanielCuevas/VirtualDreams/blob/main/punto%203%20item%203.PNG)  .En el punto 2 es cuando realizo el POST para agregar el registro y obtener un nuevo ID lo cual puede observarse en la siguiente imagen ![punto 2](https://github.com/EricDanielCuevas/VirtualDreams/blob/main/punto%203%20item%202%20con%20id.PNG) .	

#### Punto 4
https://trailblazer.me/id/ericcuevas
