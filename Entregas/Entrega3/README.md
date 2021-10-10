# Documentación funciones Entrega 3

Las siguientes funciones son de tipo void, se invocan sin necesidad de usar console.log(), cada una al invocarse mostrará en consola el resultado correspondiente: 

// La cantidad total de estudiantes que hay en el colegio.
totalEstudiantes(colegio);

// La cantidad total de estudiantes que hay en primaria.
estudiantesSeccion(primaria);

// La cantidad total de estudiantes que hay en bachillerato.
estudiantesSeccion(secundaria);

// La cantidad total de niños que hay en el colegio.
totalGenero(colegio, 'niños');

// La cantidad total de niñas que hay en el colegio.
totalGenero(colegio, 'niñas');

// La cantidad total de niños que hay en primaria.
totalGeneroSeccion(primaria, 'niños');

// La cantidad total de niñas que hay en primaria.
totalGeneroSeccion(primaria, 'niñas');

// La cantidad total de niños que hay en bachillerato.
totalGeneroSeccion(secundaria, 'niños');

// La cantidad total de niñas que hay en bachillerato.
totalGeneroSeccion(secundaria, 'niñas');

// La media de las notas en el colegio.
mediaNotasColegio(colegio);

// La media de las notas en el bachillerato.
mediaNotasSeccion(secundaria);

// La media de las notas en la primaria.
mediaNotasSeccion(primaria);

// La media de las notas de un grado seleccionado por parametro.
mediaNotasGrado('cuarto');

// La media de las notas de un grado seleccionado por parametro.
mediaNotasCurso('cuarto', 'B');

// La moda de las notas en el colegio.
modaNotasColegio(colegio);

// La moda de las notas en el bachillerato.
modaNotasSeccion(secundaria);

// La moda de las notas en la primaria.
modaNotasSeccion(primaria);

// La moda de las notas de un grado seleccionado por parametro.
modaNotasGrado('cuarto');

// La moda de las notas de un grado seleccionado por parametro.
modaNotasCurso('cuarto', 'B');

// La mediana de las notas en el colegio.
medianaNotasColegio(colegio);

// La mediana de las notas en el bachillerato.
medianaNotasSeccion(secundaria);

// La mediana de las notas en la primaria.
medianaNotasSeccion(primaria);

// La mediana de las notas de un grado seleccionado por parametro.
medianaNotasGrado('cuarto');

// La mediana de las notas de un grado seleccionado por parametro.
medianaNotasCurso('cuarto', 'B');

//Seleccionar el estudiante con mejor nota en promedio en cada materia.
mejorPromedioMateria('historia');
mejorPromedioMateria('matematicas');
mejorPromedioMateria('filosofia');
mejorPromedioMateria('religion');
mejorPromedioMateria('artes');
mejorPromedioMateria('educacion_fisica');
mejorPromedioMateria('biologia');
mejorPromedioMateria('quimica');
mejorPromedioMateria('fisica');

//Seleccionar el estudiante con mejor nota en promedio en el curso.
mejorPromedioCurso('quinto', 'B');

//Seleccionar el estudiante con mejor nota en promedio en el grado.
mejorPromedioGrado('once');

//Seleccionar el estudiante con mejor nota en promedio en primaria.
mejorPromedioSeccion(primaria);

//Seleccionar el estudiante con mejor nota en promedio en secundaria.
mejorPromedioSeccion(secundaria);

// Seleccionar el estudiante con mejor nota en promedio en el colegio.
mejorPromedioColegio(colegio);


Esta funcion retorna un objeto estudiante con la informacion del estudiante que se está buscando por el parámetro nombre, si no lo encuentra retorna una cadena de caracteres con un mensaje correspondiente a que la busqueda no tuvo exito

- Buscar un estudiante que pertenezca a un grado seleccionado por parametro.
console.log(buscarEstudianteGrado('Murray Knox', 'once'));
console.log(buscarEstudianteGrado('Boone Lang', 'quinto'));
