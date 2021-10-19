# Documentación funciones Entrega 3

## Constantes

Se crearon las constantes Colegio, Primaria, Secundaria para facilitar el acceso a estos datos en las funciones a desarrollar 

- const colegio = data[0].colegio;
- const primaria = data[0].colegio.primaria[0];
- const secundaria = data[0].colegio.secundaria[0]; 

## Funciones principales

Las siguientes funciones son de tipo void, se invocan sin necesidad de usar console.log(), cada una al invocarse mostrará en consola el resultado correspondiente: 

- La función muestra la cantidad total de estudiantes que hay en el colegio, recibe como parametro la constante colegio definida previamente
> totalEstudiantes(colegio);  

- La función muestra la cantidad total de estudiantes que hay en una sección, recibe como parámetro una de las dos constantes definidas previamente como primaria o secundaria. 
> estudiantesSeccion(primaria);

> estudiantesSeccion(secundaria);

- La función muestra la cantidad total de niños o niñas que hay en el colegio. Recibe dos parámetros la constante colegio y una cadena de caracteres con la palabra 'niños' o 'niñas' dependiendo de la información que se quiera consultar
> totalGenero(colegio, 'niños');

> totalGenero(colegio, 'niñas');

- La función muestra la cantidad total de niños o niñas que hay en una sección del colegio, ya sea primaria o secundaria. Recibe como parámetros una de las constantes definidas, primaria o secundaria y una cadena de carácteres, 'niños' o 'niñas', dependiendo de la información que se quiera consultar. 
> totalGeneroSeccion(primaria, 'niños');

> totalGeneroSeccion(primaria, 'niñas');

> totalGeneroSeccion(secundaria, 'niños');

> totalGeneroSeccion(secundaria, 'niñas');

- La función muestra la media de las notas en el colegio, recibe como parámetro la constante predefinida colegio.
> mediaNotasColegio(colegio);

- La función muestra la media de las notas en una sección del colegio. Recibe como parámetro una de las constantes definidas previamente, ya sea primaria o secundaria, dependiendo de la información que se quiera consultar.
> mediaNotasSeccion(secundaria);

> mediaNotasSeccion(primaria);

- La función muestra la media de las notas de un grado ingresado por parametro. El grado se debe ingresar en minuscula como una cadena de caracteres. EJ: 'cuarto', 'quinto', 'once', etc.
> mediaNotasGrado('cuarto');

- La función muestra la media de las notas de un curso. Recibe dos cadenas de carácteres por parámetros, en primer lugar el grado y luego el curso ya sea 'A' o 'B'. EJ: 'sexto','A'
> mediaNotasCurso('cuarto', 'B');

- La función muestra la moda de las notas en el colegio, recibe como parámetro la constante predefinida colegio.
> modaNotasColegio(colegio);

- La función muestra la moda de las notas en una sección del colegio. Recibe como parámetro una de las constantes definidas previamente, ya sea primaria o secundaria, dependiendo de la información que se quiera consultar.
> modaNotasSeccion(secundaria);

> modaNotasSeccion(primaria);

- La función muestra la moda de las notas de un grado ingresado por parametro. El grado se debe ingresar en minuscula como una cadena de caracteres. EJ: 'cuarto', 'quinto', 'once', etc.
> modaNotasGrado('sexto');

- La función muestra la moda de las notas de un curso. Recibe dos cadenas de carácteres por parámetros, en primer lugar el grado y luego el curso ya sea 'A' o 'B'. EJ: 'sexto','A'
> modaNotasCurso('quinto', 'A');

- La función muestra la moda de las notas en el colegio, recibe como parámetro la constante predefinida colegio.
> medianaNotasColegio(colegio);

- La función muestra la moda de las notas en una sección del colegio. Recibe como parámetro una de las constantes definidas previamente, ya sea primaria o secundaria, dependiendo de la información que se quiera consultar.
> medianaNotasSeccion(secundaria);

> medianaNotasSeccion(primaria);

- La función muestra la moda de las notas de un grado ingresado por parametro. El grado se debe ingresar en minuscula como una cadena de caracteres. EJ: 'cuarto', 'quinto', 'once', etc.
> medianaNotasGrado('noveno');

- La función muestra la moda de las notas de un curso. Recibe dos cadenas de carácteres por parámetros, en primer lugar el grado y luego el curso ya sea 'A' o 'B'. EJ: 'sexto','A'
> medianaNotasCurso('once', 'B');

- La función muestra el nombre del estudiante con mejor nota en promedio en cada materia. Recibe una cadena de carácteres como parámetro la cual indica de cual materia se quiere ver el mejor estudiante EJ: 'historia', 'religion'
> mejorPromedioMateria('historia');

> mejorPromedioMateria('matematicas');

> mejorPromedioMateria('filosofia');

> mejorPromedioMateria('religion');

> mejorPromedioMateria('artes');

> mejorPromedioMateria('educacion_fisica');

> mejorPromedioMateria('biologia');

> mejorPromedioMateria('quimica');

> mejorPromedioMateria('fisica');

- La función muestra el nombre del estudiante con mejor nota en promedio en el curso. Recibe dos cadenas de carácteres por parámetro, en primer lugar el grado escrito en minusculas ('primero', 'tercero') y el curso escrito en mayuscula ya sea 'A' o 'B'
> mejorPromedioCurso('quinto', 'B');

- La función muestra el nombre del estudiante con mejor nota en promedio en el grado. Recibe una cadena de carácteres como parámetro referente al grado escrito en minusculas. EJ: 'tercero', 'septimo'
> mejorPromedioGrado('once');

- La función muestra el nombre del estudiante con mejor nota en promedio en una seccion del colegio. Recibe como parámetro una de las constantes definidas previamente, primaria o secundaria.
> mejorPromedioSeccion(primaria);

> mejorPromedioSeccion(secundaria);

- La función muestra el nombre del estudiante con mejor nota en promedio en el colegio. Recibe como parámetro la constante predefinida colegio.
> mejorPromedioColegio(colegio);

Esta funcion retorna un objeto estudiante con la informacion del estudiante que se está buscando por el parámetro nombre, si no lo encuentra retorna una cadena de caracteres con un mensaje correspondiente a que la busqueda no tuvo exito

- Buscar un estudiante que pertenezca a un grado seleccionado por parametro.

> console.log(buscarEstudianteGrado('Murray Knox', 'once'));

## Funciones auxiliares

- La función retorna un arreglo con la información del grado ingresado. Recibe una cadena de carácteres referente al grado que se desee consultar. En caso de que se ingrese un grado incorrecto, se mostrará un mensaje de error en la consola
> obtenerGrado('once')

- La función permite calcular la moda de un conjunto de números. Recibe como parámetro un arreglo con datos de tipo Number y retorna la moda como un dato de tipo Number
> moda(numeros)

- La función permite calcular la mediana de un conjunto de números. Recibe como parámetro un arreglo con datos de tipo Number y retorna la moda como un dato de tipo Number
> mediana(arreglo)
