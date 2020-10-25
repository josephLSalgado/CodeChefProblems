# Chef vs Doof

## Descripción

Chef se peleó con el malvado Dr. Doof. El Dr. Doof ha decidido destruir todos los números pares del universo usando su Evil-Destroy-inator. Chef tiene _N_ números enteros con él. Para detener a Doof, Chef tiene que encontrar un número impar que sea un múltiplo entero de todos los _N_ números que tiene con él. Encuentra si es posible que Chef evite que el Dr. Doof destruya todos los números pares.

Formalmente, dados _N_ números enteros positivos, encuentra si existe un número impar que sea un múltiplo entero de todos los _N_ números dados. Si es así, imprime **"YES"**, de lo contrario **"NO"**. Puedes imprimir cualquier letra en cualquier caso.

### Entrada

- La primera línea contiene _T_, número de casos de prueba. Cada caso de prueba consta de 2 líneas.
- La primera línea de cada caso de prueba consta de un entero positivo _N_, que denota el número de enteros positivos que tiene Chef.
- La segunda línea de cada caso de prueba contiene _N_ enteros separados por espacios _Ai_, cada uno de los cuales denota un entero que Chef tiene consigo.

### Salida

Por cada caso de prueba, si existe un número impar, imprime **"YES"** en una línea separada, de lo contrario **"NO"**. El juez no distingue entre mayúsculas y minúsculas. Eso significa que tu código puede imprimir cualquier letra en cualquier caso (**"Yes"**, **"yes"** o **"YES"** son aceptados).

### Limitaciones

- 1 ≤ _T_ ≤ 10^3
- 1 ≤ _N_ ≤ 10^3
- 1 ≤ _Ai_ ≤ 10^3

### Entrada de muestra

```
2
5
1 2 5 4 3
1
7
```

### Salida de muestra

```
NO
YES
```

### Explicación

Para la prueba 1: No existe número impar.

Para la prueba 2: Los números impares posibles pueden ser 7, 21, 49, 315, ...

## Link

[CodeChef](https://www.codechef.com/problems/CLLCM)
