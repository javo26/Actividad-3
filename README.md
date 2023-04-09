# Simulación de un API

### Instrucciones:

En esta semana vamos a simular cómo funciona un API. 

Los APIs son interfaces, es decir son un conjunto de funciones y protocolos que nos permite interactuar con una aplicación. 

Vamos a simular un API meteorológico que funcionara de la siguiente manera:

    - Habrá dos elementos que el usuario puede consultar 

En el primero el usuario tendrá un elemento de input tipo date, en el cual puede seleccionar una fecha, luego habrá un botón el cual servirá para enviar la solicitud 

Una vez que la solicitud regrese se mostrará la fecha que fue enviada, el clima y la temperatura, se mostrará solamente el clima de la mañana de ese día. 

En el segundo se debe realizar la consulta para el día de hoy, en este caso se mostrará el clima de la mañana, tarde y noche. Puede realizarlo con un botón separado, o validar la consulta de la fecha al hacer clic en el botón que envía las solicitudes. 

Los estados de clima y la temperatura la generarán de manera aleatoria cada vez que se realice una consulta, puede usar la función random de JS

Para la entrega su programa debe de cumplir con las siguientes especificaciones:

Existirán 3 climas posibles:

    - Despejado 
    - Nublado  
    - Lluvioso

La temperatura puede variar desde 5 grados Celsius hasta 30 grados Celsius:

    - Las llamadas a nuestro API debe de ser por medio de llamadas asincrónicas
    - Las llamadas van a simular una llamada de red, así que agregue un tiempo de espera con ayuda 
      de la función setTimeout, esta es una función que usa Callbacks
    - Esta actividad se puede realizar con JS para un navegador web, no es necesario utilizar 
      electron 
    - Debe mostrar en pantalla la fecha y los elementos solicitados. 
    - A la hora de crear una solicitud nueva se deben de borrar los datos de la solicitud anterior 
      de la pantalla

