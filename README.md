# Sintaxis QDRAW
QDRAW es un lenguaje de programación usado en la materia "Elementos de programación y lógica" de la Universidad Nacional de Quilmes, para aprender programación procedimental. La sintaxis puede tener mínimas variaciones dependiendo de la catedra. 

*Esta guía no es oficial ni nada parecido.*

## A tener en cuenta
* Los procedimientos deben ser lo mas atómico posible

## Movimientos
1. MoverArriba
2. MoverDerecha
3. MoverAbajo
4. MoverIzquierda

## Pintar o Limpiar
1. PintarNegro
2. PintarRojo
3. PintarVerde
4. Limpiar

## Bloques principales
Se escriben en el orden en el siguiente orden.

1. programa {}
      * El programa no puede tener primitivas, por ejemplo, MoverArriba, PintarVerde, limpiar.

2. procedimiento {}
      * El nombre va en mayúscula
      * Se puede usar un procedimiento dentro de otro procedimiento 


## Comentarios
/*
      Se pone al principio del programa como propósito (para qué se hizo el programa). 
*/


## Loop
* No se pueden anidar loops porque en general, es una mala práctica
* Se usa dentro de un procedimiento

###repetirNVeces{} 
* donde **N** es un número que representa la cantidad de veces que se repite


## Condicionales
* SOLO Se usa dentro de un procedimiento.
* No debe ir dentro de una repeticion, sin embargo, hay que tener en cuenta que un procedimiento puede ir dentro del loop. 

```
      si x entonces {
            Pasos ó procedimientos
      } si no {    /* Esta parte es opcional */
            Pasos ó procedimientos
      }
```
* El **si no**, se usa SOLO cuando es necesario, es decir, si al evitarlo da el mismo resultado que al ponerlo, no se pone.

* **X** es un booleano y puede valer :

1. estaPintadaDeVerde?
2. estaPintadaDeRojo?
3. estaPintadaDeNegro?
4. estaVacia?


## Conectivas y negación entre booleanos
1.  Las Conectivas son las usadas en lógica proposicional y se usan para unir expresiones booleanas.
      * ∧ = conjunción (y)
      * ∨ = disyunción (ó)
  
2.  La Negación va atras del booleano y es el mismo aimbolo de la lógica.
      * ¬ = negación

