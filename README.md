# Metodos de Ordenamiento

El ordenamiento es una labor común que realizamos continuamente. ¿Pero te has preguntado qué es ordenar? ¿No? Es que es algo tan corriente en nuestras vidas que no nos detenemos a pensar en ello. Ordenar es simplemente colocar información de una manera especial basándonos en un criterio de ordenamiento.

![descarga](https://user-images.githubusercontent.com/72088585/97351123-f2852c00-1856-11eb-957e-891fd9c0e0d5.png)


En la computación el ordenamiento de datos también cumple un rol muy importante, ya sea como un fin en sí o como parte de otros procedimientos más complejos. Se han desarrollado muchas técnicas en este ámbito, cada una con características específicas, y con ventajas y desventajas sobre las demás.

Estos metodos se dividen en dos partes: 

+Algoritmos de ordenamiento internos

+Algoritmos de ordenamiento externos

A continuacion ejemplificaremos el método mas popular de estos:

# Metodo de la burbuja (ordenamiento interno)

El método de la burbuja es un método de ordenación no natural para ordenar arrays. Consiste en ir recorriendo todo el array a ordenar, comparando dos elementos al mismo tiempo e intercambiándolos si no están en el lugar apropiado. Al finalizar el recorrido por todos los elementos, se determina si hubo algún cambio, y en caso afirmativo, se repite el algoritmo hasta que no haya cambio alguno.
Por ejemplo:
![orden-2 1](https://user-images.githubusercontent.com/72088585/97352047-2f9dee00-1858-11eb-9dc8-a29354d38b87.png)

El nombre que se le atribuye viene porque al hacer el intercambio, los elementos más pequeños “burbujean” de forma progresiva hasta el inicio del array, mientras que los más grandes se “hunden”. Es el algoritmo de ordenación por comparación más sencillo de implementar.

En cuanto al rendimiento, el algoritmo no destaca por su rapidez.  Es de los más pobres en rendimiento y sobre todo no es recomendable usarlo en arrays largos. Sin embargo, está bastante bien si estás empezando ya que se caracteriza por su sencillez.

A continuacion presentaremos un ejemplo de uso en C++.

# Ordenamiento de Arrays de menor a mayor

![Sin título](https://user-images.githubusercontent.com/72088585/97354328-d4b9c600-185a-11eb-8451-1cdb92d1a99c.png)

Este programa se conforma de cuatro partes, el primero es el main encargado de llamar las funciones empleadas para realizar el proceso, estas funciones se dividen en tres, cada uno tiene una tarea que realizar como recibir, ordenar y proyectar los datos que introduzca el usuario.

![Sin título](https://user-images.githubusercontent.com/72088585/97355516-9e7d4600-185c-11eb-80fb-1824106c835c.png)

El segundo segmento es la función “rellenarArray”, este tiene la tarea de recibir los datos propuestos por el usuario, y ordenarlos del 1 al 10 a como fueron introducidos, esto con el objetivo de ser procesados por la siguiente función.

![Sin título](https://user-images.githubusercontent.com/72088585/97358529-fd44be80-1860-11eb-9ebc-670b59087b34.png)

El tercer segmento es la función “ordenarArray”, como lo menciona su nombre este tiene la labor de ordenar todos los números ingresaros por el usuario en la instrucción anterior, para ello hace uso del método de burbuja, con la ayuda de un if compara dos valores, si uno resulta mayor que otro este será movido de lugar con la ayuda de un for el cual recibirá la instrucción y manipulara a la vez el orden del for del anterior función, todo esto con ayuda de una variable temporal que reciba el valor resultante de la primera instrucción.

![Sin título](https://user-images.githubusercontent.com/72088585/97357761-e5b90600-185f-11eb-9e7e-01c1dcaff1e1.png)

El cuarto y ultimo segmento es la función “mostrarArray”, su función solo es mostrar en pantalla el for de los valores introducidos de la primera función, una vez que la segunda función se allá ejecutado.

![Sin título](https://user-images.githubusercontent.com/72088585/97358276-a50dbc80-1860-11eb-9e59-95e65bddb32c.png)

# Ejecución del programa.

Se ordenará la siguiente lista de números introducidos:

![2](https://user-images.githubusercontent.com/72088585/97358830-6e847180-1861-11eb-8ac4-d3c23ed63d90.png)

Se ejecuta la tarea y el resultado es el siguiente:

![2](https://user-images.githubusercontent.com/72088585/97358901-8b20a980-1861-11eb-82f1-763103399ffc.png)
