PROTOCOLO HTTP
El protocolo HTTP permite la tranferencia de datos en la web.

VERBOS HTTP
Son 4 verbos que nos indicará que se desea hacer con un recurso:

1) Verbo GET: este verbo permite recuperar datos solicitados de la web.
2) Verbo POST: este verbo nos permite enviar datos para que puedan ser procesados y estos datos 
               pueden ser procesados y darnos una respuesta verdadera ó puede ser una respuesta de error.
               tambien con este metodo se puede crear nuevo recurso y actualizar un recurso existente.
3) Verbo PUT: permite actualizar información existente en un recurso.
4) Verbo DELETE: Permite eliminar un recurso en especifico.

CABECERAS
permite enviar información adicional con una petición ó respuesta, como por ejemplo la peticón de un token


CODIGOS DE RESPUESTA
los codigos de respuesta son numeros de 3 digitos que nos indica que sucedio con la petición que se realizó

1) Codigo 1xx : Son codigos informativos, para indicar que la peticion fue recibida y se esta procesando.

2) Codigo 2xx : Son codigos de respuesta correcta, para indicar que la petición fue procesado de manera correcta

3) Codigo 3xx : Son codigos de redirección para indicar al usuario que debe realizar más acciones para su petición

4) Codigo 4xx : Son codigos de error, causados por el cliente. para indicar que algo se realizó mal

5) Codigo 5xx : Son codigos de error, causados por el servidor, para indicar que el proceso de petición fue erronea
                por fallo del servidor.