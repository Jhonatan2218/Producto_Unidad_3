# Producto_Unidad_3
Integrantes: Javier Arteaga, Bryan Azuero, Jhonatan Tituaña
 ### 1 PLANTEAMIENTO DEL PROBLEMA
 
En el siguiente informe se dará a conocer los conceptos aprendidos en el curso de Arquitectura de computadoras aplicando todos lo aprendido de Programación orientada a objetos, en la implementación de una ejecución que será ejecutado en un simulador de Raspberry PI. El lenguaje de programación Python tiene muchas ventajas para su sintaxis sencilla y su modo interactivo hace que éste sea ideal para la enseñanza. El combinar Python con un enfoque orientado a objetos hace que los estudiantes se sientan motivados. La mayoría estamos en contacto con un equipo de computación ocupando aplicaciones y programadas que facilitan la realización de nuestras actividades diarias. Es importante que es la programación orientada a objetos, conocer el paradigma de programación que más se utiliza en la actualidad. Esta práctica está destinada a explicar el desarrollo de un circuito de riego automático y un circuito para activar la alarma de incendios. Para ejecutar nuestro programa necesitaremos la ayuda de un si simulador de la Raspberry PI, ya que en ella se establecerá una función que permita la selección de las operaciones matemáticas por medio de la lectura de los puertos virtuales.

### 2 OBJETIVOS

### Objetivo general.

Desarrollar un sistema de riego automático y la alarma de incendios utilizando el lenguaje de programación Python y seleccione las operaciones por medio de la lectura de los puertos virtuales de una Raspberry PI.

### Objetivos específicos.

Comprender todos los conceptos más básicos de programación orientada a objetos y el uso de las librerías.

Comprender, seleccionar y aplicar los conceptos fundamentales aprendidos en el lenguaje de programación en Python.

### 3.	ESTADO DEL ARTE

### Smart Home

Los sistemas de automatización que se colocan en una vivienda para controlar todos los servicios relacionados con la energía, se denominan domótica. Término que significa en latín casa automática. Muchos de estos sistemas están entrelazados entre si dentro o fuera del hogar, beneficiándonos en las comunicaciones y en una gama de servicios eléctricos que tenemos a nuestra disposición en casa. Esta tecnología representa una gran ventaja, porque nos facilita el uso de la diversidad de aparatos eléctricos de una manera eficaz y rápida.
En el artículo elaborado por Miguel F. Arriaga-Gomez , Ignacio de Mendizabal-Vazquez, Rodrigo Ros-Gomez, Carmen Sanchez- ´ Avila en el año 2014, nos señala que un sistema de alarma es conjunto de elementos que tienen la facultad de detectar, censar, discriminar y avisar cualquier evento de una edificación sea en ambientes internos como externos por medio de una comunicación telefónica, radio, celular o IP y acompañado de un sonido emitido por una sirena en cuestión de minutos así este sistema permite reacción tanto local como reacción de un operador de seguridad como la policía, la empresa de seguridad que le presta el servicio de monitoreo, un vecino o los mismos afectados. [1]
En la actualidad los avances computacionales y electrónicos han aumentado las aplicaciones en comportamientos semi-inteligentes, que se emplean en sistemas de casas inteligentes. Se supone que una casa inteligente es la que está fresca en verano y caliente en invierno, la que ahorra energía, y la que en general obedece las órdenes del usuario. La domótica, por su parte trata de hacer inteligentes a las casas y edificios, empleando un conjunto de sistemas que automatizan y controlan las instalaciones del hogar. En la domótica, los dispositivos que se encuentran integrados en la red de control aportan un confort, seguridad y ahorro de energía en la casa.

###  Smart Agro.

El concepto ‘Smart Agro’ es básicamente la consecuencia de la irrupción de las TIC. De una revolución digital que trae consigo una transformación de la industria agroalimentaria, agrícola, ganadera, pesquera, rural y forestal, entre otras. El uso combinado de robótica, geoposicionamiento y análisis Big Data, ha consolidado procedimientos válidos para combatir el derroche de agua y el exceso de la aplicación de productos agroquímicos y fertilizantes. Es decir, la monitorización, actuación en tiempo real y visualización georreferenciada de datos de los activos del campo desarrollando nuevos modelos de negocio, para mejorar los procesos operativos y ahorrar costes del campo, haciendo de él, un campo inteligente. Para Ruby Roselin  y Dr A Jawahar nos presentan en su informe titulado” Sistema agrícola inteligente que utiliza redes de sensores inalámbricos” no existe una definición única para este concepto, sí podemos asociarlo con la mecanización de procesos en el agro que permitan, por un lado, reducir costos y, por otro, aumentar la productividad de los cultivos. Sin embargo, para lograr avanzar en materia de innovación y tecnología, que permita efectivamente mejorar los procesos y aumentar la productividad del sector, se necesita más que un simple deseo. [2]

### 4.MARCO TEÓRICO 

### Lógica combinacional

Los elementos que constituyen los circuitos digitales se caracterizan por admitir sólo dos estados. Es el caso por ejemplo de un conmutador que sólo puede estar ENCENDIDO o APAGADO, o una válvula hidráulica que sólo pueda estar ABIERTA o CERRADA. Para representar estos dos estados se usan los símbolos ‘0’ y ‘1’. Se denomina lógica combinacional a todo sistema digital en el que sus salidas son funciones exclusivas del valor de sus entradas en un momento dado, sin que intervengan en ningún caso estados anteriores de las entradas o de las salidas. Las funciones (OR,AND,NAND,XOR) son booleanas (de Boole) donde cada función se puede representar en una tabla de la verdad. Por tanto, carecen de memoria y de retroalimentación.

### Raspberry Pi.
La Raspberry Pi es una computadora en una sola tarjeta (Board Computer) creada por la Raspberry Pi Foundation para promover la enseñanza de la programación en escuelas y países en desarrollo. Python es un lenguaje de programación de alto nivel, interpretado, con variables con tipo de datos dinámico. Permite programar usando los paradigmas de programación imperativa, orientada a objetos o funcional y se puede extender fácilmente por medio de módulos escritos en C o C++. La Raspberry Pi se puede usar en proyectos de electrónica y para tareas básicas que haría cualquier ordenador de sobremesa como navegar por internet, hojas de cálculo, procesador de textos, reproducir vídeo en alta definición e incluso jugar a ciertos juegos.Al utilizar Python en la Raspberry Pi tenemos la ventaja de poder utiliza los pines GPIO para conectar el mundo digital con el mundo físico mediante la electrónica y programación.

### Puertos Virtuales GPIO.

General Purpose Input Output (GPIO) es un sistema de entrada y salida de propósito general, es decir, consta de una serie de pines o conexiones que se pueden usar como entradas o salidas para múltiples usos. Estos pines están incluidos en todos los modelos de Raspberry Pi, aunque con diferencias. GPIO mientras que a partir de la versión 2 de Raspberry Pi el número de pines aumentó a 40. Sin embargo, la compatibilidad es total, puesto que los 26 primeros pines mantienen su función original. Los pines GPIO tienen funciones específicas (aunque algunos comparten funciones) y se pueden agrupar de la siguiente manera.
