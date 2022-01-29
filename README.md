# Trabajo-Extra-2DO-P

Diseño de un ejemplo de interfaz de control con https://thingsboard.io/

# 1) OBJETIVOS

OBJETIVO GENERAL:

- Explicar el funcionamiento del aplicativo thingsboard mediante la utilizacion de una interfaz de control aplicando en un circuito basico electrico.

OBJETIVOS ESPECÍFICOS:

- Investigar el funcionamiento del aplicativo thingsboard sus herramientas para manejar de manera correcta.

- Conocer caracteristicas tecnicas del aplicativo y sus widgets a utilizar.

- Diseñar un circuito utilizando widgets del aplicativo para las mediciones correctas del mismo.

# 2) Marco teorico


-	ThingsBoard: es una plataforma IoT de código abierto en la que podemos almacenar, visualizar y analizar los datos de nuestros dispositivos. (Celes, 19)
Existen numerosos protocolos y formatos de datos de IoT, ,algunos de ellos son más populares, como MQTT y JSON. Normalmente la mayoría de las plataformas IoT brindan soporte para los protocolos y formatos de datos más populares desde el primer momento, pero es difícil respaldar a todos en una sola solución.
Con el crecimiento de la comunidad de código abierto de la plataforma Thingsboard, ha comenzado a recibir solicitudes sobre el soporte de protocolos IoT, como OPC-UA y algunos formatos de datos específicos, de modo que también han decidido implementar esta funcionalidad como un proyecto separado de código abierto que  permitirá unir la plataforma API a, literalmente, cualquier dispositivo.

- Que es una interfaz de control.

Un sistema de control debe estar equipado para la alteración de una o varias magnitudes de un sistema real con objeto de proporcionar una respuesta activa que modifique su comportamiento. Como ejemplo complejo de un sistema de control se puede pensar en un "edificio inteligente", que comprueba y analiza permanentemente el estado de la temperatura, la iluminación, etc., gracias a diferentes sensores. Mediante un ordenador es capaz de actuar de acuerdo con su programación sobre diversos dispositivos actuadores para regular las condiciones de las estancias y mantenerlas en los niveles deseados. Así pues, un sistema de control comprende, en general, los sistemas y dispositivos (Blanco, 2014)

- Widget utilizados para la interfaz de control

1) Control del interruptor.
Widget de control
Activar o desactivar algun LCD del monitor vislizando en el mismo.

2) Interruptor redondo
Widget de control
Permite enviar la llamada RPC al dispositivo cuando el usuario cambia el interruptor.

3) Indicador LED
Widget de control
Cabia de color dependiendo el estado del esquña activado o no.

4) Brújula
Últimos valores
Muestra el valor más reciente del atributo o clave de serie temporal en la brújula.

5) Indicador de barra LCD
Últimos valores
Permite configurar rango de valores, colores degradados y otras configuraciones.

6) Gráfico de líneas de serie temporal
serie de tiempo
Muestra los cambios en los datos de series temporales a lo largo del tiempo.

7) Indicador LCD
Últimos valores
Permite configurar rango de valores, colores degradados y otras configuraciones.

Mapa Conceptual

![](https://github.com/spcueva1/Trabajo-Extra-2DO-P/blob/4b5983bdac1162a469c2630de86112501f0fb5b1/Flowchart.jpg)

# 3) Explicacion de procedimiento

1) ingresar en la plataforma y hacer click en "Pruebalo ahora"

![](https://github.com/spcueva1/Trabajo-Extra-2DO-P/blob/0f8725c14fd3f99b21069637cea2d2f1d7719666/extra%20things/1.png)

2) Colocar en edición de la comunidad y señalar demo en vivo ingresar su informacion para registrarse.

![](https://github.com/spcueva1/Trabajo-Extra-2DO-P/blob/0f8725c14fd3f99b21069637cea2d2f1d7719666/extra%20things/2.png)

3) En la nueva pestaña colocarse en paneles y agregar un diseño propio.

![](https://github.com/spcueva1/Trabajo-Extra-2DO-P/blob/0f8725c14fd3f99b21069637cea2d2f1d7719666/extra%20things/3.png)

4) Hacer clic en el lapiz mas y la imagen del documeto y se podra señeccionar el paquete de widgets.

![](https://github.com/spcueva1/Trabajo-Extra-2DO-P/blob/0f8725c14fd3f99b21069637cea2d2f1d7719666/extra%20things/4.png)

5) Seleccionar al gusto dependiendo el criterio que tenga el programa.

![](https://github.com/spcueva1/Trabajo-Extra-2DO-P/blob/0f8725c14fd3f99b21069637cea2d2f1d7719666/extra%20things/5.png)



# 4) Respuestados

Utilizamos el aplicativo ThingsBoard para elaborar una interfaz de control la cual fue puesta en practica como lo muestra la siguiente imagen. 

Para colocar nuevos widgets podemos ir incrementando segun lo necesario y para esto se necita poner el alias que es lo mas improtante seguido las carateristicas que va tener este widgets para su correcto funcionamiento.

https://youtu.be/s6tMceYDLOM

![](https://github.com/spcueva1/Trabajo-Extra-2DO-P/blob/0f8725c14fd3f99b21069637cea2d2f1d7719666/extra%20things/6.png)



# 5) Video

-  https://www.youtube.com/watch?v=pyeGFBaGjy8

# 6) Conclusiones.

- Para la construccion la interfaz de control mediante el aplicativo de thingsboard, realizamos una investigacion del aplicativo la cual nos dice que este es un sistema de codigo abierto la cual ayuda a almacenar, visualizar y analizar los datos de nuestros dispositivos. 

- Las herramientas utilizadas en esta interfaz fueron las que ayuden a visualizar las lecturas del circuito como medidor de voltaje, intensidad, potencia. Sus especificacios de cada uno fue explicado en el mapa conceptual.

- Los diferentes widgets utilizados fueron modificados segun su conveniencia, cambiando su nombre dependiendo el funcionamiento, las caracteristicas a desarrollar y lo que tiene que mostrar en pantalla. 

# 7) Bibliografia

- Celes, M. (12 de 7 de 19). The Things Network. Obtenido de https://www.medialab-matadero.es/actividades/taller-de-introduccion-thingsboard#:~:text=ThingsBoard%20es%20una%20plataforma%20IoT,los%20datos%20de%20nuestros%20dispositivos.&text=Deashboards%3A%20Los%20datos%20enviados%20por,l%C3%ADneas%2C%20indicadores%2

- Blanco, S. (12 de 8 de 2014). platea.pntic. Obtenido de http://platea.pntic.mec.es/vgonzale/cyr_0708/archivos/_15/Tema_2.1.htm
