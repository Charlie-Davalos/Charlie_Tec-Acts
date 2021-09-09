busqBinaria()
Análisis de complejidad temporal
La complejida temporal de la función es logarítmica para el peor de los casos, o O(log n). Esto porque por cada iteración, va descartando la mitad de los resultados. La desventaja es que para que funcione, el arreglo debe de estar ordenado


busqSecuencial()
Análisis de complejidad temporal
Es lineal para el peor de los casos = O(n). Esto porque tiene que recorrer todo el arreglo para buscar el valor.


ordenaMerge()
Análisis de complejidad temporal
Es O(n*log n) porque divide el arreglo en mitades hasta que ya no se pueda más y luego le toma un tiempo lineal en volverlas a juntar ya acomodadas.

Análisis de complejidad espacial
Es lineal = O(n) porque, al menos en este algoritmo de merge sort, se tiene que crear una copia de del arreglo para hacer el sort de manera correcta y más fácil.


ordenaBurbuja()
Análisis de complejidad temporal
Es la misma que la de la función ordenaSeleccion() ya que, si bien no es el mismo algoritmo, recorren el arreglo de la misma forma, con un doble for loop anidado. Y es por eso que la complejidad también es casi O(n^2).


ordenaSeleccion()
Análisis de complejidad temporal
O(n^2)
