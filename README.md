# 📘 Calculadora de Promedio en Python

Este es un programa sencillo en Python que solicita al usuario tres notas y calcula el promedio general.

---

## 📌 Descripción

El programa:

1. Solicita al usuario que ingrese tres notas.
2. Convierte los valores ingresados a tipo `float`.
3. Calcula el promedio de las tres notas.
4. Muestra el resultado en pantalla.

Este proyecto es ideal para principiantes que están aprendiendo:

- Entrada de datos con `input()`
- Conversión de tipos de datos
- Operaciones matemáticas básicas
- Uso de `print()`

---

## 🧮 Código

```python
nota1 = float(input("digite su primera nota: "))
nota2 = float(input("digite su segunda nota: "))
nota3 = float(input("digite su tercera nota: "))

promedio = (nota1 + nota2 + nota3) / 3

print("El promedio general es:", promedio)