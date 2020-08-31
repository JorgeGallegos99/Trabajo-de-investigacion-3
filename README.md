# Trabajo-de-investigacion-3 Salida y entrada de Datos en una RaspBerry PI

## Informe

### 1. PLANTEAMIENTO DEL PROBLEMA

La Raspberry PI aparece con la necesidad de incentivar y promover la enseñanza de la programación para los estudiantes que causa interés y curiosidad.

Los campos de aplicación del Raspberry Pi son múltiples y posee numerosas posibilidades de uso generales para las que el miniordenador está predestinado. Para llevar a cabo proyectos con Raspberry Pi son necesarios ciertos conocimientos, pero si se tiene el interés suficiente, no habrá nada que impida su realización, más bien todo lo contrario: el hecho de experimentar con la placa y de aprender nuevos conocimientos que constituyen un método práctico y divertido para adentrarse en el campo electrónica digital e informática.

En base los puntos planteados se pretende realizar un circuito que permita visualizar ejemplos de entrada y salida de datos utilizando la Raspberry Pi.

### 2. OBJETIVOS

#### General

Diseñar un circuito que permita la entrada y salidas de datos en una Raspberry Pi, para la implementación se utilizará el simulador virtual  Wyliodrin.studio.

#### Especifícos
 
* Crear un circuito que permita la entrada y la salida de datos en una RaspBerry Pi.
* Conocer la estructura de la Raspberry Pi, el funcionamiento y como utilizarla en circuitos digitales.
* Investigar las instrucciones básicas de la librería GPIO de Javascript  para el control entrada y salida de datos de la Raspberry pi utilizando el simulador online Wyliodrin.studio. 
* Describir los principales componentes que facilita el simulador Wyliodrin studio.

### 3. ESTADO DEL ARTE

**1. Implementación del Asistente de Google en Rasberry Pi**

Una investigación detallada sobre cómo implementar la voz del asistente de Google en una microcomputadora Raspberry Pi. En el artículo se encuentran todos los detalles y cada uno de los pasos para poder implementar el asistente de Google a este dispositivo que tan solo contiene un micrófono y un altavoz. Además, de la implementación también realizaron la evaluación de un sistema de reconocimiento de voz.

**Autores:**

**Septimiu Mischie**

Facultad de Electrónica, Telecomunicaciones e Información, Tecnologías Politehnica University of Timisoara, Timisoara, Rumania

**Liliana Mâţiu-Iovan**

Facultad de Electrónica, Telecomunicaciones e Información, Tecnologías Politehnica University of Timisoara, Timisoara, Rumania

**Gabriel GăŠpăresc**

Facultad de Electrónica, Telecomunicaciones e Información, Tecnologías Politehnica University of Timisoara, Timisoara, Rumania

**Fecha y lugar de publicación:**

*Fecha:* 8-9 de noviembre de 2018 en la conferencia International Symposium on Electronics and Telecommunications (ISETC)

Este artículo guarda relación con el trabajo de investigación, ya que aunque es diferente la utilizacion es un circuito que recibe la voz como entrada del circuito y como es un buscador devolverá un resultado que seria la salida de datos.

**2. SMARISA: un anillo inteligente basado en Raspberry Pi para la seguridad de las mujeres con IOT**

SMARISA es un anillo que se compone de Raspberry Pi Zero, cámara Raspberry Pi, timbre y botón para activar los servicios, sirve para todas las mujeres de todos los ámbitos de la vida  pues constantemente luchan por estar a salvo y protegerse de la mirada errante de los hombres insensibles que abusan, asaltan y violan la dignidad de las mujeres a diario. ya que exiten muy pocos sitios seguros y debido a estas atrocidades a las que están sometidas las mujeresse propone un wearable de seguridad inteligente para mujeres basado en Internet of Things.  Este dispositivo es extremadamente portátil y puede ser activado por la víctima al ser asaltada con solo hacer clic en un botón que buscará su ubicación actual y también capturará la imagen del atacante a través de la cámara Raspberry Pi. La ubicación y el enlace de la imagen capturada se enviarán a los números de contacto de emergencia predefinidos o a la policía a través del teléfono inteligente de la víctima, lo que evitará el uso de dispositivos / módulos de hardware adicionales y hará que el dispositivo sea compacto.

