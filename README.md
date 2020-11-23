# PRACTICA7
codigos en C
// Seleccion de librerias
#include<stdio.h>

// Declaracion de variables globales
int edadDeAlumnos;

// Declaraci�n de Funciones
int main(){
	// Declaracion de variables locales
	char ALUMNO=20;
	int edades;
	float operacion=10;
	// Bloque de INstrucciones
	printf("Escribe la edad");
	scanf("%i",&edades);
	
	operacion=edades+20;
	printf(":\n %f", operacion);
	
	return 0;
}

