# ¿Qué son los eventos y cómo se utilízan?

Son sucesos que tienen lugar en el sistema cuando un usuario ejecuta una acción, es decir, si un usuario en una página o una aplicación llega a dar clic a cierto boton o cuardo, se puede, o no, dar una acción.
</br>
En javascript tenemos predefinidos varios eventos que podemos utilizar, sin embargo, en este curso solo veremos 3 tipos.
</br>
* KeyUp/KeyDown
* MouseUp/MouseDown
* Click

Empecemos por el principio.

Entra a [JSBin](https://jsbin.com) para poder hacer tu práctica de forma rápida.
```
//Primero debemos saber cómo funciona la selección de consultas (query) en javascript.
//crea en tu html una etiqueta div con un id similar y dale un estilo simple con css.

<style>
#target{
  width: 100px;
  height; 100px;
  background-color: blue;
}
</style>

<div id="target"></div>

//En nuestro javascript haremos la selección de este elemento de la siguiente forma:
//declaramos una variable y le asignamos la selección de un elemento del documento en el que trabajamos.

let realTarget = document.querySelector('#target');

//Con esta selección hecha podemos proseguir
//al objeto de nuestro documento seleccionado le vamos a dar la propiedad Event Listener de la siguiente forma:
//addEventListener recibe dos parámetros, uno es el evento y el otro la acción que desencadena.
//utilizaremos click
//Podemos incluir la funcion dentro del listener (fig 1.1) o crearla fuera de y después invocarla (fig 1.2).

//fig 1.1
realTarget.addEventListener("click", function(){

});

//fig 1.2
realTarget.addEventListener("click", miFuncion);

function miFuncion(){

}

//Dentro de la función va la acción que llevará a cabo el código, en este caso, para fines prácticos, simplemente enviaremos una alerta.

function miFuncion(){
  alert("Esto si está funcionando!!!");
}


//Prueba el mismo evento con mouseup y mousedown 
```

## Click
Este evento se desencadena unicamente cuando el usuario hace clic con el puntero sobre el objeto deseado, que para fines prácticos, puede ser cualquiera que el desarrollador decida o el que por cuestiones de diseño se establezca.

## Mouse Up
El evento se desencadena cuando con el botón derecho del mouse has hecho clic y luego sueltas el botón, o lo liberas, del elemento seleccionado.

## Mouse Down
Es, en una forma práctica, similar al Mouse Up... simplemente en sentido inverso, la acción se desencadena cuando presionas el botón derecho del mouse.
<br>
<br>
<br>

## Key Up
El evento se desencadena cuando una tecla es liberada.

## Key Down
El evento se desencadena cuando una tecla es presionada.
```
//En este ejemplo utilizaremos el indicador window para hacerlo nuestro listener
//Esto con la finalidad de que todo el documento sobre el que trabajamos esté escuchando por el desencadenante.

window.addEventListener("keyup", keyupFunction);

function keyupFunction(){
  alert('Esto es otra sensual función');
}


//Repite el proceso con keydown y pruébalo.

```

Como ya vimos, estos eventos nos sirven al momento de interactuar la página con el usuario, más comunmente, cuando se tiene la intención de que hay una interacción dinámica entre el usuario y la aplicación o página, por ejemplo, un juego desde el browser.

¿Dudas?
