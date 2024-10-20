[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/Z6NE2ogx)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=16551461&assignment_repo_type=AssignmentRepo)
# Práctica 1: Introducción al desarrollo. Reflexiones.

Apoyate en los siguientes recursos para realizar la práctica:

[Descripción de la práctica](https://revilofe.github.io/section3/u01/practica/EDES-U1.-Practica010/)


---

# Título de la Actividad

## Identificación de la Actividad
- **ID de la Actividad:** Práctica 1: Introducción al desarrollo. Reflexiones.
- **Módulo:** EDES
- **Unidad de Trabajo:** [Número y nombre de la unidad de trabajo]
- **Fecha de Creación:** 15/10/2024
- **Fecha de Entrega:** 20/10/2024
- **Alumno(s):** 
  - **Nombre y Apellidos:** Óscar García Jaén
  - **Correo electrónico:** ogarjae565@g.educaand.es
  - **Iniciales del Alumno/Grupo:** OGJ

## Descripción de la Actividad
[Descripción detallada de la actividad, objetivos, y contexto necesario para comprenderla. Explicar en qué consiste la actividad y qué se espera que el alumno desarrolle o implemente.]

## Instrucciones de Compilación y Ejecución
1. **Requisitos Previos:**
   - [Lenguaje de programación y versión]
   - [Entorno de desarrollo o dependencias necesarias]

2. **Pasos para Compilar el Código:**
   ```bash
   [Comando para compilar el código]
   ```

3. **Pasos para Ejecutar el Código:**
   ```bash
   [Comando para ejecutar la aplicación]
   ```

4. **Ejecución de Pruebas:**
   ```bash
   [Comandos para ejecutar pruebas, si las hubiera]
   ```

## Desarrollo de la Actividad
### Descripción del Desarrollo
[Explicación de cómo se ha abordado el desarrollo de la actividad, incluyendo las decisiones de diseño, estructura del código y enfoque de resolución de problemas. Se recomienda adjuntar diagramas o capturas de pantalla si es necesario.]

# P 1.10: Reflexión y discusión sobre los resultados
## 1. Relación software y hardware
### 1.1. Primera parte

1.1.1. ¿Cómo se ejecuta el código en el procesador?

El procesador toma las instrucciones de un programa y realiza los cálculos necesarios para su funcionamiento.

1.1.2. ¿Qué hace la memoria RAM con la información del botón o el LED?

Almacena de forma temporal la información y las instrucciones de funcionamiento del botón para accionarlas sobre el LED.

1.1.3. ¿Cómo se comunican los periféricos (botón y LED) con el procesador?

Mediante el sistema de entrada salida dele procesador, introduciendo el dato en la ALU.

### 1.2. Segunda parte

1.2.1. ¿Cómo interactúan el procesador, la memoria y los periféricos en la ejecución del programa?

El programa se carga en memoria RAM, posteriormente el procesador empieza a ejecutar las instrucciones, si hay una operacion de entrada, se utilizara el teclado para introducir el dato requerido, que posteriormente se almacenará en alguna celda de memoria.

1.2.2. ¿Qué pasa con los datos en la memoria cuando el programa se ejecuta?

Se guarda el dato en alguna celda de memoria hasta la finalización del mismo.

1.2.3. ¿Qué roles juegan las instrucciones del software en esta interacción?

Son las que dictaminan si el dato que se encuentra en memoria RAM es necesario para otra operación o se mantiene en la celda de memoria.

1.2.4. ¿Cómo se relaciona esta simulación con lo que ocurre en un ordenador real?

Esta simulacíon representa como el procesador ejecuta un programa utilizando las instrucciones que estan situadas en memoria RAM, tambien almacena los datos introducidos por teclado en alguna celda de memoria, para luego ser utilizados en alguna operación.

## 2. Del código fuente al ejecutable

2.1. ¿Cómo se diferencia el código fuente del código objeto y del ejecutable?

El código fuente es el que es escrito por el programador en algun lenguaje y el ejecutable es directamente el ensamblado para utilizarlo

2.2. ¿Por qué el ordenador no puede entender el código fuente directamente?

Porque el equipo solo entiende el lenguaje máquina que consta de unos y ceros.

2.3. ¿Por qué es importante el paso de enlazado en la creación de programas?

Porque fusiona todos los archivos generados del código objeto en uno solo ejecutable.

2.4. ¿Qué ocurre si falta alguna de las etapas (código objeto o ejecutable)?

Si el que falta es el ejecutable, a partir del código objeto podemos obtener el ejecutable, mientras que si tenemos el ejecutable no podemos obtener el codigo objeto a través de él.

## 3. Generación de código intermedio

3.1. ¿Cómo difiere el código intermedio del código ejecutable tradicional?

Es un tipo de código genérico, que puede ser ejecutado por diferentes máquinas virtuales de diferentes S.O.

3.2. ¿Por qué es útil tener una máquina virtual?

Porque hace de intermediario entre el código intermedio  y el hardware. Se encarga de ejecutar el código intermedio, traduciendolo a instrucciones que entienda el procesador.

3.3. ¿Qué ventajas ofrece el código intermedio?

Portabilidad, seguridad y optimización de tiempo de ejecución.

3.4. ¿Además de java, qué otros lenguajes usan máquinas virtuales?

Otro lenguaje puede ser C#

## 4. Lenguajes de programación

### 4.1. Primera parte

Compara el proceso de ejecución entre el lenguaje compilado y el interpretado.

4.1.1. ¿Qué diferencias notaron en el proceso de compilación frente a la ejecución directa?

Que en la compilación debe de traducirse a código máquina y en la interpretación se traduce a la vez que se ejecuta línea a línea,

4.1.2. ¿Qué pasa si hay un error de sintaxis en cada lenguaje? ¿Cuándo se detecta el error?

En lenguaje interpretado se detecta el error en tiempo de ejecución, este acabara con la ejecución del programa.

En lenguaje compilado el error se detecta en la compilación y no compila el programa.

### 4.2. Segunda parte

Compara un lenguaje de alto nivel con uno de bajo nivel.

4.2.1. ¿Qué notaron sobre la abstracción entre los lenguajes de alto nivel y bajo nivel?

Que el lenguaje de bajo nivel es el más cercano a la máquina y es posible optimizar el sistema, a su vez el de alto nivel es mas cercano al humano lo que permite mayor comprensión por el mismo pero menos control sobre el sistema.

4.2.2. ¿Qué ventajas y desventajas encontraron en cada uno?

El de alto nivel es más cercano al humano y cuenta con muchas funcionalidades que ayudan al desarrollador pero cuenta con menos control del sistema.

El de bajo nivel es más cercano a la máquina y ofrece mayor control y eficiencia del sistema pero es mas complejo de escribir y comprender.

### 4.3. Tercera parte

Compara un lenguaje orientado a objetos vs funcional.

4.3.1. ¿Cómo funciona la organización de datos en Java usando objetos y métodos?

Se organiza el código en objetos o instancias de clases. Los objetos encapsulan datos y comportamientos.

4.3.2. ¿Cómo es diferente trabajar en un enfoque funcional en Python, usando solo funciones puras?

Las funciones puras son aquellas que dado el mismo conjunto de datos la función siempre devolvera el mismo resultado. El uso de funciones puras es muy recomendable ya que garantiza la integridad de los datos y la repetibilidad de los resultados.

### 4.4. Reflexión final

4.4.1. ¿Qué lenguajes se sintieron más fáciles de usar? ¿Por qué?

Sentí más fáciles los lenguajes Python, JavaScript, Ruby, PHP ya que son lenguajes interpretados, estos son más lentos pero más sencillos al  no tener que compilar

4.4.2. ¿En qué casos es preferible usar un lenguaje compilado frente a uno interpretado?

En caso de que el rendimiento y optimización sean cruciales la mejor opción son los compilados.

4.4.3. ¿Cuándo es mejor usar un lenguaje de alto nivel en lugar de uno de bajo nivel?

El de alto nivel es mejor cuando se requiere un desarrollo rápido, mantenimiento y portabilidad, ya que es un lenguaje más comodo de mantener y mejorar.

4.4.4. ¿Cómo se siente trabajar con el paradigma orientado a objetos en comparación con el imperativo o funcional?

El orientado a objetos es mas organizado y estructurado, enfocandose en objetos, el inmperativo da las instrucciones paso a paso y el funcional trata de funciones puras. 

## 5. Herramientas de desarrollo
### 5.1. Primera parte
Respecto a las proceso de creación de software identifica un conjunto de herramientas a usar.

5.1.1. ¿Qué hace cada una de las herramientas?

Editores de texto: es una herramienta básica utilizada para escribir y modificar el código, son versátiles y ligeros.

Compiladores: son los encargados de traducir el código fuente a código máquina, el codigo generado es específico para el sistema operativo  y arquitectura de la máquina donde se ejecuta.

Intérpretes: es el encargado de ejecutar el código fuente línea por línea, sin necesidad de compilarlo  previamente a código máquina.

Herramientas de documentación: esta herramienta analiza el código fuente y genera documentación automáticamente a partir de comentarios y anotaciones

Depuradores: estas herramientas permiten detener la ejecución de un programa en puntos específicos para examinar su estado inteno y para encontrar errores lógicos y fallos.

Sistema de gestión de versiones: permiten a los desarrolladores rastrear cambios en el código, trabajar en diferentes ramas de desarrollo y colaborar sin riesgo de sobreescribir el trabajo de otros.

Frameworks: son los encargados de proporcionar una estructura predefinida para desarrollar aplicaciones, facilita la creación de proyectos mediante librerías y plantillas.

Herramientas para pruebas y calidad de código: asegura que el software funciona como debe. Puede realizar pruebas automáticas del software, como unitarias hasta de carga y rendimiento.

5.1.2. ¿Qué tipo de tareas facilita?

Compilador: facilita la traducción de código fuente a código máquina.

Intérprete: facilita la ejecución del programa (línea a línea)

Herramientas de documentación: facilita la documentación que explica el funcionamiento y la lógica del programa.

Depurador: facilita la busqueda de fallos en el código pudiendo tambien dividirlo en varias partes.

Sistema gestor de versiones: facilita el trabajo en equipo sin riesgo de corromper el trabajo del resto de miembros del equipo.

Framework: facilita el propio desarrollo del programa ya que hace más sencillo el uso de una estructura predefinida.

5.1.3. ¿Qué características ofrece que la hacen única o diferente de otras herramientas similares?

Compilador: lo que la diferencia es la facilidad para convertir un código a lenguaje máquina.

Interprete: esta se ve diferenciada ya que puede ejecutar un programa sin antes una compilación.

Herramientas de documentación: esta herramienta genera un documento con todas las anotaciones y comentarios.

Depurador: Se diferencia en su capacidad de de revisar el código por partes y no de una vez.

Sistema gestor de versiones: esta herramienta se diferencia en su capacidad de tener todo centralizado en un mismo lugar y tener todas las versiones.

Framework: esta herramienta facilita el tener una estructura predefinida para facilitar su desarrollo

Herramientas para pruebas de calidad del código: el poder comprobar el codigo y su estructura de forma sencilla.

5.1.4. Elige una ¿Cómo es la experiencia de usuario al usarla? ¿Es fácil o compleja?

El editor de texto desde el lado del editor es algo compleja ya que continua siendo un editor de texto convencional para desarrollar código, mientras que el IDE facilita el desarrollo ya que puede instalar extensiones y funcionalidades que permiten trabajar mejor.

5.1.5. Elige una ¿En qué situaciones sería ideal utilizar esta herramienta?

IDE: ya que a la hora de desarrollar tu programa es más sencillo gracias a todas las facilidades que este proporciona.

5.1.6. Elige una ¿Qué limitaciones encontraste en la herramienta?

El editor de texto ya qu este no cuenta con tantas funcionalidades añadibles como el IDE, por lo que lo considero mucho peor.

### 5.2. Segunda parte
Céntrate en una herramienta dentro de la misma categoría y compárala con otras:

5.2.1. ¿Qué herramienta se considera más útil y por qué?

El IDE ya que puede ayudar mucho a la hora de realizar tu trabajo gracias a todas las funcionalidades que puede llegar a tener.

5.2.2. ¿Qué ventajas tiene una sobre la otra?

Que a la hora de desarrollar tu trabajo es mucho más eficiente que si utilizas un editor convencional.

5.2.3. ¿Cuál herramienta resultó ser la más intuitiva y por qué?

El IDE ya que al poner el lenguaje que se iba a utilizar ya da ayudas de como iniciar.

5.2.4. ¿En qué casos se recomendaría usar un compilador en lugar de un intérprete?

Cuando sea necesario el rendimiento y optimización del código.

5.2.5. ¿Qué tipo de proyectos se beneficiarían más de un framework como Django?

Los proyectos web que necesiten de un desarrollo rápido y escalabilidad, como por ejemplo RRSS y negocios online.

### 5.3. Reflexión final
Con base en la experiencia de evaluación de las herramientas:

5.3.1. ¿Cómo crees que impacta la elección de la herramienta en la calidad del software?

Tiene un gran impacto ya que la elección de la herramienta puede facilitarte el desarrollo del software mejorando asi su calidad.

5.3.2. ¿Qué características buscarías en una herramienta para facilitar tu flujo de trabajo?

Pues buscaria eficiencia en el sentido de buscar una herramienta que me ayude a realizarlo en un menor tiempo, tambien buscaría alguna que me ayudase a corregir los errores de una forma más sencilla y más explicita.

5.3.3. ¿Cómo cambió tu percepción de estas herramientas después de haberlas probado y evaluado?

Hubo un gran cambio ya que he aprendido que una buena utilización de dichas herramientas puede ayudarte a realizar un trabajo de mayor calidad con mucha más facilidad.

### Código Fuente
[Aquí se incluirá un enlace directo a los archivos de código fuente en el repositorio, por ejemplo, si se está usando GitHub: `src/main.java` o algún enlace directo.]

### Ejemplos de Ejecución
- **Entrada 1:** Descripción de la entrada y valor de prueba.
- **Salida Esperada 1:** Explicación de la salida esperada y el resultado de la prueba.

### Resultados de Pruebas
[Aquí se detallará cómo se ha verificado la funcionalidad del código, incluyendo resultados de pruebas automatizadas o manuales, en caso de que las haya.]

## Documentación Adicional
- **Manual de Usuario:** [Enlace a la documentación del usuario, si existe]
- **Autorización de Permisos:** Verificar que el profesor tenga permisos de lectura en el repositorio para revisar el código.

## Conclusiones
[Resumen de las conclusiones alcanzadas al desarrollar la actividad, las lecciones aprendidas, y posibles mejoras que se puedan implementar en futuras entregas.]

## Referencias y Fuentes
[Aquí se listarán las fuentes consultadas para el desarrollo de la actividad, tales como documentación oficial, artículos, o cualquier recurso externo relevante.]

### Notas Adicionales:
1. **Nombres de Archivos y Repositorios:**
   - Asegúrate de que el nombre del archivo o repositorio siga la estructura definida: `XXX-idActividad-Iniciales`.
2. **Permisos:**
   - Verifica que el profesor tenga los permisos necesarios para acceder al repositorio o documento.
3. **Formato:**
   - Si se entrega en formato PDF o Google Docs, asegúrate de cumplir con el mínimo y máximo de folios establecidos.
4. **Compilación y Ejecución:**
   - Detalla claramente cómo compilar y ejecutar el código, incluyendo las instrucciones en el archivo `README.md`.

### Bibliografia
https://es.linkedin.com/pulse/qu%C3%A9-es-una-funci%C3%B3n-pura-y-c%C3%B3mo-funciona-jorge-arias-arg%C3%BCelles
