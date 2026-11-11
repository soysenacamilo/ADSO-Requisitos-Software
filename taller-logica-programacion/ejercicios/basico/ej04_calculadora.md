# Ejercicio 4: Calculadora básica

## Enunciado

Leer dos números y una opción para sumar, restar, multiplicar o dividir.

## Análisis

**Datos de entrada:** numero1 y numero2 (reales); opcion (entero).

**Proceso:** Usar Segun para elegir la operación y validar que el divisor no sea cero.

**Datos de salida:** Resultado o mensaje de error.

## Pseudocódigo en PSeInt

```text
Algoritmo Calculadora_Basica

	// Definir las variables para los numeros y el resultado
	Definir numero1, numero2, resultado Como Real

	// Definir la variable que guardara la opcion seleccionada
	Definir opcion Como Entero

	// Solicitar y guardar el primer numero
	Escribir "Ingrese el primer numero:"
	Leer numero1

	// Solicitar y guardar el segundo numero
	Escribir "Ingrese el segundo numero:"
	Leer numero2

	// Mostrar las operaciones disponibles
	Escribir "1. Sumar  2. Restar  3. Multiplicar  4. Dividir"
	Leer opcion

	// Seleccionar la operacion que se desea realizar
	Segun opcion Hacer

		// Realizar la suma de los dos numeros
		1:
			resultado <- numero1 + numero2
			Escribir "Resultado: ", resultado

		// Realizar la resta de los dos numeros
		2:
			resultado <- numero1 - numero2
			Escribir "Resultado: ", resultado

		// Realizar la multiplicacion de los dos numeros
		3:
			resultado <- numero1 * numero2
			Escribir "Resultado: ", resultado

		// Comprobar que el segundo numero no sea cero antes de dividir
		4:
			Si numero2 <> 0 Entonces
				resultado <- numero1 / numero2
				Escribir "Resultado: ", resultado
			SiNo
				Escribir "No se puede dividir entre cero"
			FinSi

		// Mostrar un mensaje si se selecciona una opcion incorrecta
		De Otro Modo:
			Escribir "Opcion no valida"

	FinSegun

FinAlgoritmo
```

## Diagrama de flujo

![Diagrama de flujo](../../diagramas/ej04_calculadora.png)
