| Carrera: | INGENIERIA DE SISTEMAS | | 
| --- | :--- | :---|
| Materia: | TECNOLOGIAS EMERGENTES II | 
| Apellidos y nombres: | JUAN QUISPE CANAVIRI |Q.
| C.I: | 9100170 L.P. | 
| Lugar y fecha: | EL ALTO 13 DE AGOSTO

# Práctica N° 1
---
## Sistemas empresariales
---
1) **Explique que son los sistemas empresariales**

***Respuesta***

SISTEMAS EMPRESARIALES Un sistema empresarial es un sistema central de la organización, que garantiza que la información se pueda transmitir atraves de todas las funciones empresariales, y todos los niveles de gestión, para soportar la operación y administración de una empresa. PANORAMA DE LOS SISTEMAS EMPRESARIALES: SISTEMA DE PROCESO DE TRANSACCIONES Y PLANEACIONDE RECURSOS EMPRESARIALES. Todas las organizaciones de procesamiento de transacción de datos (TPC), que capturan y procesan información con el detalle necesario para actualizar registros acerca de sus operaciones empresariales, la entrada de estos sistemas son las transacciones empresariales como: pedidos, órdenes de compras, recibos y facturas entre otros. 

2) **Describa cuales son las características más importantes de una aplicación empresarial**

Nombre Matrícula: Nombre del curso: Tecnologías de información para los negocios, Características de las tecnologías de información y de los sistemas empresariales. Tecnologías de información para los negocios 
 Objetivo: Conocer la estructura organizacional de una empresa a base de sus funciones. 

3) **Investigue y proponga cinco (5) instituciones que requerirían aplicaciones de misión crítica. 
Justifique su respuesta**

4) **Explique cuáles son las diferencias entre la escalabilidad horizontal y escalabilidad vertical**

Se entiende por escalabilidad a la capacidad de adaptación y respuesta de un sistema con respecto al rendimiento del mismo a medida que aumentan de forma significativa el número de usuarios del mismo. Aunque parezca un concepto claro, la escalabilidad de un sistema es un aspecto complejo e importante del diseño.
La escalabilidad esta íntimamente ligada al diseño del sistema. Influye en el rendimiento de forma significativa. Si una aplicación esta bien diseñada, la escalabilidad no constituye un problema. Analizando la escalabilidad, se deduce de la implementación y del diseño general del sistema. No es atributo del sistema configurable.
La escalabilidad supone un factor crítico en el crecimiento de un sistema. Si un sistema tiene como objetivo crecer en el numero de usuarios manteniendo su rendimiento actual, tiene que evaluar dos posibles opciones:

Con un hardware de mayor potencia o

Con una mejor combinación de hardware y software.

Se pueden distinguir dos tipos de escalabilidad, vertical y horizontal:

El escalar verticalmente o escalar hacia arriba, significa el añadir más recursos a un solo nodo en particular dentro de un sistema, tal como el añadir memoria o un disco duro más rápido a una computadora.

La escalabilidad horizontal, significa agregar más nodos a un sistema, tal como añadir una computadora nueva a un programa de aplicación para espejo.



5) **Que es un servidor Web y que es un servidor de aplicaciones**

El servidor web (también llamado webserver en inglés) es el software que se encarga de despachar el contenido de un sitio web al usuario.
Este proceso de despacho, que a simple vista parece muy simple, es en realidad más complejo de lo que parece, pues toda la «magia» de un webserver ocurre fuera de quien está navegando por un sitio web. Existen multitud de servidores web, y entre los más conocidos podemos encontrar por ejemplo a Apache, Nginx, LiteSpeed o IIS.

6) **Con un gráfico explique cómo funciona el protocolo HTTP**

![](http://img.youtube.com/vi/tN9yBV-B8Hw/0.jpg)

7) **Explique los elementos importantes de REQUEST en HTTP**

El comando HTTP Request permite enviar todo tipo de petición HTTP a un URL específico y procesar la respuesta del servidor HTTP.
Una línea de request para obtener el recurso, por ejemplo un request con el método GET /content/page1.html está requiriendo el recurso llamado /content/page1.html del servidorEncabezados. Indican cosas como el lenguaje, codificación, tipo de datos (XML,JSON, etc). (Por ejemplo– Accept-Language: EN).Una línea vacía.Un cuerpo del mensaje que es opcional. Entre aplicaciones esta es la parte mas importante. Por ejemplo, yo puedo enviar un XML o un JSON  a otra máquina, y el servidor web interpretara la información que yo le mando.

8) **Explique los elementos importantes de RESPONSE en HTTP**

A través del helper response() podemos crear fácilmente una instancia del objeto Response con el que podemos hacer varios ejemplos de uso de personalización de la respuesta.
El helper response(), como puedes ver, recibe dos parámetros: 

Contenido de la respuesta 
Código de status

El contenido es el texto que devuelve como respuesta la solicitud HTTP. El código de status son los típicos que debes de conocer del protocolo HTTP. 200 significa "todo correcto".

Después de la invocación al helper response() recibimos como valor de devolución un objeto de la clase Response. Éste objeto es el que devuelve el closure y que Laravel toma para componer la respuesta HTTP.

9) **Describa con un gráfico la arquitectura Java EE**

![](https://users.dcc.uchile.cl/~jbarrios/J2EE/arq.gif)

10) **Explique cuáles son los contenedores, componentes y servicios de Java EE**

En la siguiente figura se muestra los tipos de contenedores para los diferentes componentes:

![](http://2.bp.blogspot.com/-xtOAc9rZSpc/U9_4CLOvnRI/AAAAAAAAAPQ/vX2vnfJhcWk/s1600/Captura.PNG)


El servidor y los contenedores son:

Java EE Server: La porción de tiempo de ejecución de un producto Java EE. provee los contenedores web y de ejb.

Contenedor EJB: Maneja la ejecución de los enterprise beans.

Contenedor Web: Maneja la ejecución de las paginas web, servlets y algunos componentes ejb para las aplicaciones Java EE.

Contenedor de aplicación cliente: Maneja la ejecución de la aplicación cliente no necesita un servidor de aplicaciones.

Contenedor Applet: Maneja la ejecución de applets, no necesita servidor de aplicaciones, consiste en un browser y el plugin web de java.

11) **Investigue los métodos más utilizados de las clases HttpServlet, HttpServletRequest y 
HttpServletResponse, y para cada uno de los métodos muestre un ejemplo.**
