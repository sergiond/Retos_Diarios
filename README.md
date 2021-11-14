# Retos_Diarios

ENUNCIADO 08/11/2021
El reto consiste en lo siguiente:
- Lenguaje: Python
- IDE recomendado: PyCharm
- Nivel: Inicial
- Enunciado: Dado un fichero excel con nombres y correos (columna nombre y columna email), realiza un script en Python que devuelva los mails únicos de la columna email.
- Consideraciones: Utiliza la librería pandas para procesar el fichero Excel (.xls).

Commit ficheros relacionados al reto del día 08/11/2021:
- EmailNoDuplicado.py
- nombres_email.xlsx

ENUNCIADO 09/11/2021
- Lenguaje: HTML, CSS y JavaScript
- IDE recomendado: Visual Studio Code
- Nivel: Inicial
- Enunciado: Haz una web simulador de cuota de hipoteca. Para ello, el usuario proporcionará: cantidad (€), número de cuotas (meses) y tipo de interés (%). La página devolverá el importe de la cuota mensual. Opcional: puedes usar un slider en el número de cuotas y en el tipo de interés.
- Consideraciones: Debemos poder probar el ejercicio, ya sea con jsfiddle, stackblitz o publicado en algún sitio.

Commit ficheros relacionados al reto del día 09/11/2021:
- index.html
- estilo.css
- cuotas.js

ENUNCIADO 10/11/2021
- Lenguaje: Java
- IDE recomendado: IntelliJ
- Nivel: Inicial
- Enunciado: Dada una cadena de texto (String) con el nombre completo de una persona, debes crear un método que devuelva 3 campos: nombre, apellido1, apellido2. Debes tener en cuenta que hay nombres compuestos y que puedes recibir un nombre completo sin apellido2 o sin ningún apellido.
Ejemplos: José Martínez Pérez -> nombre: José, apellido1: Martínez, apellido2: Pérez.
                   José María Martínez -> nombre: José María, apellido1: Martínez
                   José -> nombre: José
- Consideraciones: Deberías tener los nombres de pila en un array o fichero, para poder diferenciar entre un nombre de pila y un apellido.


ENUNCIADO 11/11/2021
- Lenguaje: Kotlin
- IDE recomendado: IntelliJ
- Nivel: Inicial
- Enunciado: Crea la clase Usuario, como clase base, de la cual derivarán Estudiante, Instructor y Administrador. Cada clase, tendrá varios atributos propios. Además, deberemos crear la clase Curso. Cada Curso tendrá N Estudiantes y 1 Instructor. A la vez, desde Instructor podremos navegar a los Cursos y desde los Estudiantes también, accederemos a todos los Cursos de un Estudiante.
Crearemos 2 métodos para la clase Usuario y un método para la clase Estudiante, Instructor y Administrador. Ejemplos de método pueden ser: login, realizarEntrega, matricular, corregir…
- Consideraciones: Os dejo la documentación de Kotlin https://kotlinlang.org/docs/classes.html
Kotlin Help

ENUNCIADO 12/11/2021
- Lenguaje: Java
- IDE recomendado: IntelliJ
- Nivel: Inicial
- Enunciado: Crea un método que convierta una cadena de texto (String) en un Array de enteros (Integer). El método recibirá como parámetro la cadena y devolverá un ArrayList de tipo Integer. Debes lanzar una excepción en los siguientes casos:
1) El array no está bien formado (es decir, no tiene [] o , para separar los elementos.
2) El elemento a convertir no es un entero.
- Consideraciones: Crea una Clase llamada Util para meter este método y otros que puedan resultar de utilidad. No se debe instanciar la clase Util, se debe poder invocar directamente al método a través de Util.stringToArray()
