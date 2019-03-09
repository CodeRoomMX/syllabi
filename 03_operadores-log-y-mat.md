# Operadores.
Son expresiónes que realizan acciones específicas, sirven para discriminar datos de entrada/salida, en dos tipos de resultados posibles, que son verdadero o falso (TRUE, FALSE) u operarlos matemáticamente.
<br/>
Existen dos grupos de operadores:
** Operadores Aritméticos.
** Expresiónes Booleanas.

* ## Operadores Aritméticos.
Son expresiónes que nos permiten hacer las operaciónes básicas de las matemáticas de la vida cotidiana como: sumar, restar, multiplicar, dividir.
<br/>
Sin embargo existen también expresiónes para las potencias y los residuos de divisiónes entre dos números. Los símbolos que usaremos en programación para lograr operar son:

```
const a = 10;
const b = 5;
let res;

+ //Para sumar dos o más números.
  //Ejemplo

res = a + b; //Si imprimes la variable res, el total de la suma debe ser 15.

- //Para restar.

res = a - b; //Al imprimir la variable res, el total de la resta debe ser 5.

* //(asterisco) para multiplicar.

res = a * b; //Al imprimir la variable res, el total de la multiplicación debe ser 50.

/ //(slash o diagonal) para dividir.

res = a / b; //Al imprimir la variable res, el total de la división debe ser 2;

** //Doble asterisco para elevar un número a cierta potencia.

res = a ** b; // Al imprimir la variable res, el total de elevar "a" a la potencia "b" debe ser 100,000.

% //Signo de porcentaje, que nos dá como resultado el resíduo de la división entre dos números.

res = a % b; //Al imprimir la variable res, el residuo de la operación debe ser 0.
```
Con estos operadores aritméticos se pueden construir operaciones más complejas haciendo uso de los paréntesis "()" y las corcheas "[]".
```
let total = 2*[2+(2+2)]; //El resultado al imprimir la variable total, debe ser 12.

```

* ## Expresiónes Booleanas.
Son expresiónes que son útiles al momento de evaluar y discriminar datos, dando como resultado true o false, es decir, verdadero o falso. Esto nos permite usarlos con otros metodos en programación para determinar si se continúa por uno u otro "camino" o si un ciclo se termina o continúa.
<br/>
Se dividen en dos grupos:
<br/>
* ### Operadores Lógicos.
#### AND (&&).
Sólo regresa **TRUE** si todos los datos son iguales a un mismo parámetro: **true**, si no, da como resultado false. Ejemplo:
```
x       y       (x&&y)
true    true    true

true    false   false

false   true    false

false   false   false
```
Cualquier dato que no sea igual a los otros hará que el resultado sea false (o todos coludos o todos rabones).

#### OR (||)
Regresa el resultado **TRUE**, si **uno solo** de los operandos es true.

```
x       y       (x||y)
true    true    true

true    false   true

false   true    true

false   false   false
```
Si ningún operando es igual a true, da como resultado **FALSE**.

#### NOT(!)
Invierte el valor del operando, es decir, si el operando es ** TRUE**, lo convierte en false. Ejemplo:
```
x       !x
true    false

false   true
```

* ### Operadores Relacionales.
Nos ayudan a evaluar cantidades (números), ver qué operando es mayor, menor, igual o diferente. Ejemplo:

```
//"Menor que", evalúa si "x" es MENOR a "y".
(x < y)

//"Menor o igual que", evalúa si "x" es MENOR O IGUAL a "y".
(x <= y)

//"Mayor que", evalúa si "x" es MAYOR que "y".
(x > y)

//"Mayor o igual que", evalúa si "x" es MAYOR O IGUAL que "y".
(x >= y)
```
También podemos usar variables para evaluar igualdades o in-igualdades entre cantidades u operandos.

```
//"Igual o similar a", evalúa si el operando es próximo o igual.
( x == y)

//"Exactamente igual a", evalúa si el operando es estrictamente igual.
(x === y)

//"In-igualdad", evalúa si entre los operandos hay algúna desigualdad, es decir, que no sean iguales o similares.
(x != y)
```
**PRECAUCIÓN**
<br/>
Ten en cuenta que el signo "=" (igual matemático) es el que utilizamos para asignar valores a las variables o constantes, por lo tanto, no nos sirve para operar como igualdad, es un error común usarlo en vez de "Igual a: ==".
=======

Los operadores son herramientas utilísimas en programación con las cuales podemos discriminar y evaluar entre distintos tipos de valores.