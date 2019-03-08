# Funciones
<br/>

## ¿Qué es una función?
Podemos ver las funciónes como pequeñas máquinas las cuales, cuando reciben datos o una instrucción de ejecución, realizan un proceso, que puede repetirse las veces que sea necesario, ahorrandonos líneas de código (y tiempo).
<br/>
Las funciónes tienen una estructura y están conformadas por:

* El nombre de la función (si no tiene uno, se define como función anónima).
* El proceso de la función.
* Los datos de entrada (parámetros).
* Valores de retorno.

Ejemplo:

```
//Le decimos al programa que vamos a usar una función escribiendo la palabra reservada (en inglés) "function".

function...

//Separados con un espacio, asignamos el identificador o nombre de la función.

function miPrimeraFuncion...

//Se pone un par de paréntesis, en ellos se introducen los datos de entrada (parámetros) que vamos a recibir del exterior de la función, y, las llaves "{}" en dónde van a ir las instrucciónes que va a seguir esa función, ejemplo:


function miPrimeraFuncion(){
    let mssg = "Hello World!!!";

    console.log(mssg);
}
```

Para hacer uso de las funciónes que declaremos, debemos invocarlas, o llamarlas, por su identificador o nombre, el programa interpretará esto como: "Ok, quiere hacer uso de su función".

```
//Invocamos la función anterior con su nombre y el contenedor de los parametros.

miPrimeraFuncion();
```
Si queremos ingresar datos a la función, debemos ingresar las variables que los contienen, esto nos permite tomar resultados de otros procesos y usarlos para obtener un resultado distinto y/o decidir algo.

```
//Nuestras variables:
let a = 10;
let b = 5;

function sumatoria(a, b){
    let res = a + b
    
    return res;

}
```