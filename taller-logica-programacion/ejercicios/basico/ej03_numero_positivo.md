# Ejercicio 3: Identificar positivo, negativo o cero

## Enunciado

Leer un número y determinar si es positivo, negativo o cero.

## Análisis

**Datos de entrada:** numero (real).

**Proceso:** Comparar el número con cero mediante condicionales.

**Datos de salida:** Clasificación del número.

## Pseudocódigo en PSeInt

```text
Algoritmo Numero_Positivo_Negativo
Definir numero Como Real
Escribir "Ingrese un numero:"
Leer numero
Si numero > 0 Entonces
    Escribir "El numero es positivo"
SiNo
    Si numero < 0 Entonces
        Escribir "El numero es negativo"
    SiNo
        Escribir "El numero es cero"
    FinSi
FinSi
FinAlgoritmo
```

## Diagrama de flujo

![Diagrama de flujo](../../diagramas/ej03_positivo_negativo.png)
