# Trabajo-de-investigacion-3

## Informe

### 1. PLANTEAMIENTO DEL PROBLEMA



### 2. OBJETIVOS

#### General

Diseñar un circuito que permita la entrada y salidas de datos en una Raspberry Pi, para la implementación se utilizará el simulador virtual  Wiliodrin.studio.

#### Especifícos
 
* Crear un circuito que permita la entrada y la salida de datos en una RaspBerry Pi.
* Conocer la estructura de la Raspberry Pi, el funcionamiento y como utilizarla en circuitos digitales.
* Investigar las instrucciones básicas de la librería GPIO de Javascript  para el control entrada y salida de datos de la Raspberry pi utilizando el simulador onlineWiliodrin.studio. 
* Describir los principales componentes que facilita el simulador Wiliodrin.studio.


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

**Figura. Modelo B Raspberry Pi **

Por su parte, el Modelo A es más asequible, pero prescinde de uno de los dos puertos UB y no tiene capacidad para conectarse a Internet. Asimismo, en su última revisión el Modelo B incluye 512 Mbytes de memoria RAM, existiendo versiones más antiguas con solo 256 Mbytes. 
(ComputerHoy, 2014)

![Modelo A Raspberry Pi](https://github.com/JorgeGallegos99/Trabajo-de-investigacion-3/blob/master/Img/ModelA.PNG)

**Figura. Modelo A Raspberry Pi **

**Node.js**

Node.js es un entorno en tiempo de ejecución multiplataforma, de código abierto basado en el lenguaje de programación JavaScript, asíncrono, con Entrada/Salida de datos en una arquitectura orientada a eventos y basado en el motor V8 de Google. 

![Node](https://github.com/JorgeGallegos99/Trabajo-de-investigacion-3/blob/master/Img/Node.PNG)

**Figura. Node js**

Fue creado por Ryan Dahl en 2009 con el enfoque de ser útil en la creación de programas de red altamente escalables, como por ejemplo, servidores web.y su evolución está apadrinada por la empresa Joyent, que además tiene contratado a Dahl en plantilla.
Node.js fue creado por los desarrolladores originales de JavaScript. Lo transformaron de algo que solo podía ejecutarse en el navegador en algo que se podría ejecutar en los ordenadores como si de aplicaciones independientes se tratara. Gracias a Node.js se puede ir un paso más allá en la programación con JavaScript no solo creando sitios web interactivos, sino teniendo la capacidad de hacer cosas que otros lenguajes de secuencia de comandos como Python pueden crear.
Node es un es un entorno en tiempo de ejecución multiplataforma de código abierto. En el desarrollo web es común verlo como la capa de un servidor que utiliza JS. El que sea de código abierto ha hecho posible instalarlo en una Raspberry Pi. Por otra parte, la gran comunidad que existe se ha encargado de generar una cantidad impresionante de paquetes a un nivel tal, que el manejador de paquetes de Nodejs es el registro de software más grande del mundo.
(OpenJS Foundation, s.f.)

**JavaScript**
JavaScript (JS) es un lenguaje de programación interpretado, dialecto del estándar ECMAScript. Se define como orientado a objetos,  basado en prototipos, imperativo, débilmente tipado y dinámico.

![Java](https://github.com/JorgeGallegos99/Trabajo-de-investigacion-3/blob/master/Img/Java.PNG)

**Figura. JavaScript**

JavaScript por sí solo es bastante compacto, aunque muy flexible, y los desarrolladores han escrito gran cantidad de herramientas encima del núcleo del lenguaje JavaScript, desbloqueando una gran cantidad de funcionalidad adicional con un mínimo esfuerzo. Esto incluye:
* Interfaces de Programación de Aplicaciones del Navegador (APIs) — APIs construidas dentro de los navegadores que ofrecen funcionalidades como crear dinámicamente contenido HTML y establecer estilos CSS, hasta capturar y manipular un vídeo desde la cámara web del usuario, o generar gráficos 3D y muestras de sonido.
* APIs de terceros, que permiten a los desarrolladores incorporar funcionalidades en sus sitios de otros proveedores de contenidos como Twitter o Facebook.
* Marcos de trabajo y librerías de terceros que puedes aplicar a tu HTML para que puedas construir y publicar rápidamente sitios y aplicaciones.
(Mozilla web docs, 2020)

**Librería GPIO**

**Pines GPIO**
Es un sistema de entrada y salida de propósito general, es decir, consta de una serie de pines o conexiones que se pueden usar como entradas o salidas para múltiples usos. Estos pines están incluidos en todos los modelos de Raspberry Pi.

![Librería GPIO](https://github.com/JorgeGallegos99/Trabajo-de-investigacion-3/blob/master/Img/GPIO.PNG)

**Figura. Librería GPIO**

Existen 2 formas de numerar los pines de la Raspberry Pi, en modo GPIO o en modo BCM.
*En el modo GPIO, los pines se numeran de forma física por el lugar que ocupan en la placa (representados por el color gris) viene siendo igual para todas las versiones (comenzamos a contar desde arriba a la izquierda y finalizamos abajo a la derecha).
*En el modo BCM, los pines se numeran por la correspondencia en el chip Broadcom (que es la CPU de la Raspberry Pi).

![Pines GPIO](https://github.com/JorgeGallegos99/Trabajo-de-investigacion-3/blob/master/Img/PinesGPIO.PNG)

**Figura. Pines GPIO**

### 5. DIAGRAMAS



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
   |1      |   Raspberry                 |
   |     1 |   Pulsador                  |    
   |     6 |   leds                  |     
 
### 7. MAPA DE VARIABLES

 |**Variable** | 	**Tipo**   | **Descripción**|
 |-------------|----------------|-------------------|
 |A0,A1,A2,A3,A4,A5,A6,A7|  Entrada|Son los bits de Entrada del numero A donde A7 es el bit mas significativo y A0 es el bit menos significativo|
 |B0,B1,B2,B3,B4,B5,B6,B7| Entrada|	Son los bits de Entrada del numero B donde B7 es el bit mas significativo y B0 es el bit menos significativo|
 |S0,S1,S2,S3,S4,S5,S6,S7	| Salida|Son los bits de Salida del resultado de la suma donde S7 es el bit mas significativo y S0 es el bit menos significativo|
 |Ci	  | Entrada	|Acarreo de entrada|
 |CO	  |Salida	  |Acarreo de SalidaSalida|

### 8. EXPLICACIÓN DEL CÓDIGO FUENTE


### 9. DESCRIPCIÓN DE PRERREQUISITOS Y CONFIGURACIÓN



### 10. APORTACIONES



### 11. CONCLUSIONES


### 12. RECOMENDACIONES



### 13. CRONOGRAMA

![Cronograma](https://github.com/JorgeGallegos99/Trabajo-de-investigacion-3/blob/master/Img/Cronograma.PNG)

### 14. BIBLIOGRAFÍA


### 15. ANEXOS

**15.1.  MANUAL DE USUARIO**
