# Si-Entonces

```
Algoritmo si_entonces
	Si expresion_logica Entonces
		acciones_por_verdadero
	SiNo
		acciones_por_falso
	Fin Si
FinAlgoritmo
```

## Ejemplos

```
// si la condicion es verdadera, ejecutar un bloque de codigo

si (numero > 0) entonces
    escribir("El número es positivo")
finSi



// si la condicion es falsa, ejecutar un bloque de codigo

si (edad < 18) entonces
    escribir("Eres menor de edad")
finSi



// Si la condicion es verdadera, ejecutar un bloque de codigo; de lo contrario, ejecutar otro bloque de codigo

si (nota >= 60) entonces
    escribir("Aprobado")
sino
    escribir("Reprobado")
finSi

```

### Descripcion

El comando "si-entonces" en PSeInt se utiliza para realizar una evaluación condicional y ejecutar un bloque de código si se cumple una determinada condición. Permite tomar decisiones en función del resultado de una expresión lógica.