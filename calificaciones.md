Algoritmo Tarea_sesion_2 	
	Escribir "Calculo del promedio ponderado"
	Escribir "primero ingrese el valor de cada nota del estudiante"
	Leer parcial1
	Leer parcial2
	Leer participacion
	leer examenfinal
	
	Escribir "luego multiplique el valor de cada nota por el peso porcentual de cada nota"
	notaponderadaparcial1=parcial1*0.25
	notaponderadaparcial2=parcial2*0.25
	notaponderadaparticipacion=participacion*0.20
	notaponderadaexamenfina=examenfinal*0.30
	
	Escribir "luego calcule el promedio ponderado"
	promedioponderadocurso=notaponderadaparcial1+notaponderadaparcial2+notaponderadaparticipacion+notaponderadaexamenfina
	
	Escribir "la nota ponderada del estudiante en el curso es: ", promedioponderadocurso
	
	
FinAlgoritmo

