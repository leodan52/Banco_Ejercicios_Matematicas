# Banco_Ejercicios_Matematicas

Este banco recolecta listas de ejercicios de matemáticas generados aleatoriamente bajo ciertas condiciones. La finalidad es que los ejercicios creados puedan ser utilizados para la enseñanza de las matemáticas como preparación para la PAA ([Prueba de Actitud Académica](https://latam.collegeboard.org/paa/)).

El banco posee las siguientes listas en formato TXT:
* Aritmética:
	* [Estadística](/Estadística/ejercicios.txt)
* Álgebra:
	* [Ecuaciones lineales](/Álgebra/Ecuaciones_lineales/ecuaciones.txt)
		* [Respuestas](/Álgebra/Ecuaciones_lineales/ecuaciones_respuestas.txt)
	* [Desigualdades/Inecuaciones](/Álgebra/Desigualdades/desigualdades.txt)
	* [Sistemas de ecuaciones 2$\times$2](/Álgebra/Sistemas_de_ecuaciones/sistemas_ec.txt)

* Geometría:
	* Ángulos
		* [Intersección - Suplementarios](/Geometría/Ángulos/Interseccion-Paralelas/Suplementarios.txt)
		* [Intersección - Opuestos](/Geometría/Ángulos/Interseccion-Paralelas/Opuestos.txt)

Cada lista usa `'\n'` como secuencia de escape para salto de linea, además de tabuladores (`'\t'`) y no espacios para el uso de sangría.

## Condiciones para la generación de los ejercicios

### Estadística

La lista [Estadística](/Estadística/ejercicios.txt) posee conjuntos ejemplos con 10 datos cada uno. Las condiciones que se imponen son las siguientes:

* El promedio, o medía aritmética, debe ser siempre un **número entero**,
* los datos se limitan en el intervalo $[2,20]$.
* y en la mayoría de los ejercicios $\sigma^2$, la varianza, es un **número cuadrado perfecto**.

Próximamente se espera remplazar la lista con una mayor cantidad de ejercicios, manteniendo un porcentaje pequeño de ejercicios con $\sigma^2$ como un número sin raíz cuadrada exacta.
