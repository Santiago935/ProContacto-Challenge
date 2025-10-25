# ProContacto-Challenge

## Ejercicio 2

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
  
## Ejercicio 3 
  
Se adjuntan las pruebas del ejercicio 3, del cual consistia en usar GET y POST con el software PROMAN para la pagina ProContacto  
  
Antes del POST  
![Imagen1](Imagenes/imagen1.png)  
POST  
![Imagen2](Imagenes/imagen2.png)  
Despues del POST  
![Imagen3](Imagenes/imagen3.png)  

**¿Qué diferencias se observan entre las llamadas el punto 1 y 3?**  
Tras hacer el POST, se subio mi nombre y email a la pagina.


## Ejercicio 4
Link al perfil de Trailhead dónde hice los modulos pedidos:
[Mi perfil de Trailhead](https://www.salesforce.com/trailblazer/e3a3wigv2bg9dt5063)

## Ejercicio 5

**1. Lead (Cliente Potencial):**
Es un cliente potencial a quien le ha interesado algún producto o servicio de tu empresa. Almacena datos como el nombre, la **compañía**, el email y el teléfono.

**2. Account (Cuenta):**
Es la empresa o entidad con la que tienes ya una relación de negocio (o potencial). Se almacenan datos como el nombre, la web, etc.

**3. Contact (Contacto):**
Es un comprador o persona individual de tu empresa, siempre asociado a una **Account**. Se guardan datos más personales como el nombre de cuenta al que pertenece, teléfono, fecha de nacimiento, correo, etc.

**4. Opportunity (Oportunidad):**
Es una venta en curso. Contiene datos como el nombre, la fecha de cierre prevista de la venta y el estado (etapa).

**5. Product (Producto):**
Es el producto o servicio que ofrece la empresa. Tiene datos como el nombre del producto, el código, la descripción y si está activo o no.

**6. PriceBook (Lista de Precios):**
Es donde se almacenan los precios por producto, permitiendo tener múltiples listas de precios para diferentes segmentos.

**7. Quote (Presupuesto/Cotización):**
Es donde se almacena el precio de los productos hacia un cliente específico, a menudo vinculado a una **Opportunity**.

**8. Asset (Activo):**
Es el producto que ya fue vendido o instalado al cliente y que está en uso. Contiene datos como el nombre del producto, la **Account** a la que pertenece y el estado del activo.

**9. Case (Caso):**
Es el reclamo, pregunta o solicitud de soporte de un cliente. Contiene el número de reporte, el estado, prioridad, etc.

**10. Article (Artículo):**
Contiene la solución a un problema o información de soporte, usado en la Base de Conocimiento (Knowledge Base). Tiene datos como el título, un resumen, etc.

![Imagen3](Imagenes/Diagrama_SaleForce.png)  

## Ejercicio 6
  
---

### Soluciones de Salesforce

**A. ¿Qué es Salesforce?**  
Salesforce es una plataforma de gestión de empresas en la nube.

**B. ¿Qué es Sales Cloud?**  
Un software que automatiza el ciclo de ventas para ayudar a las empresas a vender sus productos.

**C. ¿Qué es Service Cloud?**  
Es una plataforma de servicio de atención al cliente que ayuda a empresas a gestionar y resolver consultas de índole soporte técnico.

**D. ¿Qué es Health Cloud?**  
Es una plataforma idéntica a Service Cloud pero enfocada en el sector de salud (o sea, trabajando con datos clínicos y no clínicos de un paciente).

**E. ¿Qué es Marketing Cloud?**  
Es una plataforma idéntica a las dos anteriores, pero esta vez enfocada en el mundo del marketing, trabajando con análisis y datos de campañas, redes, etc.

---

### Funcionalidades de Salesforce

**A. ¿Qué es un RecordType?**  
Es una herramienta para crear registros de un objeto.

**B. ¿Qué es un ReportType?**  
Representa los metadatos asociados a un tipo de informe personalizado.

**C. ¿Qué es un Page Layout?**  
Una herramienta para controlar la disposición y organización de las características de los objetos.

**D. ¿Qué es un Compact Layout?**  
Es una opción para mostrar los campos clave de un registro.

**E. ¿Qué es un Perfil?**  
Un conjunto de configuraciones y permisos que controla el acceso de un usuario a objetos y datos.

**F. ¿Qué es un Rol?**  
Un subconjunto de usuarios definidos del cual tienen acceso a determinados objetos (Nota: El rol en Salesforce principalmente define la jerarquía de datos a los que un usuario puede acceder, afectando el compartimiento de datos).

**G. ¿Qué es un Validation Rule?**  
Una regla que valida los datos ingresados antes de guardarlos.

**H. ¿Qué diferencia hay entre una relación Master Detail y Lookup?**  
En Master Detail un objeto hijo no puede sobrevivir sin el padre. En Lookup el objeto hijo puede sobrevivir sin el padre.

**I. ¿Qué es un Sandbox?**  
Es una copia de un entorno de Salesforce para hacer pruebas de desarrollo.

**J. ¿Qué es un ChangeSet?**  
Es una herramienta de Salesforce para migrar metadatos de un *sandbox* a otro (o a producción).

**K. ¿Para qué sirve el Import Wizard de Salesforce?**  
Sirve para importar datos en masa.

**L. ¿Para qué sirve la funcionalidad Web to Lead?**  
Para generar un formulario web con la finalidad de crear *Leads*.

**M. ¿Para qué sirve la funcionalidad Web to Case?**  
Para generar un formulario web, pero con la finalidad de crear un *Case* (Caso).

**N. ¿Para qué sirve la funcionalidad Omnichannel?**  
Asigna *Cases* y *Leads* (o elementos de trabajo) a un agente para agilizar el trabajo.

**O. ¿Para qué sirve la funcionalidad Chatter?**  
Un foro de usuarios interno de Salesforce.

---
### Conceptos Generales  
  
**A. ¿Qué significa SaaS?**   
Significa *Software as a Service* (Software como Servicio), del cual es un modelo donde se alquila el uso de un determinado software.

**B. ¿Salesforce es SaaS?**   
Sí.

**C. ¿Qué significa que una solución sea Cloud?**   
Significa que la solución se ejecuta en algún servidor externo a la empresa (en la nube).

**D. ¿Qué significa que una solución sea On-Premise?**   
Que la solución se ejecuta en algún servidor interno de la empresa.

**E. ¿Qué es un pipeline de ventas?**   
Un proceso de ventas del cual se divide en etapas.

**F. ¿Qué es un funnel de ventas?**   
El número de clientes por etapa de venta (o una representación visual del proceso de conversión).

**G. ¿Qué significa Customer Experience?**   
Es la percepción total de un cliente que se crea a partir de sus interacciones.

**H. ¿Qué significa omnicanalidad?**  
Habilidad de un negocio para interactuar con clientes de manera integrada a través de múltiples canales.

**I. ¿Qué significa que un negocio sea B2B? ¿Qué significa que un negocio sea B2C? ¿Qué es un KPI?**   
B2B significa venta entre negocios. B2C significa venta a un cliente (consumidor), y KPI es una métrica clave de rendimiento (*Key Performance Indicator*) para medir el rendimiento (ej. de una venta).

**J. ¿Qué es una API y en qué se diferencia de una Rest API?**   
Una API es una interfaz que interactúa entre dos *softwares* o servidores distintos. La diferencia con REST API es que este último se especializa en el uso de HTTP y JSON con el fin de especializarse con navegadores web (Nota: REST API es un tipo de arquitectura API que usa protocolos como HTTP).

**K. ¿Qué es un Proceso Batch?**  
Proceso que permite ejecutar grandes volúmenes de datos.

**L. ¿Qué es Kanban?**  
Un método visual (etiquetas) para la gestión del flujo de trabajo y el estado de una tarea (*Pendiente, Terminado*, etc.).

**M. ¿Qué es un ERP?**  
Un ERP es un software que integra todas las áreas de una empresa (*Enterprise Resource Planning*).

**N. ¿Salesforce es un ERP?**  
No, ya que solo se enfoca en la relación de una empresa con sus clientes (CRM).

