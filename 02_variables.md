# Variables

## ¿Qué es una variable?

Son contenedores que almacenan datos de forma temporal para que puedan ser utilizados (y, que pueden cambiar de valor) posteriormente. Estan formados por un un espacio en el sistema de almacenaje y un nombre simbólico (o identificador). El tipo y el tamaño de una variable esta definido por el tipo de dato que va a almacenar. Cabe tener en cuenta que el espacio de almacenamiento de una variable es finito (limitado).

## Tipos de variables.

El tipo de datos que puedes guardar en una variable son:

* ### Cadena
Almacenan una secuencia de carácteres ordenados compuestas, ya sea por letras del alfabeto, números o simbolos (@, !, /), es decir, frases, nombres, oraciones, etc.

```
// Como puedes ver la variable esta identificada como palabra.
// Y se le asigna la frase "Esto es una cadena" como el valor a almacenar.

var palabra = "¡Esto es una cadena!";

var otraPalabra = "tucorreo@correo.com";
```

* ### Números Enteros.
Son el tipo de variables que almacenan un número limitado de números enteros es decir, que no tienen decimal, tales cual "10, 100, 2". 
<br/>
Los números enteros, en matemáticas, son el conjunto que contienen los números naturales de menos infinito a infinito positivo. Así pues las variables de enteros contienen números de ese conjunto, exceptuando los irracionales o decimales, que se redondean, si es que son el resultado de una operación.

![Recta Numérica](https://upload.wikimedia.org/wikipedia/commons/thumb/8/83/Integers-line.svg/706px-Integers-line.svg.png)

```
//Las variables NO pueden ser identificadas por un número, 
//deben de tener, al menos, una letra al inicio.

var diez = 10;

var iso1020 = 1000;
```

* ### Números Reales.
Conocido como "coma flotane" (*float point* en inglés) almacenan datos decimales muy pequeños o números muy grandes (gracias a una forma de notación científica usada en las computadoras)
```
//Números como 0.324984
//O resultados de operaciones aritméticas que tienen como resultado irracionales.

var pi = 3.14159265359;

var decimal = 0.00000534;
```
![Imagen de Pi](https://as01.epimg.net/tikitakas/imagenes/2017/03/14/portada/1489510011_902538_1489510263_sumario_normal.jpg)

* ### Valores lógicos.
Contienen solo dos tipos de valores, verdadero o falso (true // false) y están destinados a operaciónes lógicas o decisiones que dependan de un simple si o un no.

```
//No son los más usados, pero pueden llegar a ser de utilidad
//Si son asignados para automatizar tareas que requiran de valores no pre-definidos.

var si = true;
var no = false;
```

## Fuentes
* [Fing - Variables y tipos](https://www.fing.edu.uy/inco/cursos/fpr/wiki/index.php/Variables_y_Tipos)
* [Wikipedia - variables](https://es.wikipedia.org/wiki/Variable_(programaci%C3%B3n))
