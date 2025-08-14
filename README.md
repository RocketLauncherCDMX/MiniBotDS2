# EasyFinder DS2

### Te presentamos a MiniBot DS2, un kit para armar un robot con orugas, sensor de distancia, y totalmente programable.

<p align="center">
  <img src="https://github.com/RocketLauncherCDMX/MiniBotDS2/blob/134e7b23405e8d896ac98528fd9b899120c47dd7/MiniBotDS2_ilustracion.png" alt="MiniBotDS2 ilustracion" width="1080"/>
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
<br>

<p align="center">
  <img src="https://github.com/RocketLauncherCDMX/MiniBotDS2/releases/download/V1.0/MiniBotDS2_medidas.png" alt="Medidas Minibot DS2" width="780"/>
</p>

<br>

## En el siguiente enlace encontrarás el **manual de ensamble** a todo color:

<br>

[Manual de ensamble MiniBot DS2](https://github.com/RocketLauncherCDMX/MiniBotDS2/releases/download/V1.0/MiniBotDS2_manual_completo.pdf)

<br>

---

<br>

El empaque tiene un tamaño de 30x20x5cm, y contiene todo lo necesario para su armado. Lo único de deberás tener a la mano son unas pinzas, un desarmador de cruz y pegamento blanco.

Al abrir la caja encontrarás el manaul, y debajo de el, todas las partes mecánicas en un bloque de espuma de poliuretano que se encarga de protejer los motores, servo, baterías, sensor de distancia, orugas de caucho, interruptor de alimentación, cables, engranes, un par de piezas MDF y una caja con toda la tornillería. Quita todos los componentes y ponlos de manera ordenada en una mesa para que el montaje sea más dinámico. Notarás que las protecciones se encuentran adheridas a las hojas de MDF que contienen las piezas cortadas en láser, por medio de una pelicula plástica. Bastará con que retires con cuidado este filme para que las piezas queden libres. Ya no usaremos la espuma ni el film plástico.

<p align="center">
  <img src="https://github.com/RocketLauncherCDMX/MiniBotDS2/blob/68fae42c54592296fa8c8d436ecb1395f727c641/box_content.png" alt="Contenido de la caja" width="780"/>
</p>

<br>

<p align="center">
  <img src="https://github.com/RocketLauncherCDMX/MiniBotDS2/blob/68fae42c54592296fa8c8d436ecb1395f727c641/box_content_02.png" alt="Espuma con componentes" width="780"/>
</p>

---
## TUXEDO 18650

El corazón de Minibot DS2 es la placa Tuxedo 18650, la cual tiene un microcontrolador de 32 bits ESP32, potencia de sobra para manejar las entradas y salidas, conectividad bluetooth y Wifi, control de los motores, LEDs, botones y buzzer.

<p align="center">
  <img src="https://github.com/RocketLauncherCDMX/MiniBotDS2/blob/51f389f2e7053ad8fde13cf00cd0fa613a119678/Tuxedo18650_V1.0_noSwitch.png" alt="Tuxedo 18650 frente" width="480"/>
</p>
<br>

Esta tarjeta está pensada para tener todo lo necesario para una infinidad de prácticas con este robot, y se puede programar sin necesidad de una biblioteca dedicada, ya que la definición de todos los pines se encuentra en la parte trasera. En Arduino, bastará con declarar las entradas o salidas con el número de pin asociado para leer los botones, encender los LEDs, poner pines en alto o bajo y controlar los motores.

<p align="center">
  <br>
  <img src="https://github.com/RocketLauncherCDMX/MiniBotDS2/blob/815c25c465b75ad5fa6b0acd36dab7c36775bc81/Tuxedo18650_V1_back.png" alt="Tuxedo 18650 atras" width="480"/>
</p>

<br>

Toda la información necesaria para utilizar la **Tuxedo 18650** la encontrarás en el siguiente link:

<br>

[Información técnica de la tarjeta Tuxedo 18650](https://github.com/RocketLauncherCDMX/Tuxedo18650)

<br>

---

## Programando tu MiniBot DS2 en Arduino

Si ya seguiste las instrucciones del manual para ensamblar tu robot, y conectaste todo como se indica, entonces es hora de programarlo. El MiniBot DS2 trae un programa muy sencillo de ejmplo, que funciona por medio de comandos Seriales enviados desde la computadora por medio de USB. Para poder probarlo es necesario tener el programa Arduino instalado en tu computadora. Puedes seguir los siguientes pasos para su instalación:

<br>

[Pasos para instalar Arduino en tu PC](https://github.com/RocketLauncherCDMX/ArduinoInstall)

<br>

Posteriormente, deberás instalar el core del microcontrolador ESP32 para tener acceso a todos los recursos del hardware. Puedes seguir estas instrucciones:

<br>

[Cómo instalar el core para el microcontrolador ESP32](https://github.com/RocketLauncherCDMX/expressifCoreArduinoInstall)

<br>

---

En el siguiente link puedes descargar los programas de ejemplo para hacer las pruebas en el Minibot y puedas comenzar a entender como funciona cada una de sus partes 

<br>

[Firmware de ejemplo para arduino](https://github.com/RocketLauncherCDMX/MiniBotDS2/releases/download/V1.0/Firmware_basicFunctionality.zip)

<br>

Este archivo llamado **Firmware_basicFunctionality.zip** es lo que se conoce como un archivo comprimido .zip el cual en realidad es una carpeta con más archivos dentro. Para poder tener acceso a su contenido, lo primero que hay que hacer es descomprimirlo. Vas a dar click derecho sobre el archivo y seleccionarás **Extraer todo...**. También puede estar dentro de la última opción **mostrar más opciones** 

<img width="464" height="371" alt="Click derecho" src="https://github.com/user-attachments/assets/726e0f35-63e7-4222-baf6-38cbb8666f38" />

<br>
<br>

Dentro de la opción de descomprimir, tendrás que seleccionar donde quieres guardar los archivos. Usualmente, por defecto, Windows selecciona la carpeta Descargas, pero tu puedes cambiarla. Das click en **Extraer** y aparecerá el mismo archivo, pero ahora si, como una carpeta.

<img width="623" height="500" alt="Descomprimir archivo" src="https://github.com/user-attachments/assets/86207447-e5e5-4d93-bd13-f1eea8ccac31" />

<br>
<br>

Al acceder a la carpeta, encontrarás las siguientes subcarpetas:

```
basicFunctionality
bluetoothInterface
wifiInterface
```

<br>
<br>

Dentro de ellas se encuentra un archivo de Arduino con su mismo nombre. Si ya tienes instalado Arduino, entonces, se mostrarán con su ícono y solamente bastará con dar doble click para abrir el sketch.

El programa **basicFunctionality.ino** es el que viene programado en la Tuxedo 18650 de tu kit. Si quieres comprobar como funciona, deberás emplear el monitor Serial siguiendo los siguientes pasos:

1. Conecta la placa Tuxedo18650 a la computadora, por medio del cable USB C incluido. Enciende el interruptor principal externo del robot que conectaste en uno de los pasos. Debe encenderse el LED verde ON. Este paso es muy importante, ya que si la tarjeta no se encuentra encendida, no fucnionará el programa.

2. Iremos al menú **Herramientas/Placa/ESP32 Arduino** y seleccionaremos **ESP32 Dev Module** como placa.

![Artboard 12](https://github.com/user-attachments/assets/53b1fae0-6968-4452-887a-c9ea696c2288)

3. En el menú **Herramientas/Puerto** seleccionamos el puerto que haya aparecido. Usualmente es diferente de COM1.

![portCOM](https://github.com/user-attachments/assets/8e99586a-9cc5-4caa-af16-0b27a452d319)

4. Abrimos la consola Serial para ver lo que el control está haciendo. En la esquina superior derecha encontrarás el ícono (una lupa).

![monitorSerial](https://github.com/user-attachments/assets/8ee90f7f-91f9-4460-9598-5bff69639f09)

5. Asegúrate de que la velocidad Serial se encuentre a **115200 Baudios** y **Retorno de carro**.

<img width="979" height="658" alt="Monitor serial" src="https://github.com/user-attachments/assets/496ab20a-3d1d-4748-8fdb-00254b938ff1" />

<br><br>

6. Ahora ya puedes controlar tu robot y explorar los mensajes que manda la Tuxedo 18650. Aquí tienes los comandos que puedes enviar para interactuar con tu robot:

|comando (tecla) | Accion             |
|----------------|--------------------|
|w|Avanzar|
|s|Retroceder|
|a|Girar a la izquierda|
|d|Girar a la derecha|
|z|Detener motores|
|q|Medir distancia|
|1|Cabeza gira a la izquierda|
|2|Cabeza centrada|
|3|Cabeza gira a la derecha|

<br>

Te invitamos a explorar los otros 2 códigos, con los que aprenderas a controlar tu MiniBot DS2 de maneras únicas y divertidas :)

<br>

<p align="right">
  <img src="https://github.com/user-attachments/assets/22f18627-fa08-405f-9d04-3672e83b1f30f" alt="Rocket Launcher" width="400"/>
</p>
