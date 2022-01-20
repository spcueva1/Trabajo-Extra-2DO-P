# Trabajo-Extra-2DO-P

Diseño de un ejemplo de interfaz de control con https://thingsboard.io/

# 1) OBJETIVOS

OBJETIVO GENERAL:

- Construir un ejemplo de interfaz de control mediante la utilizacion de thingsboard, asi tener claro como funciona este aplicativo y mostrar evidencias del mismo.

OBJETIVOS ESPECÍFICOS:

- Investigar el funcionamiento del aplicativo thingsboard mediante una ardua investigacion en fuentes confiables del internet y asi lograr utilizar el mismo.
- Elaborar en el aplicativo un sistema sobre la interfaz de control utilizando los conocimientos adquiridos por la investigacion.
- Explicar todo lo aprendido del aplicativo y el sistema diseñado de interfaz de control mediante un video explicativo.

# 2) Marco teorico


-	ThingsBoard: es una plataforma IoT de código abierto en la que podemos almacenar, visualizar y analizar los datos de nuestros dispositivos. (Celes, 19)

En esta sesión realizaremos un taller práctico para conectar un nodo The Things Network (concretamente el nodo TTN_MAD V2.1) a ThingsBoard, tratando los siguientes temas:

Usuarios: Una de las características diferenciadoras de ThingsBoad es su capacidad multitenant, es decir, que permite utilizar una misma instancia de la aplicación para distintas organizaciones. Por ejemplo, en el caso de una ciudad, podríamos configurar un tenant para cada empresa de mantenimiento de edificios, de forma que cada una de ellas pudiese gestionar independientemente los edificios de los que es responsable.

Activos: ThingsBoard permite jerarquizar entidades a través de las relaciones entre los activos; siguiendo  el ejemplo anterior, cada empresa de mantenimiento podría crear un activo por cada barrio, y dentro de ellos un activo por cada edificio, y dentro de ellos un activo por cada vivienda.

Dispositivos: Por defecto los dispositivos se integran mediante los protocolos HTTP POST, cliente MQTT o CoAP. Sin embargo, en el caso de The Things Network no podemos usar este camino porque la integración HTTP de ThingsBoard no admite los objetos JSON anidados que genera The Things Network. Afortunadamente ThingsBoard ofrece una aplicación específica para estos casos, denominada ThingsBoard Gateway, que actúa como pasarela entre el bróker MQTT de The Things Network y el de ThingsBoard.

Deashboards: Los datos enviados por los nodos se denominan telemetrías, y podemos visualiarlos utilizando multitud de widgets (tablas, gráficos de líneas, indicadores analógicos…).

Reglas: ThingsBoard incluye un motor de reglas similar a Node-RED con el que podemos analizar las telemetrías y realizar acciones, como enviar mensajes en caso de que se supere cierto umbral de temperatura.

Alarmas: Mediante las alarmas podemos mantener un registro de las situaciones en las que un determinado sensor se encuentra en estado de excepción, es decir, está registrando un valor fuera del rango tolerable (por ejemplo, un sensor de temperatura que supera cierto umbral), o no ha actualizado su telemetría desde hace más tiempo del que tiene asignado.


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
Espera que el valor esté en el rango de 0 a 360. Muestra el valor más reciente del atributo o clave de serie temporal en la brújula.

5) Indicador de barra LCD
Últimos valores
Indicador preconfigurado para mostrar cualquier lectura de valor como una barra. Permite configurar rango de valores, colores degradados y otras configuraciones.

6) Gráfico de líneas de serie temporal
serie de tiempo
Muestra los cambios en los datos de series temporales a lo largo del tiempo. Por ejemplo, lecturas de temperatura o humedad.

7) Indicador LCD
Últimos valores
Indicador preconfigurado para mostrar cualquier lectura de valor como un arco. Permite configurar rango de valores, colores degradados y otras configuraciones.

Mapa Conceptual

![]()

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

![](https://github.com/spcueva1/Trabajo-Extra-2DO-P/blob/0f8725c14fd3f99b21069637cea2d2f1d7719666/extra%20things/6.png)



# 5) Video




# 6) Conclusiones.

- Se logro construir un ejemplo de interfaz de control mediante la utilizacion de thingsboard, ademas se logro tener claro como funciona este aplicativo.
- Se investigo el funcionamiento del aplicativo thingsboard mediante una ardua investigacion en fuentes confiables del internet y se pudo poner en practica.
- Se diseño en el aplicativo un sistema sobre la interfaz de control utilizando los conocimientos adquiridos por la investigacion incluyendo varios elementos. 
- Se explico todo lo aprendido del aplicativo y el sistema diseñado de interfaz de control mediante un video explicativo.

# 7) Bibliografia

- Celes, M. (12 de 7 de 19). The Things Network. Obtenido de https://www.medialab-matadero.es/actividades/taller-de-introduccion-thingsboard#:~:text=ThingsBoard%20es%20una%20plataforma%20IoT,los%20datos%20de%20nuestros%20dispositivos.&text=Deashboards%3A%20Los%20datos%20enviados%20por,l%C3%ADneas%2C%20indicadores%2

- Blanco, S. (12 de 8 de 2014). platea.pntic. Obtenido de http://platea.pntic.mec.es/vgonzale/cyr_0708/archivos/_15/Tema_2.1.htm
