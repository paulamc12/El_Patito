# El_Patito

// Mejora de código para permitir que se sigan calculando promedio
Algoritmo Promedio
	
	Definir p Como Caracter;
	Repetir
	   Escribir "Ingrese la cantidad de datos:"
	   Leer n
	   acum<-0
	   Para i<-0 Hasta n-1 Hacer
		    Escribir "Ingrese el dato ",i+1,":"
			Leer dato
			acum<-acum+dato
		FinPara
	    prom<-acum/n
	    Escribir "El promedio es: ",prom
	    Escribir "¿Desea seguir? Ingrese S para sí.";
	    Leer p;
    Mientras que p="s" o p="s"	
FinAlgoritmo