**Autores:**

**Navya R Sogi**

Departamento de Ciencia e Ingeniería de la Información, Facultad de Ingeniería Dayananda Sagar, Bangalore, India

**Priya Chatterjee**

Departamento de Ciencia e Ingeniería de la Información, Facultad de Ingeniería Dayananda Sagar, Bangalore, India

**U Nethra**
Departamento de Ciencia e Ingeniería de la Información, Facultad de Ingeniería Dayananda Sagar, Bangalore, India

**V Suma**

Departamento de Ciencia e Ingeniería de la Información, Facultad de Ingeniería Dayananda Sagar, Bangalore, India

**Fecha y lugar de publicación:**

*Fecha:* 11-12 de julio de 2018 en la conferencia International Conference on Inventive Research in Computing Applications (ICIRCA)

Este anillo al igual que el presente circuito presenta entradas que vendría hacer las pulsaciones de cada mujer y las salidas serian los avisos que le llegan a cada familiar o policia de la victima por lo cual tienen relacion ya que son circuitos de entrada y salida.


**3. Sistema de identificación y conteo de personas mediante raspberry Pi (AU-PiCC: mostrador de clientes de Raspberry Pi)**

El trabajo de este documento se centra en una implementación de OpenCV en un sistema integrado como Raspberry Pi para crear una mini estación independiente para contar personas. La característica clave de AU-PiCC (Contador de clientes raspberry Pi de Assumption University) es contar una cantidad de personas interesadas en el producto de destino en un área predefinida junto con una identificación facial simple para evitar contar duplicados. Los resultados experimentales muestran que este sistema basado en Raspberry Pi se puede utilizar como una simple estación de contador de personas.

**Autores:**

**Tussanai Parthornratt**

Universidad de la Asunción, Escuela de Ingeniería Vincent Mary (VME), Departamento de Telecomunicaciones y Electrónica, Bangsaothong, Samutprakarn, Tailandia

**Natchaphon Burapanonte**

Universidad de la Asunción, Escuela de Ingeniería Vincent Mary (VME), Departamento de Telecomunicaciones y Electrónica, Bangsaothong, Samutprakarn, Tailandia

**Wisarute Gunjarueg**

Universidad de la Asunción, Escuela de Ingeniería Vincent Mary (VME), Departamento de Telecomunicaciones y Electrónica, Bangsaothong, Samutprakarn, Tailandia

**Fecha y lugar de publicación:**

*Fecha:* 27-30 de enero de 2016 en la conferencia Internacional de Electrónica, Información y Comunicaciones 2016 (ICEIC)

Este sistema tiene relación con el presente trabajo especfícamente con el circuito contador, ya que si bien este tiene un sitema más avanzado en escencia tiene el mismo objetivo contabilizar algo con ayuda de la Raspberri Pi lo cual vendría hacer un circuito que muestra la salida de datos que sería el numero de personas contabilizadas.


### 4. MARCO TEÓRICO

**¿Qué es la Raspberry Pi?**

Raspberry Pi es un ordenador de limitadas dimensiones y precio que está destinado principalmente al desarrollo de pequeños prototipos y a estimular la enseñanza de las ciencias de la computación en los centros educativos. Desarrollado en hardware libre cuenta con sistemas operativos GNU/Linux como Raspbian, aunque se pueden encontrar otros sistemas operativos optimizados para el hardware de la Raspberry Pi. ( Asociación Programo Ergo Sum, s.f.)

**Hardware y software de la Raspberry Pi**

|**Hardware**|**Software**	|    
|-------|-----------------------------|
|Es un producto con propiedad registrada, pero de uso libre. De esa forma la Fundación Raspberry Pi mantiene el control de la plataforma, pero permitiendo su uso libre tanto a nivel educativo como particular. Raspberry Pi utiliza una arquitectura para el procesador ARM la cual es de tipo RISC (Reduced Instruction Set Computer), es decir, utiliza un sistema de instrucciones realmente simple lo que le permite ejecutar tareas con un mínimo consumo de energía|El software es open source siendo su sistema operativo oficial una versión adaptada de la distribución Debian, denominada Raspbian, aunque permite usar otros sistemas operativos, incluido una versión de Windows 10 IoT Core. La fundación da soporte para las descargas de las distribuciones para arquitectura ARM |
  
