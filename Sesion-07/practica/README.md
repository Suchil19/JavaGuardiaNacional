## Creación de actividades
- Diseña la interfaz de la actividad principal (MainActivity) con dos campos de texto (EditText) para ingresar los números y un botón para realizar la suma.

![Activity](img/01.png)
- En el archivo Java de la MainActivity, declara las variables para los elementos de la vista y agrega un listener al botón. En el método onClick, obtén los valores ingresados, conviértelos a enteros y realiza la suma.
- Utiliza un Intent para cambiar a la segunda actividad (Actividad2) y pasa el resultado de la suma como un extra.
- En la Actividad, recibe el Intent y muestra el resultado en un TextView.

![Activity](img/02.png)


- [Práctica Activity](practica)