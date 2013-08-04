curso-google-map-msp
====================

Curso google map MSP
Estos son los recursos relevantes para el curso que seran util para el aprendizaje de Google Maps



Recursos:

Documentacion API
https://developers.google.com/maps/documentation/javascript/reference


Static Maps
https://developers.google.com/maps/documentation/staticmaps/?hl=es


Code Project
http://www.codeproject.com/articles/291499/google-maps-api-v3-for-asp-net


Jquery;
http://code.jquery.com/jquery-1.10.2.min.js


Geocomplete 
http://ubilabs.github.io/geocomplete/


Directions Services
https://developers.google.com/maps/documentation/javascript/services?csw=1#Directions


Notas importantes de Google Static Maps
Clave de API

El API de Google Static Maps utiliza una clave de API para identificar tu aplicación. Las claves de API se administran a través de la consola de las API de Google. Para activar el API de Google Static Maps y crear una clave, sigue estos pasos:

Accede a la página de la consola de las API (https://code.google.com/apis/console) e inicia sesión en tu cuenta de Google.
Haz clic en el enlace de servicios en el menú de la izquierda y, a continuación, activa el servicio del API de Google Static Maps.
Una vez que el servicio se haya activado, tu clave de API estará disponible en la sección de acceso del API sencillo de la página de acceso del API. Las aplicaciones del API de Google Static Maps utilizan la clave para aplicaciones del navegador.
De forma predeterminada, una clave se puede utilizar en cualquier sitio. Te recomendamos encarecidamente que restrinjas el uso de la clave a los dominios que administres. Para especificar los dominios que pueden utilizar la clave de API, haz clic en el enlace para Editar referencias permitidas... de la consola de las API.

Si incluyes una clave de API en tu solicitud, podrás realizar un seguimiento del uso en la consola de las API y adquirir límites adicionales si fuera necesario. Para especificar una clave en tu solicitud, inclúyela como valor del parámetro key.

http://maps.googleapis.com/maps/api/staticmap?center=New+York,NY&zoom=13&size=600x300&key=API_console_key
Ten en cuenta que no es obligatorio utilizar una clave, pero sí recomendable. Los ejemplos que aparecen en este documento no incluyen el parámetro key, por lo que funcionarán para todos los usuarios que copien y peguen el código.

Límites de uso

Los clientes del API de Google Maps for Business cuentan con límites distintos a los que se indican a continuación. Una solicitud de mapa estático se considera una "visita de página" a efectos de la administración de límites del API de Google Maps for Business y se aplica al número total de visitas a la página adquiridas con la licencia del API de Google Maps for Business.

El API de Google Static Maps cuenta con los límites de uso que se indican a continuación:

25.000 solicitudes gratuitas diarias de mapas estáticos por aplicación
Las solicitudes de imágenes adicionales se pueden adquirir por aplicación y se les aplica la tarifa que se indica en las preguntas frecuentes. Los límites adicionales se adquieren a través de la consola de las API y es necesario utilizar una clave de API.
