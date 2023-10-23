<a name="top"></a>
 
# Apuntes de Entornos de Desarrollo

<p align="center">
   <img width="1000" height="450" src="https://github.com/mdrp93/ENTORNOS-1-DAW/blob/main/entornos-de-desarrollo-2.jpg">
                                                                                                                  
<p align="left">
   <img src="https://img.shields.io/badge/STATUS-EN%20DESAROLLO-green">
   </p>

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

<a name="itemud1"></a>
## 1 y 2 Introducción: Conceptos básicos

<ul>
  <li>Existen tres tipos de software: de sistema, de aplicación, y de desarrollo.
  	 <ul>
  		<li>En el <b>software de sistema</b> se encuentran el SO., los drivers o controladores de dispositivos (firmware).</li>
  		<li>En el <b>software de aplicación</b> encontramos suite ofimática, navegadores, editor de imagenes o texto...</li>
  		<li>Y en el <b>software de desarrollo</b>encontramos editores, compiladores, interpretes..etc</li>
  	 </ul>
  </li>
 <li>En cuanto al hardware tenemos disco duro, memoria RAM, CPU, dispositivos de entrada y salida.
         	<ul>
         		<li><b>Los dispositivos de entrada y salida:</b> recogen datos desde la entrada y muestran los resultados por la salida.</li>
               <ul>
         		     <li>La salida es la información que se lee desde la cpu al exterior.</li>
         		     <li>La entrada es información que se lee del exterior hacia la cpu.</li>
         	    </ul>
           </li>
           <li><b>Memoria RAM:</b> almacena de manera temporal el código binario de los archivos ejecutables y de los datos que necesita.</li>
           <li><b>CPU ó _Central processing Unit_:</b>lee y ejecuta las instrucciones que se han almacenado en la RAM, y coge analiza los datos necesarios para llevar a cabo las instrucciones.</li>
           <li><b>Disco duro:</b> almacena de manera permanente los arcchivos ejecutables y los archivos de datos. </li>
          </ul>
</ul>

Hay diferentes tipos de códigos:
- **Código fuente:** es el código entendible por un ser humano para crear un programa. Permite modificar un programa de manera sencilla. 
- **Código objeto:** es un archivo binario, no ejecutable, que se genera a partir del código fuente.
- **Código ejecutable:** es un archivo que se puede ejecutar en el ordenador, y que previamente se han basado en el código fuente.

> Comentario: En JAVA el código objeto se le llama bytecode.
  
El que hace que un código se entienda en una máquina es el compilador. 

Hay lenguajes compilados y otros que son los lenguajes interpretados que no necesitan ser compilados. 

Por otro lado **los scripts** son lenguajes que no necesitan ser compilados, se empiezan a ejecutar desde la primera orden o línea. (python, typescrit). 

> Comentario: Core - Los núcleos permiten llevar diferentes hilos de ejecución independientes.

