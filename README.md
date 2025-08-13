### Te presentamos a MiniBot DS2, un kit para armar un robot con orugas, sensor de distancia, y totalmente programable.

<p align="center">
  <img src="https://github.com/user-attachments/assets/19cead73-eca3-4f60-8209-6eb909850203" alt="MiniBotDS2 box" width="560"/>
</p>

Este kit está pensado para que los pequeños desarrollen sus habilidades de construcción, robótica y programación. Dentro de la caja encontraras todo lo necesario para ensamblarlo, y podrás programarlo por medio del lenguaje de programación más popular para robots: Arduino, además, si aún no sabes nada sobre programación, ¡No te preocupes!, ya que es totalmente compatible con Nairda programming, un lenguaje de programación visual basado únicamente en bloques, así que bastará con que instales el programa para cualquier plataforma: MacOS, Windows, Android y pruebes los ejemplos que se incluyen. En poco tiempo serás capaz de hacer tus propios programas.

---
[Página oficial de Nairda programming](https://nairda.com.mx/#/about)
---

<br>
<br>

<p align="center">
  <img src="https://github.com/user-attachments/assets/36010b20-9203-45fc-9d48-2bf162e45eb4" alt="Nairda" width="460"/>
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/c5ce35f5-924f-4317-b4b7-cf3844f8651c" alt="Nairda logo" width="460"/>
</p>

Este kit incluye:

- Tarjeta electrónica Tuxedo 18650, compatible con Arduino y Nairda software.
- Caja de baterias con 2 pilas recargables ¡no necesitaras comprar baterias nunca!
- 2 motorreductores
- 1 servo motor de 9 gramos.
- 1 sensor ultrasónico de distancia.
- 2 orugas de goma.
- Engranes de acrílico.
- Patrones con las piezas del robot en madera MDF.
- Tornillería.
- Manual de ensamble.
- Cables.

<br>

## En el siguiente enlace encontrarás el **manual de ensamble** a todo color:

<br>

https://github.com/RocketLauncherCDMX/MiniBotDS2/releases/download/V1.0/MiniBotDS2_manual_completo.pdf

<br>

---

<br>

El empaque tiene un tamaño de 30x20x5cm, y un peso aproximado de 800g, y contiene todo lo necesario para su armado. Lo único de deberás tener a la mano son unas pinzas, un desarmador de cruz y pegamento blanco.

Al abrir la caja encontrarás el manaul, y debajo de el, todas las partes mecánicas en un bloque de espuma de poliuretano que se encarga de protejer los motores, servo, baterías, sensor de distancia, orugas de caucho, interruptor de alimentación, cables, engranes, un par de piezas MDF y una caja con toda la tornillería. Quita todos los componentes y ponlos de manera ordenada en una mesa para que el montaje sea más dinámico. Notarás que las protecciones se encuentran adheridas a las hojas de MDF que contienen las piezas cortadas en láser, por medio de una pelicula plástica. Bastará con que retires con cuidado este filme para que las piezas queden libres. Ya no usaremos la espuma ni el film plástico.

<p align="center">
  <img src="https://github.com/RocketLauncherCDMX/MiniBotDS2/blob/68fae42c54592296fa8c8d436ecb1395f727c641/box_content.png" alt="Contenido de la caja" width="780"/>
</p>

<br>

<p align="center">
  <img src="https://github.com/RocketLauncherCDMX/MiniBotDS2/blob/68fae42c54592296fa8c8d436ecb1395f727c641/box_content_02.png" alt="Espuma con componentes" width="780"/>
</p>

El corazón de Minibot DS2 es la placa Tuxedo 18650, la cual tiene un microcontrolador de 32 bits ESP32, potencia de sobra para manejar las entradas y salidas, conectividad bluetooth y Wifi, control de los motores, LEDs, botones y buzzer.

<p align="center">
  <img src="https://github.com/RocketLauncherCDMX/MiniBotDS2/blob/51f389f2e7053ad8fde13cf00cd0fa613a119678/Tuxedo18650_V1.0_noSwitch.png" alt="Tuxedo 18650 frente" width="480"/>
</p>

Esta tarjeta está pensada para tener todo lo necesario para una infinidad de prácticas con este robot, y se puede programar sin necesidad de una biblioteca dedicada, ya que la definición de todos los pines se encuentra en la parte trasera. En Arduino, bastará con declarar las entradas o salidas con el número de pin asociado para leer los botones, encender los LEDs, poner pines en alto o bajo y controlar los motores.

<p align="center">
  <img src="https://github.com/RocketLauncherCDMX/MiniBotDS2/blob/815c25c465b75ad5fa6b0acd36dab7c36775bc81/Tuxedo18650_V1_back.png" alt="Tuxedo 18650 atras" width="480"/>
</p>

<br>

## Toda la información necesaria para utilizar la **Tuxedo 18650** la encontrarás en el siguiente link:

<br>

https://github.com/RocketLauncherCDMX/Tuxedo18650

<br>

---

## Programando tu MiniBot DS2 en Arduino

Si ya seguiste las instrucciones del manual para ensamblar tu robot, y conectaste todo como se indica, entonces es hora de programarlo. El MiniBot DS2 trae un programa muy sencillo de ejmplo, que funciona por medio de comandos Seriales enviados desde la computadora por medio de USB. Para poder probarlo es necesario tener el programa Arduino instalado en tu computadora. Puedes seguir los siguientes pasos para su instalación:

<br>

[Pasos para instalar Arduino en tu PC](https://github.com/RocketLauncherCDMX/ArduinoInstall)

<br>

---
