# Navegación

## Navegación Planeada

## Navegación Basada en Comportamientos


# Investigaciones Destacadas


## Robots de Rodney Brooks y Mark Tilden

# Planeación de Rutas con Obstaculos


# Algoritmos Bug 
Los algoritmos Bug estan basados en sensores, que pueden ser a distancia o de contacto para la detección de obstaculos, junto con odometría es posible conocer su posición actual en el plano.

El movimiento en los algoritmos Bug se basan en dos principios, moverse en linea recta o seguir los bordes de algun objeto, donde el robot cambia entre uno y otro dependiendo de la información de los sensores.

Estos algoritmos garantizan que el robot llega a la meta si se cumplen las siguientes condiciones:

* El robot se modela como un punto.
* Los obstaculos tienen perimetros con bordes finitos.
* El robot conoce su posición, orientación y puede medir la distancia recorrida.
* El robot puede calcular la distancia a la meta entre dos puntos con un uso de memoria pequeño.


## Bug 0 

En el algoritmo Bug 0, el robot inicia en dirección a la meta establecida. Al encontrarse con un obstaculo lo sigue hasta que el obstaculo no este entre el robot y la meta. 
El algoritmo finaliza cuando la meta es alcanzada.

![Bug 0](./images/bug0.webp "Bug 0")

## Bug 1
En bug 1, el robot se dirige a la meta hasta que encuentra un obstaculo. Cuando choca contra un obstaculo, este lo rodea hasta encontrar el punto más cercano a la meta. El robot debe memorizar cual es el punto más cercano a la meta sobre el contorno del obstaculo.

![Bug 1](./images/bug1.webp "Bug 1")

## Bug 2 

En Bug 2 el robot se dirige hacia la meta hasta que encuentra un obstaculo. Para enfrentarlo, rodea el obstacula hasta que vuelve a estar sobre la recta entre el inicio y la meta.

![Bug 2](./images/bug2.webp "Bug 2")


# Algoritmos MAZE

