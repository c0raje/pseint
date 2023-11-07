# Function

```
Funcion variable_de_retorno <- Nombre ( Argumentos )
	
Fin Funcion

Algoritmo funcion
	
FinAlgoritmo
```

## Ejemplos

### Ejemplo 1
```
// calculo del area de un triangulo

funcion calcularAreaTriangulo(base, altura)
    area = (base * altura) / 2
    escribir("El área del triángulo es: ", area)
fin funcion
```
### Ejemplo 2
```
// verificacion de un numero par

funcion esNumeroPar(numero)
    si numero modulo 2 == 0 entonces
        escribir("El número es par.")
    sino
        escribir("El número es impar.")
    fin si
fin funcion
```
### Ejemplo 3
```
// conversion de temperatura

funcion convertirCelsiusAFahrenheit(celsius)
    fahrenheit = (celsius * 9/5) + 32
    escribir("La temperatura en grados Fahrenheit es: ", fahrenheit)
fin funcion
```

### Descripcion

El comando "funcion" en PSeInt se utiliza para definir una subrutina o función en el código. Permite agrupar un conjunto de instrucciones que se pueden ejecutar en diferentes partes del programa, lo que facilita la reutilización del código y mejora la legibilidad del mismo.



[01_escribir.md](01_escribir.md)

[02_leer.md](02_leer.md)

[03_asignar.md](03_asignar.md)

[04_si-entonces.md](04_si-entonces.md)

[05_segun.md](05_segun.md)

[06_mientras.md](06_mientras.md)

[07_repetir.md](07_repetir.md)

[08_para.md](08_para.md)

[09_funcion.md](09_funcion.md)

[README.md](README.md)