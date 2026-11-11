# Ejercicio 8: Contar las vocales de una cadena

## Enunciado

Leer una frase y contar cuántas vocales contiene.

## Análisis

**Datos de entrada:** frase (cadena).

**Proceso:** Recorrer cada carácter, pasarlo a minúscula y contar a, e, i, o, u.

**Datos de salida:** Cantidad de vocales.

## Pseudocódigo en PSeInt

```text
Algoritmo Contar_Vocales

	// Definir las variables para almacenar la frase y cada letra
	Definir frase, letra Como Cadena

	// Definir las variables para recorrer la frase y contar las vocales
	Definir i, contador Como Entero

	// Inicializar el contador de vocales en cero
	contador <- 0

	// Solicitar y guardar una frase
	Escribir "Ingrese una frase:"
	Leer frase

	// Recorrer cada caracter de la frase
	Para i <- 0 Hasta Longitud(frase) - 1 Hacer

		// Obtener la letra actual y convertirla a minuscula
		letra <- Minusculas(Subcadena(frase, i, i))

		// Comprobar si la letra actual es una vocal
		Si letra = "a" O letra = "e" O letra = "i" O letra = "o" O letra = "u" Entonces

			// Aumentar el contador cuando se encuentre una vocal
			contador <- contador + 1

		FinSi
	FinPara

	// Mostrar la cantidad total de vocales encontradas
	Escribir "Cantidad de vocales: ", contador

FinAlgoritmo
```

## Diagrama de flujo

![Diagrama de flujo](../../diagramas/ej08_vocales.png)
