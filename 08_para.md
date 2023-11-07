# Para

```
Algoritmo para
	Para variable_numerica<-valor_inicial Hasta valor_final Con Paso paso Hacer
		secuencia_de_acciones
	Fin Para
FinAlgoritmo
```

## Ejemplos

### Ejemplo 1
```
// uso basico

para i <- 1 hasta 10
   escribir(i)
fin para
```
Este código imprime los números del 1 al 10 en la consola. Cumple el requisito de imprimir una secuencia de números.
### Ejemplo 2
```
// uso con variables contadoras

entero i
para i <- 1 hasta 5 con paso 2
   escribir(i)
fin para
```
En este caso, se imprime los números 1, 3 y 5 en la consola, ya que el paso es de 2 en 2. Cumple el requisito de imprimir una secuencia de números con un paso específico.
### Ejemplo 3
```
// uso con arreglos

definir matriz numeros[5] como entero
para i <- 0 hasta 4
   numeros[i] <- i * 2
fin para
```
En este ejemplo, se asignan los valores 0, 2, 4, 6 y 8 a los elementos del arreglo "numeros". Cumple el requisito de asignar valores a los elementos de un arreglo.
### Ejemplo 4
```
// uso con condiciones

para i <- 1 hasta 10
   si i mod 2 = 0 entonces
       escribir(i)
   fin si
fin para
```

### Descripcion

El comando "para" en PSeInt se utiliza para crear bucles o ciclos que permiten repetir una serie de instrucciones un número determinado de veces.



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