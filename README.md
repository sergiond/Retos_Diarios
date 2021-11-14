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

ENUNCIADO 13/11/2021
- Lenguaje: Java o Python
- IDE recomendado: IntelliJ (Java) o PyCharm (Python)
- Nivel: Inicial
- Enunciado: El objetivo es crear una calculadora de texto. Le podrás dar instrucciones del siguiente estilo:
      - suma dos y dos
      - multiplica tres y cuatro
      - resta seis y tres
      - divide seis y dos (la división siempre dará un resultado entero)
El resultado será también en texto. Los números que recibirá irán del cero al nueve.
- Ampliación: Añade una operación extra después de la primera operación. Ejemplo:
      - suma dos y dos y multiplícalo por seis
      - multiplica tres y cuatro y súmale dos
- Consideraciones: si no se reconoce un número o una operación, se debe lanzar una excepción (una diferente en cada caso)

ENUNCIADO 14/11/2021
El reto de hoy consiste en lo siguiente:
- Lenguaje: Scala
- IDE recomendado: IntelliJ
- Nivel: Intermedio
- Enunciado: Crea 4 clases, Usuario (clase abstracta), Estudiante (hereda de Usuario), Invitado  (hereda de Usuario) y Administrador (hereda de Usuario y tiene nivel), cada uno con sus atributos (no hacen falta métodos). En el método Main, debes crear una lista (List) de Usuarios. Para cada elemento:
      - Si es de tipo Invitado, debes mostrarle el mensaje "No estás autorizado a entrar en esta lección".
      - Si es de tipo Estudiante, debes comprobar que su $nombre y $password existe y mostrar el mensaje "Bienvenid@ a OpenVitae, $nombre".
      - Si es de tipo Administrador y su nivel es 1, debes mostrar el mensaje "Tu nivel es insuficiente".
      - Si es de tipo Administrador y su nivel es 2, debes mostrar el mensaje "Tu nivel es el correcto".
- Consideraciones: Debes usar una de las funcionalidades más potentes de Scala, llamada pattern matching.
