# Factory Function
Como lo dice su nombre, son funciónes que actuan como fabricas creando objetos "nuevos" 
<br>

```
//Un ejemplo sencillo de una factory function es la siguiente.
//Declaramos la función con su respectivo identificador y los datos que le vamos a pasar para construir el objeto, por ejemplo, color, nombre, etc, etc.

function objectFactory(nombre, apellido, edad, puesto){
  return {
    nombre: nombre,
    apellido: apellido,
    edad: edad,
    puesto: puesto
  }
}

//Lo primero que notamos al declarar la función es que ésta misma solo hace un return de un objeto con los parámetros de la función
//asi que dentro del objeto la propiedad nombre tiene como valor asignado el nombre que nosotros asignemos más adelante

const newObject = objectFactory("Pablo", "Martinez", 26, "Web Developer & programmer Jr");

//Para construir un objeto nuevo basta con crear una nueva variable o constante con el nombre del objeto a crear
//Le asignamos la función objectFactory con los datos que nosotros queremos dentro de los paréntesis.
//RECUERDA: si es texto debe ir entre comillas dobles o simples, si son números solos, pero siembre deben de ir separads por comas y en el orden en el que están declaradas.

console.log(newObject);

//Por último para probar que estamos creando un objeto lo imprimimos en consola con el identificador de la constante, en este caso.
//Si queremos imprimir un valor en específico del objeto simpemente debemos hacer lo siguiente.
//Escribir el nombre del objeto agregar un punto seguido y escribir el nombre del valor a imprimir.

console.log(newObject.nombre) //"Pablo"

//Otra forma de crear una factory function es, utilizando las nuevas características de ECS6
//Asignamos a una constante un identificador según el tipo de objeto que vayamos a crear
//Así mismo le asignamos los parámetros que va a recibir, utilizamos una arrow function para establecer que es una función y dentro utilizamos return para que nos devuelva el objeto.


const objectFactory2 = (nombre1, apellido1, edad1, puesto1) => {
  return {
    nombre: nombre1,
    apellido: apellido1,
    edad: edad1,
    puesto: puesto1
  }
}

const anotherObject = objectFactory2("Patrick", "Knott", 25, "Web Developer Jr");

console.log(anotherObject);

```

Estos ejemplos son de factory functions "básicas" que, con el uso de otras formas de programación en javascript, podemos ir haciendo más complejas, de tal forma que los objetos no tengan solamente atributos, si no también sean capaces de interactuar con otros objetos o reaccionar a eventos que establezcamos.
