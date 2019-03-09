# Arreglos
Son, (básicamente) listas.
<br>
Para entender de qué se tratan, primero, debemos enteder cómo es que están formadas, su estructura, y así, entender cómo es que nos son útiles dentro de nuestros códigos.
```
//Definimos una variable contenedora del arreglo.
//Entre los brackets insertaremos los elementos que la conformarán.

let list = [];

//Asignamos una lista de "cosas", por ejemplo:

let list = ["leche", "huevos", "pan"];

//Los elementos dentro del arreglo tienen una posición con la que se identifican, dentro de la lista el primer identificador es el número 0, es decir, la lista empieza en 0. Así dentro de nuestro arreglo muestra la palabra "leche" tiene una posición 0.

let list = ["leche", "huevos", "pan"];
//Posición:    0        1        2

```
Podemos, entonces, tomar cualquier valor del arreglo y utilizarlo.
<br/>
Si hacemos console.log a una posición 0 del arreglo, el item que se imprimiría en consola debería ser: "leche".
<br/>
Si quisieramos recorrer e imprimir el arreglo completo podemos hacer uso del ciclo for de la siguiente manera:
```
//Declaramos nuestra lista, suemos la misma lista anterior.

let list = ["leche", "huevos", "pan"];

// luego hacemos un ciclo for, poniendo como condicional el largo de la lista, lo expresamos de la siguiente forma: "i>=list.length".
//Que quiere decir: si i es mayor o igual a el largo de la variable "lista".
//Asignamos una variable item que va a contener cada uno de los elementos de la lista cada vez que el ciclo for la recorra
//E imprimimos cada item.

for(let i = 0; i>=list.length; i++){

    let item = list[i];

    console.log(item);
}
```
Así podemos obtener todos los items del arreglo y recorrerlo completo.