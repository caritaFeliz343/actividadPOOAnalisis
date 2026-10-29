# Desarrollo actividad análisis de código y dependencia
### Estudiante: Christian Espinoza S.

Clases identificadas: Clase calculadora, Clase CarroCompra.
La clase calculadora representa una calculadora de 2 enteros, los cuales son atributos de la clase. Estos se pueden sumar y multiplicar. 
Tiene 2 constructores, el primero que no recibe ningún parámetro, y el segundo que recibe 2 enteros. Además, en el primer constructor, los enteros son inicializados igualándolos a 0, mientras que el segundo constructor asigna los 2 parámetros a cada atributo. Por último, cada entero se puede asignar con su setter.

La clase CarroCompra representa un carrito de compras que el cual tiene un arreglo de enteros de 2 dimensiones, específicamente 2 filas con 5 columnas, aceptando así 10 números.
Tiene un constructor, el cual se encarga de asignar a toda la primera fila con 1, y toda la segunda fila con 1000.  Permite calcular el total, recorriendo cada espacio de la matriz y sumándolos, además de luego poder mostrar el total. Por último, puede instanciar a la clase Calculadora, para así poder calcular el subtotal, que sería calcular el valor de un producto dependiendo de su cantidad.

Como contexto del problema, es una persona que puede comprar 10 productos. Ha esta persona le interesa saber el total de la compra, y el subtotal por producto. 

Entre las clases, existe una dependencia, ya que la clase CarroCompra depende de la clase Calculadora.
Aquí se puede ver una representación utilizando Visual Paradigm.

