# Ejercicio 2: Área y perímetro de un rectángulo

## Enunciado

Leer base y altura y calcular el área y el perímetro.

## Análisis

**Datos de entrada:** base y altura (reales).

**Proceso:** área = base * altura; perímetro = 2 * (base + altura).

**Datos de salida:** Área y perímetro.

## Pseudocódigo en PSeInt

```text
Algoritmo Area_Perimetro_Rectangulo
Definir base, altura, area, perimetro Como Real
Escribir "Ingrese la base:"
Leer base
Escribir "Ingrese la altura:"
Leer altura
area <- base * altura
perimetro <- 2 * (base + altura)
Escribir "El area es: ", area
Escribir "El perimetro es: ", perimetro
FinAlgoritmo
```

## Diagrama de flujo

![Diagrama de flujo](../../diagramas/ej02_rectangulo.png)
