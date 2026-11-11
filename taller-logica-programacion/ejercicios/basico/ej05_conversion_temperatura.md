# Ejercicio 5: Convertir Celsius a Fahrenheit

## Enunciado

Leer temperatura Celsius y convertirla a Fahrenheit.

## Análisis

**Datos de entrada:** celsius (real).

**Proceso:** fahrenheit = celsius * 9 / 5 + 32.

**Datos de salida:** Temperatura Fahrenheit.

## Pseudocódigo en PSeInt

```text
Algoritmo Celsius_A_Fahrenheit

	// Definir las variables para almacenar las temperaturas
	Definir celsius, fahrenheit Como Real

	// Solicitar y guardar la temperatura en grados Celsius
	Escribir "Ingrese la temperatura en Celsius:"
	Leer celsius

	// Convertir la temperatura de Celsius a Fahrenheit
	fahrenheit <- celsius * 9 / 5 + 32

	// Mostrar la temperatura convertida
	Escribir "Temperatura en Fahrenheit: ", fahrenheit

FinAlgoritmo
```

## Diagrama de flujo

![Diagrama de flujo](../../diagramas/ej05_temperatura.png)
