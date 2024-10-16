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
- **Fecha de Entrega:** [Fecha de entrega]
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

Es un tipo de código genérico, 

3.2. ¿Por qué es útil tener una máquina virtual?



3.3. ¿Qué ventajas ofrece el código intermedio?



3.4. ¿Además de java, qué otros lenguajes usan máquinas virtuales?


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