( Asociación Programo Ergo Sum, s.f.)

**Modelos de Raspberry Pi**

Actualmente existen dos modelos de Raspberry Pi. El más popular es el Modelo B, que viene con procesador ARM 1176JZF-S a 700 MHz, dos puertos USB 2.0 y Ethernet, siendo el resto de sus características las mismas que os hemos avanzado al principio de este artículo.

![Modelo B Raspberry Pi](https://github.com/JorgeGallegos99/Trabajo-de-investigacion-3/blob/master/Img/ModelB.PNG)

**Figura 1. Modelo B Raspberry Pi**

Por su parte, el Modelo A es más asequible, pero prescinde de uno de los dos puertos UB y no tiene capacidad para conectarse a Internet. Asimismo, en su última revisión el Modelo B incluye 512 Mbytes de memoria RAM, existiendo versiones más antiguas con solo 256 Mbytes. 
(ComputerHoy, 2014)

![Modelo A Raspberry Pi](https://github.com/JorgeGallegos99/Trabajo-de-investigacion-3/blob/master/Img/ModelA.PNG)

**Figura 2. Modelo A Raspberry Pi**

**Node.js**

Node.js es un entorno en tiempo de ejecución multiplataforma, de código abierto basado en el lenguaje de programación JavaScript, asíncrono, con Entrada/Salida de datos en una arquitectura orientada a eventos y basado en el motor V8 de Google. 

![Node](https://github.com/JorgeGallegos99/Trabajo-de-investigacion-3/blob/master/Img/Node.PNG)

**Figura 3. Node js**

Fue creado por Ryan Dahl en 2009 con el enfoque de ser útil en la creación de programas de red altamente escalables, como por ejemplo, servidores web.y su evolución está apadrinada por la empresa Joyent, que además tiene contratado a Dahl en plantilla.
Node.js fue creado por los desarrolladores originales de JavaScript. Lo transformaron de algo que solo podía ejecutarse en el navegador en algo que se podría ejecutar en los ordenadores como si de aplicaciones independientes se tratara. Gracias a Node.js se puede ir un paso más allá en la programación con JavaScript no solo creando sitios web interactivos, sino teniendo la capacidad de hacer cosas que otros lenguajes de secuencia de comandos como Python pueden crear.
Node es un es un entorno en tiempo de ejecución multiplataforma de código abierto. En el desarrollo web es común verlo como la capa de un servidor que utiliza JS. El que sea de código abierto ha hecho posible instalarlo en una Raspberry Pi. Por otra parte, la gran comunidad que existe se ha encargado de generar una cantidad impresionante de paquetes a un nivel tal, que el manejador de paquetes de Nodejs es el registro de software más grande del mundo.
(OpenJS Foundation, s.f.)

**JavaScript**
JavaScript (JS) es un lenguaje de programación interpretado, dialecto del estándar ECMAScript. Se define como orientado a objetos,  basado en prototipos, imperativo, débilmente tipado y dinámico.

![Java](https://github.com/JorgeGallegos99/Trabajo-de-investigacion-3/blob/master/Img/Java.PNG)

**Figura 4. JavaScript**

JavaScript por sí solo es bastante compacto, aunque muy flexible, y los desarrolladores han escrito gran cantidad de herramientas encima del núcleo del lenguaje JavaScript, desbloqueando una gran cantidad de funcionalidad adicional con un mínimo esfuerzo. Esto incluye:
* Interfaces de Programación de Aplicaciones del Navegador (APIs) — APIs construidas dentro de los navegadores que ofrecen funcionalidades como crear dinámicamente contenido HTML y establecer estilos CSS, hasta capturar y manipular un vídeo desde la cámara web del usuario, o generar gráficos 3D y muestras de sonido.
* APIs de terceros, que permiten a los desarrolladores incorporar funcionalidades en sus sitios de otros proveedores de contenidos como Twitter o Facebook.
* Marcos de trabajo y librerías de terceros que puedes aplicar a tu HTML para que puedas construir y publicar rápidamente sitios y aplicaciones.
(Mozilla web docs, 2020)

**Librería GPIO**

**Pines GPIO**
Es un sistema de entrada y salida de propósito general, es decir, consta de una serie de pines o conexiones que se pueden usar como entradas o salidas para múltiples usos. Estos pines están incluidos en todos los modelos de Raspberry Pi.

![Librería GPIO](https://github.com/JorgeGallegos99/Trabajo-de-investigacion-3/blob/master/Img/GPIO.PNG)

**Figura 5. Librería GPIO**

Existen 2 formas de numerar los pines de la Raspberry Pi, en modo GPIO o en modo BCM.
* En el modo GPIO, los pines se numeran de forma física por el lugar que ocupan en la placa (representados por el color gris) viene siendo igual para todas las versiones (comenzamos a contar desde arriba a la izquierda y finalizamos abajo a la derecha).
* En el modo BCM, los pines se numeran por la correspondencia en el chip Broadcom (que es la CPU de la Raspberry Pi).

![Pines GPIO](https://github.com/JorgeGallegos99/Trabajo-de-investigacion-3/blob/master/Img/PinesGPIO.PNG)

**Figura 6. Pines GPIO**

### 5. DIAGRAMAS

**5.1 Diagramas de Bloques**

Diagrama de funcionamiento del Circuito de Entrada de datos.

![Diagrama_1.PNG](https://github.com/JorgeGallegos99/Trabajo-de-investigacion-3/blob/master/Img/Diagrama_1.PNG)

**Figura 7. Circuito 1**

Diagrama de funcionamiento de los Circuitos de Salida de datos.

![Diagrama_2.PNG](https://github.com/JorgeGallegos99/Trabajo-de-investigacion-3/blob/master/Img/Diagrama_2.PNG)

**Figura 8. Circuito 2 **

![Diagrama_3.PNG](https://github.com/JorgeGallegos99/Trabajo-de-investigacion-3/blob/master/Img/Diagrama_3.PNG)

**Figura 9. Circuito 3 **

**5.2 Diagramas de flujo**

De forma general se presenta el diagrama de flujo para el circuito 1 y 3 centrandose en el ciclo **While**

![D_Flujo.PNG](https://github.com/JorgeGallegos99/Trabajo-de-investigacion-3/blob/master/Img/D_Flujo.PNG)

**Figura 10. Circuitos 1 y 3**

Para el Circuito 2 se presenta el diagrama de flujo de forma general especificando el ciclo **For**

![D_Flujo1.PNG](https://github.com/JorgeGallegos99/Trabajo-de-investigacion-3/blob/master/Img/D_Flujo1.PNG)

**Figura 11. Circuito 2**

**5.3 Diagrama de Pines en RaspBerry Pi**

![RaspberryPi.png](https://github.com/JorgeGallegos99/Trabajo-de-investigacion-3/blob/master/Img/RaspberryPi.png)

**Figura 12. Pines en Raspberry Pi**

### 6. LISTA DE COMPONENTES

EL principal componente para el disieño del circuito fue la **Raspberry PI.**

En la Tabla 1 se muestra las herramientas  de software usadas para la simulacion del circuito se utilizó un simulador y la plataforma para la implementación.

**Tabla 1: Herramientas de Software usadas para el diseño de los 3 circuitos.**


   |     **Herramientas de Software**      |                 
   |---------------------------------------|
   |           Wiliodrin.studio.           | 

   
**Tabla 2: Componentes electronicos del Circuito de Entrada y salida **

  | **N°** |**Componentes Electronicos**	|    
   |-------|-----------------------------|
   |     1 |   Raspberry                 |
   |     1 |   Pulsador                  |    
   |     9 |   leds                  |     
 
### 7. MAPA DE VARIABLES

 |**Variable** | 	**Tipo**   | **Descripción**|
 |-------------|----------------|-------------------|
 |led, ledRed,ledYellow, ledGreen|  Salida| Variables de salida que se crean con el objetico de controlar los pines GPIO de la raspberry|
 |Boton| Entrada|	Variable que permite controlar los pines GPIO de la raspberry con el objetivo de recibir los datos ingresados por el usuario |
 |i,j	| Variables de control de estructura |Variables que permiten controlar los ciclos repetitivos|
 |Gpio	  | Paquete	|Varible a traz de la cual obtenemos el control de los pines Gpio de la Raspberry pi|


### 8. EXPLICACIÓN DEL CÓDIGO FUENTE

**Circuito de Entrada de Datos**

![](https://github.com/JorgeGallegos99/Trabajo-de-investigacion-3/blob/master/Img/fc1.PNG)

**Figura 13.** Circuito 1 entrada de Datos

![](https://github.com/JorgeGallegos99/Trabajo-de-investigacion-3/blob/master/Img/fc2.PNG)

**Figura 14.** Código de Circuito 1 entrada de Datos

Este circuito nos permite ver un Diodo LED parpadeando indefinidamente en intervalos de 1 segundo hasta cuando presionamos el botón del pulsador.

Creamos un objeto al cual le asignamos el paquete que vamos a usar, para poder controlar los pines de la raspberry debemos usar la librería "onoff" (linea 1)

Creamos tantos objetos como elementos electronicos tengamos e inicializamos los mismos mandando como parametro el pin GPIO al cual esta conectado el elemento ademas debemos indicar el flujo de datos de cada elemento (entrada - in, salida - out), para nuestro ejemplo el LED representa el flujo de salida de datos y el pulsador el flujo de entrada de datos.(Linea 3, Linea 4)

**CICLO WHILE**

Como sabemos el ciclo while es una estructura repetitiva que se ejecuta indefinidamente mientras una cierta condicion sea verdadera, cuando esta condicion sea falsa se rompe el ciclo. (Linea 8)

La condicion que definimos es que mientras no oprimamos el boton del pulsador (Linea 8), es decir la variable boton tiene guadado un valor de "0", el ciclo se sigue ejecutando y el LED sigue parpadeando indefinidamente(Linea 9 enciende el LED, Linea 10 permanece 1 segundo encendido ,Linea 11 Apaga el LED), cuando pulsamos el botón le asignamos el valor de "1" a la variable boton haciendo que el ciclo while se rompa y termine la ejecucion del programa. 

**Circuito de salida de datos**

En circuito fue configurado con la idea de simular el funcionamiento de un semaforo en estado normal y en estado preventivo.
Los diodos Led se encienden de igual forma que un semaforo y cada LED permanece encendido durante 3 segundo, luego se apaga y se enciende el siguiente LED. Este proceso se repite 2 veces. 
Posteriormente luego de haber funcionado como un semáforo en estado normal el cirucito el circuito simula el comportamiento de un semaforo en estado preventivo, es decir, parpadea solo el led de color amarrillo 5 veces y finaliza la ejecucion del programa.


![](https://github.com/JorgeGallegos99/Trabajo-de-investigacion-3/blob/master/Img/fc3.PNG)

**Figura 15.** Circuito de salida de datos


![](https://github.com/JorgeGallegos99/Trabajo-de-investigacion-3/blob/master/Img/fc4.PNG)

**Figura 16.** Codigo del Circuito 2 de salida de datos

Empezamos creando un objeto que nos permite controlar los pines de la raspberry al cual le asignamos el paquete "onoff" como se hizo en el ejemplo anterior. (Linea 1)

Creamos 3 objetos de tipo Gpio uno para cada LED y le asignamos los pines de la raspberry a los cuales estan conetados. En este caso particular todos los elementos del circuito cumplen la funcion de salida de datos. (Linea 2,3,4)

**CICLO FOR**

Como sabemos el ciclo for es una estructura repetitiva controlada. 
En el primer for nuestro semáfono esta configurado en estado normal. (Linea 6)

Impimimos un mensaje que nos indica que la simulación comenzó (linea 7)
Encendemos el Led rojo (linea 8)
Con la función sleep hacemos que el Led permanezca encendido durante 3 segundos (linea 9)
Apagamos el Led rojo (linea 10)

Repetimos el mismo procedimiento con los otros dos diodos LED.

Al tener este bloque de codigo dentro del ciclo for programamos la raspberry para que realice esta configuración de nuestro semáforo 2 veces.

Luego de haber ejecutado el bloque de codigo 2 veces el primer siclo for finaliza y se ejecuta el segundo ciclo for en el cual configuramos a nuestro semaforo en estado preventivo. 
Imprimimos un mensaje que nos permite indentificar que el ciclo for inició (linea 20)
Encendemos el Led amarillo (linea 21)
Con la funcion sleep hacemos que el Led permanezca encendido durante 1 segundos (linea 22)
Apagamos el Led (linea 23)
De nuevo con la funcion sleep hacemos que el Led permanezca apagado durante 1 segundo.
Gracias al ciclo for este bloque de codigo se repite 5 veces.
Posteriormente finaliza la ejecución del programa.

### 9. DESCRIPCIÓN DE PRERREQUISITOS Y CONFIGURACIÓN

En el circuito para realizar la conexión  tanto de las entradas como de las salidas de los circuitos se hace uso de el simulador en línea WyliodrinStudio que permite trabajar en linea o descargarse en el equipo para trabajar con el.


![Studio.PNG](https://github.com/JorgeGallegos99/Trabajo-de-investigacion-3/blob/master/Img/Studio.PNG)

**Figura 17.** Simulador de WyliodrinStudio

Tienen diferentes características, entre ellas la que nos interesa es que es compatible con RaspBerry pi.

![Caracteristicas.PNG](https://github.com/JorgeGallegos99/Trabajo-de-investigacion-3/blob/master/Img/Caracteristicas.PNG)

**Figura 18.** Caracteristicas de WyliodrinStudio


 |**Caracteristicas | Descripción**|
 |-------------|-------------|
 |  **Notebook**| un tutorial interactivo sobre cómo crear la aplicación| 
 |**Aplicación** |escriba el código en su idioma visual o de texto favorito| 
 |**Panel de control** |visualizar señales de datos	|
 |**Esquemas**  |cargue los esquemas de su proyecto|
 |**Administrador de archivos**| cree nuevas carpetas y archivos según lo necesite|
 |**Shell**  |Utilice comandos avanzados para tener un control total sobre sus dispositivos. El caparazón le permite controlar cualquier dispositivo remoto como si estuviera conectado a su teclado.|
 |**Administración**|conéctese fácilmente a Internet y / o instale / elimine bibliotecas|
 |**Simuladores** |ejecute aplicaciones sin un dispositivo real|
 |**Emuladores** | ¿aún no tienes una Raspberry Pi? , el emulador te permite ejecutar todos los proyectos usando tu computadora.|


### 10. APORTACIONES



**Figura 19.** 

**Figura 20.** 

### 11. CONCLUSIONES

• La visualización de entrada y salida de datos es posible y sencilla de explicar por medio de un circuito de prueba junto con diodos leds y dispositivos de ingreso de datos como lo es un pulsador.	
* La Raspberry posee un gran campo de aplicaciones con distintos niveles de dificultad, pero accesibles a múltiples usos predeterminados, por lo que nos permitió crear circuitos tanto de entrada y salida de datos.
•	Mediante la programación de la Raspberry Pi  mediante la libreria GPIO de Javascript  para el control entrada y salida de datos y de la y adaptación a circuitos establecidos  se pudo crear los tres circuitos.
* Las diferentes pestañas que posee el simulador Wyliodrin studio facilitan la Programación de laS Raspberry PI y las plantillas la contruccion de los circuitos.

### 12. RECOMENDACIONES

* Tener en cuenta el flujo de datos que quqeremos que reciba la Raspberry Pi.
* Es necesario tener en cuenta donde estan ubicado y que numeración tiene cada pin en la Raspberry Pi para realizar debidamente la programación.
* Tener en cuenta la estructura de las funciones logicas de Javascript para obtener el funcionamiento adecuado de los circuitos.
* Pese a que se puede descargar la aplicación es preferible trabajar con el simulador en linea ya que se requiere de un modulo, y al no tener mucha informacion sobre la plataforma no se sabe cual es el modulo correcto.


### 13. CRONOGRAMA

![Cronograma](https://github.com/JorgeGallegos99/Trabajo-de-investigacion-3/blob/master/Img/Cronograma.PNG)

**Figura 21.** Cronograma en Monday


### 14. BIBLIOGRAFÍA

Asociación Programo Ergo Sum. (s.f.). Programo Ergo Sum. 

      Obtenido de https://www.programoergosum.com/cursos-online/raspberry-pi/232-curso-de-introduccion-a-raspberry-pi/que-es-raspberry-pi
    
ComputerHoy. (23 de enero de 2014). CH. 

    Obtenido de https://computerhoy.com/noticias/hardware/que-es-raspberry-pi-donde-comprarla-como-usarla-8614
 
Mozilla web docs. (17 de Agosto de 2020). Mozilla web docs. 
 
    Obtenido de https://developer.mozilla.org/es/docs/Learn/Getting_started_with_the_web/JavaScript_basics
    
OpenJS Foundation. (s.f.). OpenJS Foundation. 

    Obtenido de https://nodejs.org/es/about/

### 15. ANEXOS

**15.1.  MANUAL DE USUARIO**

1. Ingresamos a la direccion https://beta.wyliodrin.studio/

2.Damos clic en salida

![](https://github.com/JorgeGallegos99/Trabajo-de-investigacion-3/blob/master/Img/fm1.PNG)

**Figura 22.** Botón de Salida

3. Damos clic en proyects library 

![](https://github.com/JorgeGallegos99/Trabajo-de-investigacion-3/blob/master/Img/fm2.PNG)

**Figura 23.** Inicio del Proyecto

4. Damos clic en crear una nueva aplicación

![](https://github.com/JorgeGallegos99/Trabajo-de-investigacion-3/blob/master/Img/fm3.PNG)

**Figura 24.** Creación de la aplicación

5. Asignamos el nombre de nuestra aplicación y elegimos el lenguje que vamos a utilizar y damos clic en el boton Create Procjet, actualmente la plataforma solo funciona con Node JS

![](https://github.com/JorgeGallegos99/Trabajo-de-investigacion-3/blob/master/Img/fm4.PNG)

**Figura 25.** Elección del Lenguaje

6. En la pantalla que se despliega damos clic en el proyecto creado.

![](https://github.com/JorgeGallegos99/Trabajo-de-investigacion-3/blob/master/Img/fm5.PNG)

**Figura 26.** Click sobre el proyecto Creado

7. Dependiendo del circuito que queramos utilizar copiamos el codigo de la carpeta "Codigo Fuente" y lo pegamos en la pestaña aplicacion.

![](https://github.com/JorgeGallegos99/Trabajo-de-investigacion-3/blob/master/Img/fm11.PNG)

**Figura 27.** Pestaña Aplicación

8. Damos clic en conectar y seleccionamos RaspberryPi

![](https://github.com/JorgeGallegos99/Trabajo-de-investigacion-3/blob/master/Img/fm6.PNG)

**Figura 28.** Botón Conectar

![](https://github.com/JorgeGallegos99/Trabajo-de-investigacion-3/blob/master/Img/fm7.PNG)

**Figura 29.** Elección de RaspBerry PI 

9. En la pestaña **Raspberry Pi Simulator** elegimos el circuto predeterminado por la plataforma que este acorde al codigo que copiamos.

![](https://github.com/JorgeGallegos99/Trabajo-de-investigacion-3/blob/master/Img/fm8.PNG)

**Figura 30.** Pestaña Raspberry Pi Simulator

![](https://github.com/JorgeGallegos99/Trabajo-de-investigacion-3/blob/master/Img/fm9.PNG)

**Figura 31.** Pestaña Led

![](https://github.com/JorgeGallegos99/Trabajo-de-investigacion-3/blob/master/Img/fm10.PNG)

**Figura 32.** Plantillas de Wyliodrin Studio

10. Damos clic en el signo de play y comenzara la simulacion

![](https://github.com/JorgeGallegos99/Trabajo-de-investigacion-3/blob/master/Img/fm12.PNG)

**Figura 33.** Botón Play

11. Para el caso del cirucito que tiene el pulsador, el Diodo Led permanecera intermitente hasta que presionemos el boton del pulsador, cuando lo hagamos la simulacion se dentendrá para volver a hacer que el circuito funcione es necesario volver a iniciar la simulación.

![](https://github.com/JorgeGallegos99/Trabajo-de-investigacion-3/blob/master/Img/fm14.PNG)

**Figura 34.** Circuito 1

12. Para el caso del circuito usado para simular el comportamiento del semáforo solo es necesario iniciar la simulacion cuando se acaben los ciclos for el programa finalizara la ejecucion por si solo.

![](https://github.com/JorgeGallegos99/Trabajo-de-investigacion-3/blob/master/Img/fm13.PNG)

**Figura 35.** Circuito 2
