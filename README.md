[//]: <> (PORTADA)

# DIAGRAMAS DE COMPORTAMIENTO
## <u>Entornos de desarrollo</u>

![logo de diagramas de comportamiento](https://sites.google.com/site/analisisguzmanjose/_/rsrc/1427436460730/unidad-3-modelos-de-actividad-y-de-estado/3-1-diagramas-de-comportamiento/png%20%289%29.png)

<!--
    TABLA DE CONTENIDO
-->

### **Contenido**
[¿Qué es un diagrama de comportamiento?](#¿qué-es-un-diagrama-de-comportamiento)

Tipos:<br>
      1. [Diagrama de casos de uso](#diagrama-de-casos-de-uso)<br>
      2. [Diagrama de Interacción](#diagrama-de-interacción)<br>
      3. [Diagrama de secuencia](#diagrama-de-secuencia)<br>
      4. [Diagrama de actividades](#diagrama-de-actividades)<br>
      5. [Diagramas de Estado](#diagramas-de-estado)<br>
   		
[_Bibliografía_](#bibliografía)


#### ¿Qué es un diagrama de comportamiento?
Es un diagrama que expresa las secuencias de estado por los que pasa un objeto en su vida en respuesta a eventos. Se suelen usar para visualizar, documentar y especificar aspectos dinámicos de un sistema. Se define formalmente como: Diagrama que expresa las secuencias de estados por los que pasa un objeto a lo largo de su vida en respuesta a eventos.
Hablando en un lenguaje más llano, se trata de diagramas que muestran diferentes estados de un proceso. Mediante estos diagramas se plasman de forma gráfica los procesos a programar.
~~~
Estos diagramas se usan para visualizar y especificar, a la vez que documentar, aspectos dinámicos de un sistema. Estos diagramas pueden ser muy simples o muy complejos en función del proceso que están representando.  
~~~

Tipos:
#### Diagrama de casos de uso
El diagrama de casos de uso es una forma de diagrama de comportamiento en lenguaje de modelado unificado (UML, del inglés Unified Modelling Language), con la que se representan procesos empresariales, así como sistemas y procesos de programación orientada a objetos. Por lo tanto, UML no es un lenguaje de programación, sino un lenguaje de modelado, es decir, un método estandarizado para representar sistemas planificados o ya existentes. En este diagrama, todos los objetos involucrados se estructuran y se relacionan entre sí.

<img src="diagramasdecu.png" width='400px'>
<br>
<br>

#### Diagrama de Interacción
Es un tipo de diagrama UML que se centra en describir el flujo de los mensajes en un sistema. También, se usan para representar secuencias ordenadas en un sistema y actúan como medio para ver los datos en tiempo real. 
Tal como su nombre lo sugiere, un diagrama de interacción es un tipo de diagrama UML que se emplea para captar el comportamiento interactivo de un sistema. Los diagramas de interacción se centran en describir el flujo de mensajes dentro de un sistema y ofrecen contexto para una o más líneas de vida dentro de un sistema.
Además, los diagramas de interacción pueden emplearse para representar las secuencias ordenadas dentro de un sistema, y actúan como medio para visualizar los datos en tiempo real vía UML.
***
Ventajas de usar un Diagrama de Interacción:
- Nos muestra el sistema como una secuencia de eventos ordenados cronológicamente.
- Organiza la estructura de los eventos.
- Transmite de manera simple el comportamiento de un sistema,
  
---
Existen varios tipos dentro de los Diagramas de Interacción, que pueden ser:
- Diagrama de colaboración: Representa las relaciones/interacciones entre distintos objetos.
- Diagrama de secuencia: Otra opción de representar las interacciones.
- Diagrama de tiempos: Estos se usan para representar el estado de una línea de vida en una instancia de tiempo y muestra los cambios de un objeto. En un diagrama de tiempos se emplean ondas para visualizar el flujo en el programa.
- Diagrama global de interacciones: Actúa como una vista global del flujo de control en las interacciones, además del flujo de actividad entre diagramas.
___

#### Diagrama de Secuencia
El diagrama de secuencia es un tipo de diagrama usado para modelar interacción entre objetos en un sistema según UML. En inglés se pueden encontrar como "sequence diagram", "event-trace diagrams".Un diagrama de secuencia muestra la interacción de un conjunto de objetos en una aplicación a través del tiempo y se modela para cada caso de uso. A menudo es útil para complementar a un diagrama de clases, pues el diagrama de secuencia se podría describir de manera informal como "el diagrama de clases en movimiento", por lo que ambos deben estar relacionados entre sí (mismas clases, métodos, atributos...).

#### Diagrama de Actividades
Los diagramas de actividades, junto con los diagramas de casos de uso y los diagramas de máquina de estados, son considerados diagramas de comportamiento porque describen lo que debe suceder en el sistema que se está modelando.
Las partes interesadas tienen muchos asuntos que manejar, por lo que es importante una comunicación clara y concisa. Los diagramas de actividades ayudan a que las personas en las áreas de negocios y desarrollo de una organización se integren para comprender el mismo proceso y comportamiento. 
>Usarás un conjunto de símbolos especializados incluidos aquellos para pasos de inicio, finalización, fusión y recepción en el flujo- para crear un diagrama de actividades, lo cual cubriremos con más detalle dentro de esta guía de diagramas de actividades.

#### Diagramas de Estado
Un diagrama de estado muestra el estado inicial, final y al menos un estado intermedio de cada objeto. Este nos permite representar el ciclo de vida de  cualquier sistema, subsistema, componentes o clases. 
Cada diagrama de estados generalmente empieza con un círculo oscuro que indica el estado inicial y termina con un círculo de contorno blanco que denota el estado final. Sin embargo, a pesar de tener puntos de inicio y finalización definidos, los diagramas de estado no necesariamente son la mejor herramienta para plasmar un desarrollo general de eventos. 
Los diagramas de estado representan principalmente estados y transiciones. Los estados se representan con rectángulos de esquinas redondeadas que se etiquetan con el nombre del estado. Las transiciones se marcan con flechas que fluyen de un estado a otro, mostrando cómo cambian los estados. A continuación, podrás ver estos dos elementos en acción en un diagrama básico para la vida estudiantil. 

Está compuesto por: 
* Evento
* Actividades
* Estado, pudiendo ser :
    * Enviando mensajes
    * Subestados
    * Transición, que puede ser simple, interna o compleja
  
Las principales ventajas de los Diagrama de Estado son:
- Permite centrarse en las necesidades del usuario.
- Tiene éxito en sistemas interactivos. 
  
Los elementos principales de los Diagramas de Estado son:
1. Estado inicial
2. Estado final
3. Estado
4. Transición

Ejemplo:
<br>
<img src="Destado.png" width='500px' height='300px'>


| Diagramas de Comportamiento | |
| ----------- |:------------:|
| Diagrama de Casos de uso | Diagrama de Interacción |
| Diagrama de Secuencia| Diagrama de Actividades |
| Diagrama de Estado | |

#### Bibliografía:

\- [Link 1 - Diagrama de Comportamiento](https://www.ceac.es/blog/elaborar-diagramas-de-comportamiento-en-entornos-de-desarrollo#:~:text=Un%20diagrama%20de%20comportamiento%20se,vida%20en%20respuesta%20a%20eventos.&text=Estos%20diagramas%20se%20usan%20para,aspectos%20din%C3%A1micos%20de%20un%20sistema)<br>
\- [Link 2 - Diagrama de Interacción](https://www.lucidchart.com/pages/es/diagrama-de-interaccion-uml/#section_0)<br>
\- [Link 3 - Diagrama de Interacción](https://www.lucidchart.com/pages/es/diagrama-de-interaccion-uml)<br>
\- [Link 4 - Diagrama de Estado](https://www.ionos.es/digitalguide/paginas-web/desarrollo-web/diagrama-de-estado-uml/)<br>
\- [Link 5 - Diagrama de Estado](https://es.slideshare.net/betocardenas140/diagrama-de-estado-69392609)
