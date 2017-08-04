ordernar
========

Ordena los primeros `n` elementos del array `arr` de menor a mayor.

### pseint

Funcion OrdenarArray(list,n)
	definir auxiliar,j,i como entero;
	auxiliar<-0;
	i<-1;
	j<-0;
	
	mientras j<(n-2) hacer
		mientras i< n Hacer
			si list[i-1]>list[i] entonces
				auxiliar<-list[i-1];
				list[i-1]<-list[i];
				list[i]<-auxiliar;
			finsi
			
			i<-i+1;
			
		finmientras
		j<-j+1;
		i<-1;
	FinMientras
	escribir "lista ordenada";
	ImprimeLista(list,n);
FinFuncion

#### Ejemplo de uso:

Falta completar esta seccion. ¿Te animas a escribirlo?
