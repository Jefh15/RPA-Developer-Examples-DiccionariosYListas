# RPA-Developer-Examples-DiccionariosYListas

Recapitulemos las actividades y los métodos utilizados

Comenzamos el proyecto como Secuencia e iniciaremos una instancia de la variable recién creada Diccionario mediante el uso de una Asignar actividad y la siguiente expresión: cities = new Dictionary(of String, List(Of String))

* Usamos 2 actividad Asignar para rellenar la Diccionario, con el nombre de un país como clave y varias ciudades de esos países como valores;

* Usamos una actividad Añadir a colección para agregar un nuevo nombre de ciudad ("Portland") en el valor correspondiente a la clave "EE. UU.", escribiendo el nombre de la ciudad en el campo Elemento en el panel Propiedades;

* Usamos una actividad Quitar de colección para eliminar un nombre de ciudad ("Londres") del valor correspondiente Lista. Para ello, "Londres" se insertó en el campo Elemento en el panel Propiedades;

* Usamos 2 actividades Registrar mensaje para mostrar los valores correspondientes a las 2 claves en Diccionario. 