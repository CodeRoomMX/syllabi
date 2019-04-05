# Programación Orientada a Objetos

La programación orientada a objetos es un paradígma de la programación, es decir, es una forma en la cual nosotros podemos resolver una problematica a partir de clases y objetos.
</br>
Ya hemos visto anteriormente qué es un objeto, pero ¿Qué es una clase? ¿Qué es una instancia?

## Clases
Si tomamos dos objetos como dos lápices, uno convencional y otro especializado para dibujo, notaremos que ambos tienen atributos diferentes entre si, a pesar de ser la misma clase de objeto, es decir, un lápiz.
</br>
Si a un objeto le quitamos todos los atributos que los diferencían entre si y dejamos sólo las características en común, tendremos una plantilla de un lápiz, la estructura primaria, el esqueleto, algo con lo que podemos diseñar nuevos lápices con atributos diversos, diferentes entre si, pero con una estructura en común.
</br>
A esas "plantillas" se les conoce como clases.
</br>
Desde ES6 contamos con la palabra reservada "class" para poder crear clases, y, a partir de ellas, objetos.
```
//definimos el nombre de la clase
class lapiz{
	constructor(color, forma, largo){ //creamos el constructor con los atributos o caracteristicas del objeto
	this.color = color;
	this.forma = forma;
	this.largo = largo;
	}
}

//Listo, tenemos una clase... continuemos.
```

## Instancias
A la creación de un nuevo objeto, en programación, lo conocemos como instancias... y eso. Veamos unos ejemplos.

```
//Declaramos una nueva variable con el nombre de nuestro nuevo objeto.
//Le asignamos la palabra reservada new, que sirve para crear nuevos objetos de una clase.
//Entre parétesis agregamos los atributos que querramos que lleve el objeto.

let lapizRojo = new lapiz("rojo", "hexagonal", "25cm");


//Para comprobar que nuestro objeto fue creado usemos console log sobre uno de los atributos de nuestro nuevo objeto

console.log(lapizRojo.color);

//Listo ;)

```
