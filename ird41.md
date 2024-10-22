# 2 .- Problema: Sumatoria Recursiva de Ventas

Eres un desarrollador que trabaja en una tienda en línea. Tu tarea es crear un script en Bash que calcule la sumatoria total de las ventas de diferentes productos, aplicando ciertas restricciones.

#### Descripción del Problema

Tu script debe recibir un arreglo de ventas donde cada elemento representa el monto vendido de un producto. Sin embargo, existen condiciones que deben cumplirse:

1. Si un producto tiene un monto de ventas menor o igual a cero, no se debe incluir en la suma.
2. Si hay más de 10 productos en el arreglo, la suma se debe multiplicar por 1.1 (un 10% extra) como un incentivo.
3. Si el total de ventas supera 1000, se aplica un descuento del 5% al total.

#### Entrada

La entrada será un arreglo de números enteros que representan las ventas de los productos.

- La primera línea contendrá un número entero \( n \) (1 ≤ \( n \) ≤ 1000): el número de productos.
- La segunda línea contendrá \( n \) enteros \( v_1, v_2, \ldots, v_n \) (−1000 ≤ \( v_i \) ≤ 10000): los montos de ventas de cada producto.

#### Salida

El script debe imprimir un solo número, que es la sumatoria total de las ventas con las condiciones aplicadas, redondeado a dos decimales.

#### Ejemplo de Entrada

```
5
100 200 300 0 -50
```

#### Ejemplo de Salida

```
600.00
```

#### Ejemplo de Entrada 2

```
12
200 150 300 400 0 100 150 80 90 70 500 600
```

#### Ejemplo de Salida 2

```
1515.00
```

### Requerimientos del Script

1. Utilizar funciones recursivas para calcular la sumatoria.
2. Implementar las condiciones mencionadas.
3. El script debe manejar entradas incorrectas (números no enteros o fuera del rango).
4. Debe incluir comentarios explicativos para cada parte importante del código.
