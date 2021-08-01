# Tarea-3
tarea 3


Para poder probar las funcionalidades del programa hay que ejecutar la clase Tarea3Test.java. El resto de las clases Test permiten probar funcionalidades de clases de
tareas anteriores.

//tarea1 La idea del programa es encapsular los tipos primitivos de java en clases que permitan abstraer el funcionamiento de estos tipos. Para eso cada clase se puede transformar en algunas de las otras dependiendo de cuál sea mediante un método.

Para la realización de las operaciones entre clases se utiliza el patrón de diseño Double Dispatch, y dado que no existía simetría entre las operaciones de todas las clases se tuvo que crear varias interfaces para poder simplificar las operaciones entre clases. Las funciones que cumplen lo pedido son x.suma(y), x.resta(y), x.multiplicación(y), x.division(y), x.Or(y), x.And(y) y x.negacion().

//tarea2 Ademas se pueden crear árboles de sintáxis abstracta con las operaciones Add, Sub, Mult, Div, And, Or y Neg. Estos pueden ser evaluados entregando el tipo de la tarea1 que se obtiene al operar los nodos del arbol. Se agregan Factories para cada uno de los tipos de la primera tarea, implementando el patron Flyweight para poder optimizar la memoria.


//tarea3 Se agregan instrucciones de control de flujo(If y While), las cuales funcionaran de manera similar a los arboles de la tarea 2. Ademas se agregaron algunas clases de
comparacion que entregan un Bool True o False dependiendo de la comparacion. Tambien se implementaron las variables Var que permiten que un String id se relacione
con algun valor que puede cambiar usando HashTable.

