# Ejercicio 9: Generar los primeros N términos de Fibonacci

## Enunciado

Leer N y mostrar los primeros N términos de Fibonacci.

## Análisis

**Datos de entrada:** N (entero).

**Proceso:** Iniciar a = 0 y b = 1; mostrar a y actualizar los valores N veces.

**Datos de salida:** Los primeros N términos.

## Pseudocódigo en PSeInt

```text
Algoritmo Serie_Fibonacci

	// Definir las variables para la cantidad de terminos y los valores de Fibonacci
	Definir n, i, a, b, temporal Como Entero

	// Inicializar los dos primeros valores de la serie
	a <- 0
	b <- 1

	// Solicitar la cantidad de terminos que se desean mostrar
	Escribir "Cuantos terminos desea mostrar?"
	Leer n

	// Repetir el proceso la cantidad de veces indicada
	Para i <- 1 Hasta n Hacer

		// Mostrar el valor actual de la serie
		Escribir a

		// Sumar los dos valores anteriores para obtener el siguiente
		temporal <- a + b

		// Actualizar el primer valor
		a <- b

		// Actualizar el segundo valor
		b <- temporal

	FinPara

FinAlgoritmo
```

## Diagrama de flujo

![Diagrama de flujo](../../diagramas/ej09_fibonacci.png)
