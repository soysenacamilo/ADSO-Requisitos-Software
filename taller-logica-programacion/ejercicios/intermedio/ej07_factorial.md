# Ejercicio 7: Calcular el factorial de un número

## Enunciado

Leer un entero no negativo y calcular su factorial.

## Análisis

**Datos de entrada:** n (entero no negativo).

**Proceso:** Iniciar factorial en 1 y multiplicar por cada entero desde 1 hasta n.

**Datos de salida:** Factorial de n. El factorial de 0 es 1.

## Pseudocódigo en PSeInt

```text
Algoritmo Calcular_Factorial

	// Definir las variables para el numero, contador y factorial
	Definir n, i, factorial Como Entero

	// Inicializar el factorial en uno
	factorial <- 1

	// Solicitar y guardar un numero entero no negativo
	Escribir "Ingrese un numero entero no negativo:"
	Leer n

	// Comprobar que el numero sea mayor o igual a cero
	Si n >= 0 Entonces

		// Recorrer los numeros desde 1 hasta el numero ingresado
		Para i <- 1 Hasta n Hacer

			// Multiplicar el factorial por cada numero del recorrido
			factorial <- factorial * i

		FinPara

		// Mostrar el resultado del factorial
		Escribir "El factorial es: ", factorial

	// Si el numero es negativo, mostrar un mensaje de error
	SiNo
		Escribir "El numero debe ser no negativo"
	FinSi

FinAlgoritmo
```

## Diagrama de flujo

![Diagrama de flujo](../../diagramas/ej07_factorial.png)
