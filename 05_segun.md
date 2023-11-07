# Segun

```
Algoritmo segun
	Segun variable_numerica Hacer
		opcion_1:
			secuencia_de_acciones_1
		opcion_2:
			secuencia_de_acciones_2
		opcion_3:
			secuencia_de_acciones_3
		De Otro Modo:
			secuencia_de_acciones_dom
	Fin Segun
FinAlgoritmo
```

## Ejemplos

### Ejemplo 1
```
// realizar una seleccion multiple basada en el valor de una variable

según dia
    caso 1:
        escribir("Hoy es lunes")
    caso 2:
        escribir("Hoy es martes")
    caso 3:
        escribir("Hoy es miércoles")
    otroCaso:
        escribir("Hoy no es lunes, martes ni miércoles")
finSegún
```
### Ejemplo 2
```
// realizar una seleccion multiple basada en el valor de una expresion

según edad
    caso < 18:
        escribir("Eres menor de edad")
    caso >= 18 y <= 65:
        escribir("Eres adulto")
    caso > 65:
        escribir("Eres adulto mayor")
    otroCaso:
        escribir("No se puede determinar tu edad")
finSegún
```

### Descripcion

El comando "según" en PSeInt se utiliza para realizar una selección múltiple basada en el valor de una variable o expresión. Permite ejecutar diferentes bloques de código dependiendo del valor que tome la variable o expresión evaluada.3