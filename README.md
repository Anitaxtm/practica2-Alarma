# practica2-Alarma

PRACTICA 2 ALARMA CON REEDSWITCH EN ARDUINO
===========================================

DESCRIPCION DE LA PRACTICA
--------------------------

Practica que utiliza un ReedSwitch para hacer la simulación de activación de 
una alarma para puerta, la cual utiliza también un Buzzer y un led los cuales 
se activan cuando el ReedSwitch está en estado LOW (cuando el imán no está cerca del ReedSwitch) 
y es en este momento cuando empezara a sonar el Buzzer y a prender y apagar el Led indicando 
la activación de la alarma (cuando la puerta está abierta). También se le implemento 
el ahorro de energía SLEEP_MODE_PWR_DOWN el cual ahorrara energía del Arduino mientras 
no se produzca una interrupción. La interrupción se producirá cuando el ReedSwitch 
este en estado LOW y comenzara el funcionamiento de activación de la alarma. 
El led 13 del Arduino se prendera cuando no se esté usando el ahorro de energía, y 
se apagara cuando se esté implementando el ahorro de energía.

Contiene los siguientes archivos:
-------------------------------------------
 
README.md: este archivo.

Alarma_PuertaAbierta.jpg: Foto del circuito activado simulando cuando la puerta está abierta (el imán está lejos del ReedSwitch).

Alarma_PuertaCerrada.jpg: Foto del circuito en modo ahorro de energía simulando cuando la puerta está cerrada (el imán está en el ReedSwitch).

Codigo_Alarma_ReedSwitch_Arduino: programa en Arduino que contiene las instrucciones en código que se llevaron a cabo para la realización del proyecto.

Diagrama.png: Imagen del diagrama de las conexiones y componentes utilizados para hacer la práctica.

Diagrama_Alarma.fzz: Diagrama de las conexiones y componentes realizados para hacer la practica hecha en Fritzing.

Evidencia2_UtilizacionDeLinux.png: Foto donde se muestra el código utilizando el sistema operativo Ubuntu.

Evidencia_UtilizacionDeLinux.png: Imagen de captura de pantalla donde se muestra el código utilizando el sistema operativo Ubuntu.

Foto_circuito_Alarma.jpg: Foto donde se muestra el circuito hecho en físico.

Nota
------

Es importante que en el código al momento de utilizarlo hacer los cambios necesarios, si es que se necesita, por si no se sigue el armado del circuito que se muestra en el diagrama.

Se necesitara un imán para simular una puerta cerrada y abierta con el ReedSwitch.


Contacto.
--------------
correo electronico: anitaxtm@hotmail.com
