Este codigo fue probado en el editor de texto en linea Repl.it

Análisis de complejidad de los algoritmos

Función: add(T val)
Análisis de complejidad temporal

Al contrario de la lista simple, como aquí podemos guardar el último nodo de la lista en una variable, el tiempo que se requiere para añadir un nuevo elemento es constante, osea O(1), porque ya no tenemos que recorre toda la lista.

Función: find(T val)
Análisis de complejidad temporal

Para el peor de los casos, el elemento a buscar está hasta el final de la lista, por lo que igual tendría que recorrer toda la lista de forma lineal y es por esto que también tiene una complejidad O(n).

Función: update(int index, T val)
Análisis de complejidad temporal

Ocurre lo mismo que con la función find(), en caso de que el elemento a modificar se encuentre hasta el final de la lista, tendría que recorrerla toda. Es por esto que su complejidad es O(n).

Función: remove(int index)
Análisis de complejidad temporal

De igual manera, para eliminar un elemento, tiene que recorrer todos los nodos anteriores a ese. En el peor de los casos, tendría que recorrer toda la lista, la complejidad para este caso sería O(n)
