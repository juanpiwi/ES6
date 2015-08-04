# ES6

## for..of

Crea un bucle de Iteración sobre objetos iterables (incluyendo Array, Map, Set, arguments object and so on)

### Diferencia entre for...of and for...in

**for..in**: itera sobre sobre el mombre de la propied

**for..of**: itera sobre el valor de la propiedad

```sh
let arr = [3, 5, 7];
arr.foo = "hello";

for (let i in arr) {
   console.log(i); // logs "0", "1", "2", "foo"
}

for (let i of arr) {
   console.log(i); // logs "3", "5", "7"
}
```

## let

Declara una variable de alcance local

### Diferencia entre let y bar

**let**: permite declarar variables con acceso limitado al bloque, declaracion, o expresion donde se esta usando

**var**: define una variable global, o local en una funcion sin importar el ambito del bloque

```sh
let var1 [= valor1] [, var2 [= valor2]] [, ..., varN [= valorN]];
```

ECMAScript compatibility table (https://kangax.github.io/compat-table/es6/) 



