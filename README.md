<img  align="left" width="150" style="float: left;" src="https://www.upm.es/sfs/Rectorado/Gabinete%20del%20Rector/Logos/UPM/CEI/LOGOTIPO%20leyenda%20color%20JPG%20p.png">

<img  align="right" width="250" style="float: right;" src="logos/LogoMoodleOscuro.png">

<br/><br/>

# Práctica 0 - Entrega de prácticas


## Contenido

-   [Introducción](#introducción)
-   [Objetivos](#objetivos)
-   [Requisitos Previos](#requisitos-previos)
-   [Temas relacionados con la práctica](#temas-relacionados-con-la-práctica)
-   [Actividades de la práctica](#actividades-de-la-práctica)
    -   [Creación del proyecto](#creación-del-proyecto)
    -   [Creación de la clase Paciente.java](#creación-de-la-clase-paciente.java)
    -   [Extensión de la clase PruebaPaciente.java](#extensión-de-la-clase-pruebapaciente.java)
-   [Evaluación](#evaluación)
-   [Entrega de la práctica](#entrega-de-la-práctica)



## Introducción

En la presente práctica, vamos a realizar una entrega del proyecto siguiendo los pasos que se deberán seguir en el resto de las prácticas. Esta práctica servirá para comprobar que Eclipse está correctamente instalado, además de para familiarizarse con el proceso de entrega de las prácticas.

A partir de este punto, se enuncian las diferentes actividades a desarrollar en esta práctica. Se recomienda leer y comprender el enunciado entero antes de comenzar a trabajar.


## Objetivos

- Uso del Moodle
- Descarga del proyecto base.
- Comprobación de la instalación de Eclipse.
- Uso del entorno de trabajo (IDE): compilación, ejecución y entrega.

## Requisitos Previos

Disponer de un entorno de desarrollo como Eclipse que permita desarrollar programas en el lenguaje de programación Java.


## Temas relacionados con la práctica

Tema 2 del temario del curso.


## Actividades de la práctica

### Creación del proyecto

Debe seguir los siguientes pasos:

- Descargue de Github pulsando sobre el botón _Code->Download ZIP_ el fichero zip que encontrará en la entrada _Práctica 0_.
- Importe el proyecto con _Import-$>$Existing Projects into Workspace_ e indicar la localización del fichero zip descargado usando la opción _Select archive file_.
- Dentro del proyecto, en la carpeta _src_, encontrará un paquete llamado **es.upm.dit.fprg22.p0**, siguiendo el convenio más extendido de nomenclatura de paquetes: Práctica 0 (**p0**) de la asignatura FPRG Curso 2022-2023 (**fprg22**) del Departamento de Ingeniería de Sistemas Telemáticos (**dit**) de la Universidad Politécnica de Madrid (**upm**) de España (**es**).
- También encontrará la clase **C1.java** de Moodle.

En este punto, ya deberíamos poder ver la clase **C1.java** en nuestro espacio de trabajo y, si la abrimos, podremos ver su código. Es un proyecto Eclipse con una clase C1 y un método int prueba(). En esta práctica, *no debe modificar ningún archivo del proyecto*.


## Entrega de la práctica

La práctica se estar entregada en Moodle.
\\

Cuando haya completado todas las clases pedidas y esté seguro de que funcionan correctamente, es decir, ha pasado con éxito las pruebas que se proporcionan en el proyecto, puede obtener una indicación aproximada de su nota en la práctica mediante unas pruebas automáticas parecidas a las que llevarán a cabo los profesores. Este proyecto solo incluye una prueba para evaluar la entrega, que chequea si el método prueba() devuelve 4. Si funciona la nota es 10, sino 0. Pero en cualquier caso se puede subir la entrega (si no se meten errores de compilación). Esta es una mera indicación, sin valor académico; la nota real será la que obtenga tras subir su práctica a Moodle en el período de entrega, los profesores corrijan todas las prácticas y revisen que no hay copias de código, un tiempo después de la fecha de entrega de la práctica.

Para obtener la nota aproximada debe seguir estos pasos:

- Seleccionar el lanzador _Practica0Entrega.launch_ en la carpeta del proyecto. Activar con el botón derecho del ratón el menú de contexto de eclipse, y aparecerá un menú con la entrada _Run As_, dentro de la cual se encuentra la entrada _Practica0Entrega_, que debe selecionar.

- Se ejecutan unas pruebas y se muestran los resultados en la consola: ficheros que componen la práctica, nota estimada, e indicaciones de las pruebas que pudieran haber fallado. Las indicaciones de fallos no permiten saber la causa de los fallos, sólo muestran situaciones en las que la práctica no funciona correctamente. Debe ser usted quien descubra y repare los errores.

- Después de realizar las pruebas y dar una nota estimada, _Practica0Entrega.launch_ construye un fichero .zip que queda en la carpeta del proyecto eclipse.

Cuando esté convencido de que puede subir su práctica (por supuesto, antes de que acabe el plazo de entrega), debe hacerlo como sigue. El proceso de entrega varía según el sistema operativo que esté usando:

### Windows y Mac:

- Tras ejecutar el archivo _Practica0Entrega.launch_, se abre Moodle en un browser embebido.

- Se debe hacer login en Moodle.

- A continuación Eclipse automáticamente realizará la subida de la entrega. El alumno no debe hacer nada más.

### Ubuntu 20

- Tras ejecutar el archivo _Practica0Entrega.launch_, se muestra una serie de pasos por la consola de Eclipse.

- El primer paso es abrir un navegador y hacer login en Moodle. Se deberá copiar el token de Moodle y escribirlo en la consola.

- A continuación Eclipse automáticamente realizará la subida de la entrega. El alumno no debe hacer nada más.  El script de entrega puede detectar situaciones anómalas muy diversas en las que no se puede realizar la entrega, como por ejemplo: la práctica no compila, las clases o métodos no se ajustan al enunciado. En esos casos no se crea/actualiza el fichero .zip, ni se ejecutan las pruebas de evaluación. Para poder generar el zip y subir la entrega hay que arreglar esos problemas. Solo se corregirá la última entrega subida a "Practica0Entrega".

## IMPORTANTE

Es importante subir el fichero fprg-practica2-2022.zip tal cual lo construye y lo entrega eclipse desde el script de entrega Practica0Entrega.launch. Es IMPORTANTE NO hacer lo siguiente:

- Cambiar el nombre al fichero
- Subir el export de eclipse del proyecto
- Comprimir una carpeta y subir esa carpeta

En cualquiera de esos casos la práctica se dará por incorrecta y se puntuará a 0.
