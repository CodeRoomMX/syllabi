# Built-in Functions
Son funciónes incluidas dentro del lenguaje de programación que usamos, como las herramientas que vienen dentro de un kit hazlo tu mismo (DIY), nos sirven para hacer un trabajo más eficiente y evitar construir funciones innecesarias o tardadas.
<br>
Dos ejemplos son:
## Math
Nos sirve para realizar operaciónes matemáticas específicas, como una raíz cuadrada, o elevar un número a una potencia "y", calcular seno o coseno, etc.
<br>
Por ejemplo:
```
//Nos regresa la raíz cuadrada de el número entre los paréntesis.

let rcuadrada = math.sqrt(9);

//Eleva x a la y potencia

let potencia = math.pow(10, 2);

//Regresa el coseno de x (el número debe estar en radianes)

let coseno = math.cosh(20);

//Prueba realizando las operaciónes en tu calculadora e imprimiendo las de muestra.

```
Exísten más propiedades que puedes probar, visita este [link](https://www.w3schools.com/jsref/jsref_obj_math.asp).

## Random
Es una propiedad de math, con la singularidad de que, al usarlo con la función math, nos regresa un número aleatorio.

```
//Esta variable nos debe regresar un número aleatorio entre el 0 y el 1, es decir, decimales.

let rn = math.random();

//Si queremos expresar un número entero, debenos hacer uso de la función floor() de la siguiente manera.

let rn = math.floor();

//Y dentro de los paréntesis de floor poner math.random() multiplicándolo por el máximo de números a elegir, mas uno.

let rn = math.floor(math.random()*10 + 1);

let rn = math.floor(math.random()*11);

```

Estas funciónes te serán útiles más adelante, continúa practicando para conocerlas lo suficiente y poder usarlas en otros programas.