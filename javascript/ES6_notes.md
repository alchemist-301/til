# EcmaScript 5 - 6
## EcmaScript 5
ECMAScript 5 también se conoce como ES5 y ECMAScript 2009

En esta ocacion aprenderemos Ecmascript 5 tambien conocido como ES5 o Ecmascript2009.

Entre las principales caracteristicas del EcmaScript 5 nos encontramos:

* ["use strict"](#uso-de-la-directiva-de-use-strict)
* [String.trim()](#stringtrimp)
* [Array.isArray()](#arrayisarray)
* [Array.map()](#arraymap)
* [Array.forEach()](#arrayforeach)
* [Array.filter()](#arrayfilter)
* [Array.reduce()](#arrayreduce)
* [Array.reduceRight()](#arrayreduceright)
* [Array.every()](#arrayevery)
* [Array.some()](#arraysome)
* [Array.indexOf()](#arrayindexof)
* [Array.lastIndexOf()](#arraylastindexof)
* [JSON.parse()](#jsonparse)
* [JSON.stringify()](#jsonstringify)
* [Date.now()](#datenow)

## Algunos cambios en la sintaxis
* Acceso a la propiedad [] en cadenas
* Comas finales en las matrices y literales de objetos.
* Literales de cadena multilinea
* Palabras reservadas como nombres de propiedad.

#### Uso de la Directiva de "Use strict"
```"use strict"``` define que el codigo js debe ejecutarse en modo estricto. Con el modo estricto podemos no usar variables no declaradas.

#### Const antes de Let y Let antes que Var
La declaración  ```let``` nos permite declarar una variable con alcance de bloque.

```javascript
 var x = 10;
// Here x is 10
{
  let x = 2;
  // Here x is 2
}
// Here x is 10 
```

La declaración ```const``` nos permite declarar una constante (una variable de JavaScript con un valor constante).

Las constantes son similares a las variables let, excepto que el valor no se puede cambiar.
``` js
 var x = 10;
// Here x is 10
{
  const x = 2;
  // Here x is 2
}
// Here x is 10 
```

Funciones de tipo flecha
```javascript
var x = function(x,y){
  return x*y;
}
```

```javascript
ES5
const x = (x, y) => x * y;
```
#### String.trimp()
```String.trim()``` Elimina el espacio en blanco de ambos lados de una cadena.

#### Array.trim()

#### Array.isArray()

#### Array.map()

#### Array.forEach()

#### Array.filter()

#### Array.reduce()

#### Array.reduceRight()

#### Array.every()

#### Array.some()

#### Array.indexOf()

#### Array.lastIndexOf()

#### JSON.parse()

#### JSON.stringify()

#### Date.now()



## EcmaScript 6 




# Buenas Practicas
