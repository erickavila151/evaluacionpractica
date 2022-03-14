<p align="center">
  <img src="https://user-images.githubusercontent.com/69064746/158085652-2c35bd59-80ac-4ac1-92d8-b8f53a4613f4.jpg"/>
 </p>

## Ejercicio 1
### Instalación del ambiente
Visual Studio Code
<p align="center">
  <img src="https://user-images.githubusercontent.com/69064746/158078138-7df0fb2d-e269-4360-92fd-dc51646b4989.png" />
</p>

GitBash
<p align="center">
  <img src="https://user-images.githubusercontent.com/69064746/158078149-775abebd-fd0e-481d-bed0-3fa1798866f1.png"/>
</p>

---
## Ejercicio 2

1. **¿Qué es un servidor HTTP?**
- Un servidor HTTP es un sotfware que se encuentra del lado del servidor, donde se realiza una conexión directa con el cleinte (usuario) a través de su navegador web de forma bidireccional o unidireccional, dando respuestas visibles al cliente.
2. **¿Qué son los verbos HTTP? Menciona los más conocidos**
- Los métodos de petición o los **verbos HTTP** existen para hacer peticiones predeterminadas a un recurso determinado como por ejemplo:

| VERBO | DESCRIPCIÓN |
| ------ | ------ |
| GET | El método GET  solicita una representación de un recurso específico. Las peticiones que usan el método GET sólo deben recuperar datos. |
| HEAD | El método HEAD pide una respuesta idéntica a la de una petición GET, pero sin el cuerpo de la respuesta. |
| POST | El método POST se utiliza para enviar una entidad a un recurso en específico, causando a menudo un cambio en el estado o efectos secundarios en el servidor. |
| PUT | El modo PUT reemplaza todas las representaciones actuales del recurso de destino con la carga útil de la petición. 
| DELETE | El método DELETE borra un recurso en específico. |
| TRACE |El método TRACE  realiza una prueba de bucle de retorno de mensaje a lo largo de la ruta al recurso de destino. |

3. **¿Qué es un request y un response en una comunicación HTTP? ¿Qué son los headers?**
- Un **request** es el mensaje que se envía desde el cliente al servidor para solicitar un recurso, una **response** es el mensaje que envía el servidor al cliente tras haber recibido una petición o HTTP **request**. <br>
Los HTTP **headers** son la parte central de los HTTP requests y responses, y transmiten información acerca del navegador del cliente, de la página solicitada, del servidor, etc. Aquí algunos ejemplos:

<p align = "center">
  <img src= https://user-images.githubusercontent.com/69064746/158096428-75a26ed6-87b0-49d1-9797-36033e25f8cc.png />
</p>

La primera línea es la línea del request, que contiene su información básica (método HTTP, URL y versión). Lo demás son headers HTTP.
<br>

4. **¿Qué es un queryString? (En el contexto de una url)**
- Las Query String o cadenas de consultas es un término que se utiliza para hacer referencia a una interacción con una base de datos. Además, es la parte de una URL que contiene los datos que deben pasar a las aplicaciones web.

5. ¿Qué es el responseCode? ¿Qué significado tiene los posibles valores devueltos?
- Los códigos de estado de respuesta HTTP indican si se ha completado satisfactoriamente una solicitud HTTP específica. Las respuestas se agrupan en cinco clases:

|CLASE|RANGO|
| ------ | ------ |
| Respuestas informativas|100-199|
| Respuestas satisfactorias|200-299|
| Redirecciones|300-399|
| Errores de los clientes|400-499|
| Errores de los servidores|500-599|

6. **¿Cómo se envía la data en un Get y cómo en un POST?**

|MÉTODO|CONCEPTO|OBSERVACIONES
| ------ | ------ | ------ |
| GET | GET lleva los datos de forma "visible" al cliente (navegador web). El medio de envío es la URL. Los datos los puede ver cualquiera. | Los datos son visibles por la URL, por ejemplo:www.aprenderaprogramar.com/action.php?nombre=pedro&apellidos1= gomez
| POST | POST consiste en datos "ocultos" (porque el cliente no los ve) enviados por un formulario cuyo método de envío es post. Es adecuado para formularios. Los datos no son visibles. | La ventaja de usar POST es que estos datos no son visibles al usuario de la web. En el caso de usar get, el propio usuario podría modificar la URL escribiendo diferentes parámetros a los reales en su navegador, dando lugar a que la información tratada no sea la prevista.

<br>

7. ¿Qué verbo http utiliza el navegador cuando accedemos a una página?
-  Se utiliza el verbo GET

8. Explicar brevemente qué son las estructuras de datos JSON y XML dando ejemplo de estructuras posibles.
- 









    





