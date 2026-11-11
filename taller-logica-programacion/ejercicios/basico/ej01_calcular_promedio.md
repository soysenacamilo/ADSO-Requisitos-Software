# Ejercicio 1: Calcular el promedio de tres notas

## Enunciado

Leer tres notas y calcular su promedio.

## Análisis

**Datos de entrada:** nota1, nota2 y nota3 (reales).

**Proceso:** Sumar las tres notas y dividir entre 3.

**Datos de salida:** El promedio.

## Pseudocódigo en PSeInt

```text
Algoritmo Calcular_Promedio

	// Declarar las variables que almacenan las notas y el promedio
	Definir nota1, nota2, nota3, promedio Como Real

	// Solicitar y guardar la primera nota
	Escribir "Ingrese la primera nota:"
	Leer nota1

	// Solicitar y guardar la segunda nota
	Escribir "Ingrese la segunda nota:"
	Leer nota2

	// Solicitar y guardar la tercera nota
	Escribir "Ingrese la tercera nota:"
	Leer nota3

	// Sumar las tres notas y dividir el resultado entre 3
	promedio <- (nota1 + nota2 + nota3) / 3

	// Mostrar el promedio obtenido
	Escribir "El promedio es: ", promedio

FinAlgoritmo
```

## Diagrama de flujo

![Diagrama de flujo](../../diagramas/ej01_promedio.png)
