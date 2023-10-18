# 1er-parcial-de-SPD
:books:primer parcial de la materia de sistema de procesamiento de datos de la carrera de tecnicatura en programacion en la utn 2023


:paperclip: Integrantes.




:angel: matias Mazzino

:angel:Valentin Giraldi

:angel:ignacio Villalba


:bomb:PROJECTO: 

Parte 1: Contador de 0 a 99 con Display 7 Segmentos y Multiplexación


![](https://github.com/MatiasMazzino2001/1er-parcial-de-SPD/blob/main/primer%20parcial%20spd%202.jpeg)


:bell:Descripcion


Con este proyecto planteamos un codigo de arduino para crear un contador con displays de 7 segmentos y multiplexacion.


:computer: Funcion principal


Este código se utiliza para crear un contador que muestra valores en dos displays de 7 segmentos y se controla mediante tres botones en un Arduino Uno R3 en Tinkercad. Su funcionalidad es la siguiente:
Configura las conexiones de los displays de 7 segmentos y los botones en el Arduino.
Utiliza tres botones para controlar el contador:
El botón "Incrementar" aumenta el valor del contador.
El botón "Decrementar" disminuye el valor del contador.
El botón "Reiniciar" restablece el contador a 0.
Utiliza la técnica de multiplexación para mostrar los dígitos del contador en los displays de 7 segmentos, evitando el parpadeo al cambiar los dígitos.
Muestra los dígitos del contador de 0 a 99 en los displays de 7 segmentos.
En resumen, el código crea un contador con dos displays de 7 segmentos que puede aumentar, disminuir y reiniciar su valor utilizando tres botones, y muestra el valor actual en los displays.

:satellite:Enlace del proyecto


https://www.tinkercad.com/things/84cOtP9RYw3-cool-kasi-fyyran/editel?tenant=circuits


Parte 2: Modificación con Interruptor Deslizante y Números Primos


![](https://github.com/MatiasMazzino2001/1er-parcial-de-SPD/commit/90a6d5b804718e48844a57466c2b5ebee40ff666)



:bell:Descripcion
presentamos un codigo de arduino para mostrar uma modificacion de la primera parte agregando un interruptor deslizante



:computer: Funcion principal
El código principal es un programa de Arduino que controla un contador de dos dígitos y la visualización de números primos en un display de 7 segmentos. Aquí está una descripción de las partes clave:
El código configura dos displays de 7 segmentos, un botón para incrementar, un botón para decrementar y un interruptor deslizante que permite alternar entre el contador y los números primos.
En la función loop(), se lee el estado del interruptor deslizante para determinar si se debe mostrar el contador o los números primos en el display.
Si el interruptor está en una posición, muestra los números primos llamando a la función displayPrimes(). Esta función aún necesita ser implementada para mostrar números primos.
Si el interruptor está en la otra posición, el código verifica el estado de los botones para incrementar o decrementar el contador. Cuando se presiona uno de los botones, el contador se incrementa o decrementa en 1 y se muestra en el display.El código utiliza la técnica de multiplexación para mostrar los valores en el display de 7 segmentos, lo que evita el parpadeo al cambiar los dígitos.
En resumen, el código principal controla un contador y alterna entre mostrar el contador y los números primos en función de la posición del interruptor deslizante. Puedes personalizar la lógica para mostrar números primos en la función displayPrimes() según tus necesidades.



:satellite:Enlace del proyecto
https://www.tinkercad.com/things/cVglYRGo3dx-glorious-trug/editel

:mailbox:Fuentes


https://www.youtube.com/playlist?list=PL7LaR6_A2-E11BQXtypHMgWrSR-XOCeyD



