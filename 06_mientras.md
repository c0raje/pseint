# Mientras

```
Algoritmo mientras
	Mientras expresion_logica Hacer
		secuencia_de_acciones
	Fin Mientras
FinAlgoritmo
```

## Ejemplos

### Ejemplo 1
```
// ejecutar un bloque de codigo mientras se cumpla una condicion

mientras (contador <= 10) hacer
    escribir("El contador es: ", contador)
    contador <- contador + 1
finMientras
```
### Ejemplo 2
```
// realizar una suma acumulativa mientras se cumpla una condicion

suma <- 0
mientras (suma < 100) hacer
    escribir("Ingrese un número: ")
    leer(numero)
    suma <- suma + numero
finMientras
escribir("La suma total es: ", suma)
```

### Descripcion

El comando "mientras" en PSeInt se utiliza para crear un bucle que se ejecuta repetidamente mientras se cumpla una determinada condición. Permite repetir un bloque de código hasta que la condición especificada sea falsa.