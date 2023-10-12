# promedio-calificasion-
manuel eduardo christian himanol
var nombre = prompt("Bienvenido, ingresa tu nombre");
var numMaterias = parseInt(prompt("¿Cuántas materias tienes? "));

var totalCalificaciones = 0;

for (var i = 0; i < numMaterias; i++) {
    var calificaciones = parseFloat(prompt("Ingresa la calificación de la materia " + (i + 1) + ": "));
    totalCalificaciones += calificaciones;
}

var promedio = totalCalificaciones / numMaterias;


console.log("Bienvenido, " + nombre +"!!!!!!" );
console.log("Tu promedio en " + numMaterias + " materias es: " +promedio);

