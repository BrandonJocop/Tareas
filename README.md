Para la solución a la actividad de la semana 2 me basé más que nada
en buscar la forma de que se mostrara el mensaje correcto según el
número del mes.
Inicialmente lo realizé de la siguiente forma:

switch(mes){
	case "12","1","2":
		console.log("Es invierno")
		break;

Pero al hacerlo de esta forma, ocurría el error de que únicamente
detectaba un número de los tres necesarios. Fue mediante una 
búsqueda rápida que me dí cuenta de que necesitaba arreglarlo de
la siguiente manera:

switch(mes){
	case "12":
	case "1":
	case "2":
		alert("¡Es Invierno!")

Con esto, conseguía que mostrara la alerta requerida según el número
dado por el usuario.