# ProContacto-Challenge

## Protocolo HTTP

### 1. ¿Qué es un servidor HTTP?

Un servidor HTTP consiste en un software que recibe request y responde usando el contenido de un sitio web. Todo esto usando el protocolo HTTP, y siendo accedidos mediante URLs

### 2. ¿Qué son los verbos HTTP? Mencionar los más conocidos

Los verbos HTTP son metodos que el cliente puede realizar sobre un recurso del servidor. Algunos ejemplos de estos son:
→ GET que se usa para obtener datos del servidor.  
→ POST que se usa para crear un nuevo recurso en el servidor.  
→ PUT que reemplaza un recurso ya existente en el servidor.    
→ PATCH que modifica parcialmente un recurso.  
→ DELETE que elimina un recurso del servidor.  
→ HEAD que obtiene un header de algun recurso del servidor.  
→ OPTIONS que consulta los metodos disponibles respecto a un recurso del servidor.  


### 3. ¿Qué es un request y un response en una comunicación HTTP? ¿Qué son los headers?

Request es el mensaje que envia el cliente al servidor y response es la respuesta que da al servidor a dicho request. Los headers son metadatos que vienen en el mensaje (idioma, tipo de dato, etc)

### 4. ¿Qué es un queryString? (En el contexto de una url)

Son los parámetros incluidos en el URL. Estan formados con clave-valor, y comienzan con `?` y se separan con `&`.

### 5. ¿Qué es el responseCode? ¿Qué significado tiene los posibles valores devueltos?

Un responseCode es un codigo de respuesta que da HTTP a la solicitud. Se enumeran en cinco intervalos de valores:  
[100-199] son las respuestas de estandar informativa.  
[200-299] son respuestas que indican que la solicitud se ha completado correctamente.  
[300-399] indica que la respuesta fue redireccionada a un recurso externo.  
[400-499] indica que hubo un error por parte del cliente.  
[500-599] indica que hubo un error por parte del servidor.  

### 6. ¿Cómo se envía la data en un Get y cómo en un POST?

Usando GET los datos se envian en el mismo URL, mientras que en POST se envian los datos en la solicitud HTTP (en la parte del cuerpo del request).

### 7. ¿Qué verbo http utiliza el navegador cuando accedemos a una página?

Se usa el metodo GET.

### 8. Explicar brevemente qué son las estructuras de datos JSON y XML dando ejemplo de estructuras posibles.

Las estructuras JSON y XML son formas de organizar los datos. En JSON se usa un formato clave-valor. Osea, por cada etiqueta se rellena uno o varios valores. Por ejemplo:  

```json
{
  "name": "Santiago",
  "pasatiempos": ["leer", "videojuegos", "youtuber"]
}
```

En XML es una estructura mas echa para computadoras, poniendo valores entre etiquetas. Por ejemplo:  

```xml
<Name>Santiago</Name>
<Pasatiempos>
  <Pasatiempo>leer</Pasatiempo>
  <Pasatiempo>videojuegos</Pasatiempo>
</Pasatiempos>
```

### 9. Explicar brevemente el estándar SOAP

SOAP es un protocolo para intercambiar informacion entre un servidor WEB y cliente, estructurandose con formato XML. 

### 10. Explicar brevemente el estándar REST Full 

El estandar REST Full consiste en usar una APIREST para la comunicación entre el servidor web y el cliente, respetando los protocolos HTTP.

### 11. ¿Qué son los headers en un request? ¿Para qué se utiliza el key Content-type en un header?

Los headers del request son datos que acompañan a la solicitud del cliente hacia el servidor web. Por ejemplo autenticacion o el idioma. El content-type es lo que indica el tipo de dato que se esta enviando en header del request.
