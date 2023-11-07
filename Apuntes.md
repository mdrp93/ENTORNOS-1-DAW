<a name="top"></a>
 
# Apuntes de Entornos de Desarrollo

<p align="center">
   <img width="1000" height="450" src="https://github.com/mdrp93/IMAGENES_ENTORNOS/blob/main/entornos-de-desarrollo-2.jpg">
                                                                                                                  
<p align="left">
   <img src="https://img.shields.io/badge/STATUS-EN%20DESAROLLO-green"></p>

## Apartados:
* [Unidad 1](#item1)
* [Unidad 2](#item2)
* [Unidad 3](#item3)
* [Unidad 4](#item4)

<a name="item1"></a>

# Unidad 1

## Índice unidad 1

* [Introducción: Conceptos básicos](#itemud1)
* [Ciclo de vida del software](#itemud2)
* [Modelos de desarrollo](#itemud3)
* [Lenguajes de programación](#itemud4)
* [Actividades de la unidad](#Itemud5)

<a name="itemud1"></a>

## 1 y 2 Introducción: Conceptos básicos

<p align="justify">
Existen tres tipos de software: de sistema, de aplicación, y de desarrollo.</p>
<p align="justify"><ul><li>En el <b>software de sistema</b> se encuentran el SO., los drivers o controladores de dispositivos (firmware).</li>
<li>En el <b>software de aplicación</b> encontramos suite ofimática, navegadores, editor de imagenes o texto...</li>
<li>Y en el <b>software de desarrollo</b>encontramos editores, compiladores, interpretes..etc</li></ul></li></p>

<p align="right"><img width="360" height="200" src="https://github.com/mdrp93/IMAGENES_ENTORNOS/blob/main/software_apuntes.png"></p>

<p align="justify">En cuanto al hardware tenemos disco duro, memoria RAM, CPU, dispositivos de entrada y salida.</p>

<p align="justify"><ul>
 <li><b>Los dispositivos de entrada y salida:</b> recogen datos desde la entrada y muestran los resultados por la salida.</li>
 <ul>
 <li>La salida es la información que se lee desde la cpu al exterior.</li>
 <li>La entrada es información que se lee del exterior hacia la cpu.</li></ul></li>
 <li><b>Memoria RAM:</b> almacena de manera temporal el código binario de los archivos ejecutables y de los datos que necesita.</li>
 <li><b>CPU ó _Central processing Unit_:</b>lee y ejecuta las instrucciones que se han almacenado en la RAM, y coge analiza los datos necesarios para llevar a cabo las instrucciones.</li>
 <li><b>Disco duro:</b> almacena de manera permanente los arcchivos ejecutables y los archivos de datos. </li></ul></p>

<p align="right"><img width="360" height="200" src="https://github.com/mdrp93/IMAGENES_ENTORNOS/blob/main/hardware.png">

<p align="justify">Hay diferentes tipos de códigos (conceptos):</p>
<ul>
<p align="justify"><li><b>Código fuente:</b>es el código entendible por un ser humano para crear un programa. Permite modificar un programa de manera sencilla. </li></p>
  <p align="justify"><li><b>Código objeto:</b> es un archivo binario, no ejecutable, que se genera a partir del código fuente.</li></p>
  <p align="justify"><li><b>Código ejecutable:</b> es un archivo que se puede ejecutar en el ordenador, y que previamente se han basado en el código fuente.</li></p>
</ul>

<p align="justify">
 > Comentario: En JAVA el código objeto se le llama bytecode.</p>
<p align="justify">El que hace que un código se entienda en una máquina es <b>el compilador</b></p>
<p align="justify">Hay lenguajes compilados y otros que son los lenguajes interpretados que no necesitan ser compilados.</p>
<p align="justify">Por otro lado <b>los scripts</b> son lenguajes que no necesitan ser compilados, se empiezan a ejecutar desde la primera orden o línea. (python, typescrit).</p>
<p align="justify">
> Comentario: Core - Los núcleos permiten llevar diferentes hilos de ejecución independientes.</p>

[Subir](#item1)

<a name="itemud2"></a>

## 3. Ciclo de vida del software. 

<p align="justify">La ingeniería es el ingenio de crear un diseño. Principios y metodologías para desarrollar y mantener el software. Se puede definir cómo la isciplina que estudia los principios y metodologías para el desarrollo y mantenimiento de sistemas software.
Ahora se usa el término desarrollo de software.</p>

### FASES DEL DESARROLLO DEL SOFTWARE:

<p align="justify">

En un proceso de desarrollo de software  se define quién va a hacer qué, cuándo hacerlo y como alcanzar el objetivo determinado.</p>


   * ANÁLISIS 
   * DISEÑO 
   * CODIFICACIÓN
   * PRUEBAS 
   * MANTENIMIENTO (documentación)

<p align="justify"><b>ANÁLISIS:</b> se definen los requisitos y especificaciones. No solo corresponde al cliente si no a los desarrolladores.
   <ul>
   <li>Completos y sin omisiones: no se debe omitir nada y muy específicos</li>
   <li>Concisos y sin trivialidades: solo cosas importantes. </li>
   <li>Evitar ambigüedades y utilizar lenguaje formal. </li>
   <li>Evitar detalles de diseño e implementación. Es decir, se debe centrar en los requisitos “generales” que sean importantes para el cliente. </li>
   <li>Ser entendible por el cliente. </li>
   <li>Separar requisitos funcionales o no funcionales. Funcional que hace algo, no funcional no afecta a función del programa. </li>
   <li>Dividir y jerarquizar el modelo. Es tener claro las diferentes partes que tiene la aplicación.  </li>
   <li>Fijar criterios de validación: que se va a considerar válidos y cuáles no.</li>
   </ul></p>

<p align="justify"><b>DISEÑO:</b> Se organiza y se descompone el sistema  en elementos que se puedan desarrollar por separado. Intentando que esta descomposición de las partes  se puedan actuar a la vez. 
Se especifica la interrelación y funcionalidad de los elementos componentes.</p>

<p align="justify">Actividades más habituales:</p>
<p align="justify"><ul>
  <li>Diseño arquitectura: que va a hacer cada bloque</li>
  <li>Diseño detallado: de qué es y cómo va a ser cada bloque.</li>
  <li>Diseño de datos: qué datos figuran en cada bloque, como es la estructura de datos que se van a usar en todos los bloques debe ser el mismo. </li>
 <li>Diseño de interfaz de usuario.</li>
</ul></p>
<p align="justify"><b>CODIFICACIÓN:</b>en esta fase se escribe el código fuente de cada componente.</p>
<p align="justify"><b>PRUEBAS:</b> en esta fase se realizan pruebas para comprobar los errores que pueda tener el programa. Las pruebas consisten en que el software falle para mejorarlo.</p> 
<p align="justify"><b>MANTENIMIENTO:</b>Durante la explotación del sistema software es necesario realizar cambios ocasionales. Para ello hay que rehacer parte del trabajo realizado en las fases previas.</p>
<p align="justify">Tipos de mantenimiento:
<ul> 
   <li> Correctivo: se corrigen defectos.</li>
   <li>  Perfectivo: se mejora la funcionalidad</li>
   <li>  Evolutivo: se añade funcionalidades nuevas.</li>
   <li>  Adaptativo: se adapta a nuevos entornos.</li>
</ul>
</p>

[Subir](#item1)

<a name="itemud3"></a>

## 4. Modelos de desarrollo de software.

<p align="justify">Un modelo de desarrollo es el conjunto de una serie de técnicas y sistemas de organización para crear un software. </p>
<p align="justify">Hay diferentes modelos de desarrollo.</p>
 <p align="justify">	<ul>
         		<li><p align="justify"><b>Modelos clásicos (predictivos):</b></p></li>
               <ul>
         		     <li><p align="justify"><b>Modelo en cascada:</b> El modelo de desarrollo en cascada es un tipo de procedimiento lineal se caracteriza por dividirse en fases que se suceden entre sí, las cuales se ejecutan tan solo una vez a lo largo del proyecto.
                    </p>
                   <ol><li><p align="justify">La fase anterior es el punto de partida para la siguiente. Es un modelo bastante rígido que se adapta mal al cambio continuo de especificaciones.</p></li>
                   <li><p align="justify">En este modelo las fases han de realizarse en el orden indicado, siendo el resultado de una fase es la entrada de la siguiente fase.</p>
                   <p align="right"><img width="460" height="300" src="https://github.com/mdrp93/IMAGENES_ENTORNOS/blob/main/FasesModeloCascada_act2_ud1.png"></li>
                   </ol>
                </li></ul>
                <ul>
         		    <li><p align="justify"><b>Modelo en V:</b> Este es un modelo similar al modelo en cascada, pero en este se jerarquizan los distintos niveles. Los niveles superiores indican mayor nivel de abstracción y los inferiores maoyr nivel de detalle.</p><p align="right"><img width="460" height="300" src="https://github.com/mdrp93/IMAGENES_ENTORNOS/blob/main/ModeloV_ud1.png"></li>
               </ul>
          </p></li>
           <li><p align="justify"><b>Modelo de construcción de prototipos:</b> Este es un modelo que se basa en la creación de prototipos. Es utilizado principalmente para ofrecer al usuario una visión previa de cómo será el programa o sistema. El modelo de prototipos pertenece a los modelos de desarrollo evolutivo.</p>
               <ul>
               <li><p align="justify">Un prototipo es un primer modelo que sirve como representación o simulación del producto final y que nos permite confirmar que cuenta con lor requisitos y características deseados.</p>
                <li><p align="justify">En un modelo de prototipos las características fundamentales son:</p>
                    <ol>
                      <li><p align="justify"><b>Tiempo:</b> El prototipo se desarrolla en menos tiempo para poder ser probado o testeado.</p></li>
                      <li><p align="justify"><b>Coste:</b> La inversión en un modelo de prototipo es ajustada, lo que requiere un uso óptimo de los recursos.</p></li>
                      <li><p align="justify"><b>Conciso:</b> El prototipo debe incluir los requisitos y características básicas de la aplicación para poder evaluar su funcionamiento y utilidad.</p></li>
                      <li><p align="justify"><b>Evolutivo:</b> El prototipo evoluciona gracias a la interacción con los usuarios.</p></li>
                     <li><p align="justify"><b>Funcional:</b> El prototipo es una aplicación que funciona.</li>
                     <p align="right"><img width="460" height="300" src="https://github.com/mdrp93/IMAGENES_ENTORNOS/blob/main/FasesModeloPrototipo_act2_ud1.png"></p>
                    </ol>
               </li>
                <li><p align="justify"><b>Tipos de prototipos:</b></p>
                    <ol>
                      <li><p align="justify"><b>Rápidos:</b> En este modelo se da prioridad al desarrollo rápido pues el objetivo es conseguir una rápida evaluación del modelo, por ejemplo, para evaluar si es viable o rentable el desarrollo del producto final.</p></li>
                      <li><p align="justify"><b>Evolutivos:</b> El prototipo está diseñado en el mismo lenguaje y herramientas del proyecto, y el prototipo se usa como base para desarrollar el proyecto.</p></li>
                     </ol>
               </li>
                <li><p align="justify"><b>Fases:</b> Plan rápido-->  Modelado/diseño --> rápido --> Construcción del prototipo -->Desarrollo/ entrega/ retroalimentación --> Comunicación --> ...</p></li>
               </ul>
           </li> 
         <li><p align="justify"><b>Modelos evolutivos o incrementales</b></p></li>
               <ul>
         		     <li><p align="justify"><b> Modelo en espiral (iteractivos)</b> Este es un modelo de proceso evolutivo que une la interactividad de la construcción de prototipos con los aspectos controlados del modelo en cascada, es decir, el software se desarrolla en una serie de entregas o ciclos, y en cada una de estas se entregan prototipos más completos que el anterior, todo esto en función del análisis de riesgo y las necesidades del cliente.  En resúmen, este es un modelo que está basado en el riesgo y orientado a objetos. A diferencia de un modelo lineal como es el modelo en cascada este modelo tiene un ciclo de vida por medio de espirales que hay que recorrer.</p>
                 <p align="justify">Este enfoque se parece bastante a la creación de prototipos. </p><p>Al centrarse en la minimización del riesgo, mediante el análisis y la evaluación de riesgos, este modelo tiene un componente financiero que puede ser muy relevante. </p>
                   <ul><li><p align="justify">El progreso del proyecto va a depender de cómo se vayan resolviendo los riesgos identificados.</p></li>
                    <li><p align="justify">El objetivo de este modelo es producir un proyecto en continua mejora desde el inicio.</p> </li></ul>
               </li></ul>
                <ul>
         		    <li><p align="justify"><b>Metodologías ágiles (adaptativos)</b></p>
                  <ul><li><p align="justify">Son métodos de ingeniería del software basados en el desarrollo iterativo e incremental, se diferencian por que los requisitos y soluciones evolucionan con el tempo según la necesidad del proyecto</p></li>
                      <li><p align="justify">Los <b>principios básicos</b> de estas metodologías son:</p>
                         <ul><li><p align="justify">Valorar más a los individuos y sus interacciones que a los procesos y las herramientas. Los procesos deben ser una ayuda y un soporte para guiar el trabajo.</p></li>
                         <li><p align="justify">Valorar más el software funcionando que la documentación exhaustiva.</p></li>
                         <li><p align="justify">Valorar más la respuesta ante el cambio a que seguir un plan.</p></li>
                         <li><p align="justify">Valorar más la colaboración con el cliente que la negociación contractual</p></li></ul>
                       <li><p align="justify">Las metodologías más conocidas son:</p>
                        <ul><li><p align="justify"><b>KANBAM (o sistema de tarjetas):</b> Un tablero KANBAN es una herramienta de gestión de proyectos basada en un sistema de visualización del trabajo para generar claridad, alineación,y enfoque de los objetivos clave a seguir.</p></li>
                        <li><p><b>SCRUM</b></p></li>
                        <li>XP (sXtreme Programing o programación extrema)</li>
                        <li><p><a href="https://github.com/mdrp93/ENTORNOS-1-DAW/blob/main/Actividad_3_Unidad_1_entornos.md" target="_self">Ver: Tarea 3- Unidad 1</a></p></li>
                        </ul>
                  </ul></li>
               </ul>
          </p></li>
</ul>

### SCRUM

<p align="justify"><b>Proceso que sigue la metodología SCRUM:</b></p>
<ol type="1">

<li><p>Objetivos del producto</p></li>
<li><p>objetivos de la interación</p></li>
<li><p>De 2 a 4 semanas: vuelta a objetivos de la interación</p></li>
<li><p>Reuniones diarias</p></li>
<li><p>Resultado incremental utilizable</p></li>
</ol>

<p align="justify">En la metodología SCRUM se manejan los siguientes conceptos:</p>

<ul type="circle">
<li><p align="justify"> <b>Roles principales:</b> Product Owner, Scrum Master y Team. </p></li>
<li><p align="justify"> <b>Artefactos:</b> Product Backlog, Sprint Backlog e Incremento.</p></li>
<li><p align="justify"> <b>Eventos:</b> Sprint, Sprint plannig, Daily Scrum, Scrum Review y Scrum Retrospective</p></li></ul>


[Subir](#item1)

<a name="itemud4"></a>

## 5. Lenguajes de programación. 

### Obtención de código ejecutable y proceso de compilación e interpretación del código. 

La compilación o interpretaci compilación se lleva a cabo en dos fases:

<ol type="1">
<li><p align="justify"><b>Análisis léxico:</b> si las palabras o términos son correctos y existen en el lenguaje. </p></li>
<li><p align="justify"><b> Análisis sintáctico:</b> si el orden de esas palabras forman frases o procesos que son coherentes y puedan ser dichos de esa forma en ese orden. </p></li>
</ol>
<p align="justify">Si tras estas dos fases no existen errores, se genera el código objeto correspondiente. </p>
<p align="justify">Un código fuente que este escrito de manera correcta no tiene porque funcionar. </p>


### Existen lenguajes:

<ul>
<li><p align="justify"><b>Compilados:</b> En los lenguajes compiladoos no generan código objeto. Cada vez que el código fuente se modifica es necesario compilarlo. </p></li>
<li><p align="justify"><b>Interpretados:</b> su principal ventaja que el código se ejecuta directamente.</p></li></ul>


### JAVA:

<p align="justify">El odigo fuente de JAVA se compila y se obtiene un código binario intermedio : bytecode.</p>
<p align="justify">Este <b>bytecode</b> es transparente al desarrollador independientemente del micro en el que se ejecute el código.<br>Se hacen cosas muy generales al ser para todos los microprocesadores. </p>
<p align="justify">Para poder ejecutar este bytecode necesitas tener instalada la máquina virtual propia para el microprocesador que corresponda. El lenguaje de JAVA es un lenguaje orientado a objetos. </p>

**Ventajas:**
 - Es estructurado
 - Orientado a objetos.
 - muy esclable: es muy facil añadir nuevas funciones a las clases.
 - Gran control sobre el.

**Desventajas:** 
- No es tan eficiente al ser algo genérico o "universal" para todos. Se pierden matices.

### Tipos de lenguajes

**Tipos de lenguajes según la forma en la que operan:** 

- Declarativos.
- Imperativos.

**Tipos de lenguajes declarativos:**

Normalmente son lenguajes interpretados. 
- Lógicos: Utilizan reglas. Ej: Prolog
- Funcionales: Utilizan funciones. Ej: Lisp, Haskell
- Algebraicos: Utilizan sentencias. Ej: SQL

**Tipos de lenguajes imperativos:**

Los lenguajes orientados a objetos son también lenguajes estructurados.

Muchos de estos lenguajes son compilados.
- Orientados a objetos: Java
- Multiparadigma: C++, Javascript
- Estructurados: C

**Tipos de lenguajes según el nivel de abstracción:**

- Bajo nivel: ensamblador
- Medio nivel: C
- Alto nivel: C++, Java

### Evolucion. 

- Código binario
- Ensamblador
- Lenguajes estructurados
- Lenguajes orientados a objetos

### Criterios para la selección de un lenguaje.

- Campo de aplicación
- Experiencia previa
- Herramientas de desarrollo
- Documentación disponible
- Base de usuarios
- Reusabilidad
- Transportabilidad
- Imposición del cliente

[Subir](#item1)

<a name="itemud5"></a>

### Actividades de la unidad 1.

* [Actividad 1: Introducción.](https://github.com/mdrp93/ENTORNOS-1-DAW/blob/main/Actividad_1_unidad_1_entornos.md)
* [Actividad 2: Ciclo de vida del software.](https://github.com/mdrp93/ENTORNOS-1-DAW/blob/main/Actividad_2_unidad_1_entornos.md)
* [Actividad 3: Ciclo de vida del software II. Metodologías.](https://github.com/mdrp93/ENTORNOS-1-DAW/blob/main/Actividad_3_Unidad_1_entornos.md)
* [Actividad 4: Lenguajes de programación](https://github.com/mdrp93/ENTORNOS-1-DAW/blob/main/Actividad_4_unidad_1_entornos.md)

<p></p>
<p></p>
<p></p>

<p><h5>Fin de la Unidad 1:<br></p> <p><i><a href="#top">Subir a APARTADOS</a></i></h3></p>

 
<a name="item2"></a>

## Unidad 2

## Índice unidad 

* [](#item1ud2)
* 

<a name="item1ud2"></a>
### HERRAMIENTAS BÁSICAS
#### BIBLIOTECAS -LIBRERIAS
<p>Cada libreria esta compuesta por varios archivos objeto.</p>
Parte de una biblioteca: 
<ul>
 <li>especificaciones</li>
 <li>Implementacion: suele ser privada, pero podrian darte acceso si es de codigo abierto. </li>
</ul>
<p>API = Interfaz de Programación de aplicaciones. </p>
#### HERRAMIENTAS JAVA
#### BUILD
#### ARCHIVOS DE CONSTRUCCIÓN
Entornos integrados de desarrollo: 
- VISUALCODE
- ECLIPSE
- etc...

