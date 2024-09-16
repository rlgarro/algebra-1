## Ejercicio 10. Sean  A = {1,2,3,4,5} y B = {1,2,3,4,5,6,7,8,9,10,11,12}. Sea F el conjunto de todas las funciones f : A -> B.

### (a) Cuantos elementos tiene el conjunto F?

La respuesta es la cantidad de funciones f de A a B posibles.

#B^(#A) = $12 ^ 5$

### (b) Cuantos elementos tiene el conjunto {f $\in F : 10 \notin$ Im(f)}?

Es importante siempre tratar de interpretar y tratar estas cosas con conjuntos bien definidos. En este caso esta dado, busco el cardinal de C = {f $\in$ F : 10 $\notin\$ Im(f)}

Es decir, para cualquier a $\in$ A en cualquiera de las funciones no se puede dar que 
f(a) = 10.

Entonces f va de A a un subconjunto de B que no contiene unicamente al 10 pero al resto si. En este caso el conjunto: D = {1,2,3,4,5,6,7,8,9,11,12}.

Por lo tanto la cantidad de funciones son #D^(#A) = $11^5$

### (c) Cuantos elementos tiene el conjunto {f $\in F : 10 \in$ Im(f)}?

Es importante ver que para desarrollar una suma de cardinales de conjuntos disjuntos en este caso es dificil por la cantidad distinta de casos que existen. Es mejor obtener el cardinal del conjunto de las funciones que nunca tienen al 10 en la imagen de f y restarlo al cardinal de todas las funciones.

En este caso el cardinal de las funcionese que nunca tienen al 10 lo tenemos y es 11^5 por el inciso anterior.


Luego la respuesta es: $12 ^ 5 - 11 ^ 5$

### (d) Cuantos elementos tiene el conjunto {f $\in F : f(1) \in$ {2,4,6}}?

En este caso f(1) $\in$ {2,4,6} (3 posibilidades) pero el resto de a \in A del dominio pueden tener cualquier valor al aplicarle la funcion, es decir 12 posibilidades.

f(1) : 3
f(2) : 12
f(3) : 12
f(4) : 12
f(5) : 12

Rta:

3 * $12^4$