[Subir](#item1)

<a name="itemud2"></a>
## 3. Ciclo de vida del software. 
La ingeniería es el ingenio de crear un diseño. Principios y metodologías para desarrollar y mantener el software.
Ahora se usa el término desarrollo de software.

### FASES DEL DESARROLLO DEL SOFTWARE:
   * ANÁLISIS 
   * DISEÑO 
   * CODIFICACIÓN
   * PRUEBAS 
   * MANTENIMIENTO (documentación)

**ANÁLISIS:** se definen los requisitos y especificaciones. No solo corresponde al cliente si no a los desarrolladores.
   - Completos y sin omisiones: no se debe omitir nada y muy específicos
   - Concisos y sin trivialidades: solo cosas importantes. 
   - Evitar ambigüedades y utilizar lenguaje formal. 
   - Evitar detalles de diseño e implementación. Es decir, se debe centrar en los requisitos “generales” que sean importantes para el cliente. 
   - Ser entendible por el cliente. 
   - Separar requisitos funcionales o no funcionales. Funcional que hace algo, no funcional no afecta a función del programa. 
   - Dividir y jerarquizar el modelo. Es tener claro las diferentes partes que tiene la aplicación.  
   - Fijar criterios de validación: que se va a considerar válidos y cuáles no.

**DISEÑO:** Se organiza y se descompone el sistema  en elementos que se puedan desarrollar por separado. Intentando que esta descomposición de las partes  se puedan actuar a la vez. 
Se especifica la interrelación y funcionalidad de los elementos componentes.

Actividades más habituales:
<ul>
  <li>Diseño arquitectura: que va a hacer cada bloque</li>
  <li>Diseño detallado: de qué es y cómo va a ser cada bloque.</li>
  <li>Diseño de datos: qué datos figuran en cada bloque, como es la estructura de datos que se van a usar en todos los bloques debe ser el mismo. </li>
 <li>Diseño de interfaz de usuario.</li>
</ul>

**CODIFICACIÓN:** en esta fase se escribe el código fuente de cada componente. 

**PRUEBAS:** en esta fase se realizan pruebas para comprobar los errores que pueda tener el programa. 

**MANTENIMIENTO:** Durante la explotación del sistema software es necesario realizar cambios ocasionales. Para ello hay que rehacer parte del trabajo realizado en las fases previas.

Tipos de mantenimiento: 
   * Correctivo: se corrigen defectos.
   * Perfectivo: se mejora la funcionalidad
   * Evolutivo: se añade funcionalidades nuevas.
   * Adaptativo: se adapta a nuevos entornos.

[Subir](#item1)

<a name="itemud3"></a>
## 4. Modelos de desarrollo de software.

Un modelo de desarrollo es el conjunto de una serie de técnicas y sistemas de organización para crear un software. 

Hay diferentes modelos de desarrollo. 

**Modelos clásicos (predictivos):**
<p><b>- Modelo en cascada:</b> El modelo de desarrollo en cascada es un tipo de procedimiento lineal se caracteriza por dividirse en fases que se suceden entre sí, las cuales se ejecutan tan solo una vez a lo largo del proyecto.</p>
<p>La fase anterior es el punto de partida para la siguiente. Es un modelo bastante rígido que se adapta mal al cambio continuo de especificaciones.</p>
<p>En este modelo las fases han de realizarse en el orden indicado, siendo el resultado de una fase es la entrada de la siguiente fase.</p>
<p><b>- Modelo en V:</b> Este es un modelo similar al modelo en cascada, pero en este se jerarquizan los distintos niveles. Los niveles superiores indican mayor nivel de abstracción y los inferiores maoyr nivel de detalle.</p> 
</p><b></b>- Modelo de construcción de prototipos:</b> Este es un modelo que se basa en la creación de prototipos. Es utilizado principalmente para ofrecer al usuario una visión previa de cómo será el programa o sistema.</p>
<p>Un prototipo es un primer modelo que sirve como representación o simulación del producto final y que nos permite confirmar que cuenta con lor requisitos y características deseados.</p>
<p>En un modelo de prototipos las características fundamentales son:</p>
<ol>
  <li><b>Tiempo:</b> El prototipo se desarrolla en menos tiempo para poder ser probado o testeado.</li>
  <li><b>Coste:</b> La inversión en un modelo de prototipo es ajustada, lo que requiere un uso óptimo de los recursos.</li>
  <li><b>Conciso:</b> El prototipo debe incluir los requisitos y características básicas de la aplicación para poder evaluar su funcionamiento y utilidad.</li>
  <li><b>Evolutivo:</b> El prototipo evoluciona gracias a la interacción con los usuarios.</li>
 <li><b>Funcional:</b> El prototipo es una aplicación que funciona.</li>
</ol>
<p><b>Fases:</b> Plan rápido-->  Modelado/diseño --> rápido --> Construcción del prototipo -->Desarrollo/ entrega/ retroalimentación --> Comunicación --> ...</p>

**Modelos evolutivos o incrementales**
 - Modelo en espiral (iterativos)
 - Metodologías ágiles (adaptativos)






<a name="itemud4"></a>
## 5. Lenguajes de programación. 

### Obtención de código ejecutable. 
 - Compilar
 - Interpretar

### Existen lenguajes:
- Compilados: En los lenguajes compiladoos no generan código objeto.
  
- Interpretados.

### JAVA:

El odigo fuente de JAVA se compila y se obtiene un código binario intermedio : bytecode.
Este bytecode es transparente al desarrollador independientemente del micro en el que se ejecute el código. 
Se hacen cosas muy generales al ser para todos los microprocesadores. 
Para poder ejecutar este bytecode necesitas tener instalada la máquina virtual propia para el microprocesador que corresponda. 
El lenguaje de JAVA es un lenguaje orientado a objetos. 

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



[Subir](#top)

### Tareas de la unidad 1.
* [Tarea 1: Introducción.](https://github.com/mdrp93/ENTORNOS-1-DAW/blob/main/Tarea1_%20introducci%C3%B3n.md)
* [Tarea 2: Ciclo de vida del software.]()
* [Tarea 3: Ciclo de vida del software 2. Metodologías.] ( )


[Subir](#top)
 
<a name="item2"></a>
## Unidad 2

en construcción...
