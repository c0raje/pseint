# Repetir

```
Algoritmo repetir
	Repetir
		secuencia_de_acciones
	Hasta Que expresion_logica
FinAlgoritmo
```

## Ejemplos

### Ejemplo 1
```
// repetir un bloque de codigo un numero fijo de veces

repetir 5 veces
    // bloque de código a repetir
fin repetir
```
### Ejemplo 2
```
// repetir un bloque de codigo mientras se cumpla una condicion

repetir mientras (condicion)
    // bloque de código a repetir
fin repetir
```
### Ejemplo 3
```
// repetir un bloque de codigo hasta que se cumpla una condicion

repetir mientras (condicion)
    // bloque de código a repetir
fin repetir
```
### Ejemplo 4
```
// repetir un bloque de codigo al menos una vez y luego mientras se cumpla una condicion

repetir
    // bloque de código a repetir
hasta que (condicion)
```

### Descripcion

El comando "repetir" en PSeInt es una estructura de control repetitiva que permite ejecutar un conjunto de instrucciones varias veces, según el valor que genere una expresión relacional y/o lógica. Esta estructura se utiliza principalmente cuando no se conoce de antemano la cantidad exacta de repeticiones que se deben realizar.