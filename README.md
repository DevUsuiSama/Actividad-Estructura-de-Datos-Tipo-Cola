# Actividad Estructura de Datos Tipo Cola

- Asignatura: Paradigma y Lenguaje de Programación
- Carrera: Ingeniería en Sistemas de Información
- Profesor: Ing. Pedro Ferrando

## Descripción
Este proyecto es a manera de aprendizaje, su objetivo es la de entender el funcionamiento de una lista enlazada simple.

## Consigna

```
En un supermercado dispone en la salida de 2 cajas para pagar. En el local hay 6 carritos de compra. Escribir un programa que simule el comportamiento, siguiendo las siguientes reglas:

Si cuando llega un cliente no hay ningún carrito disponible, espera a que lo haya (en una cola de espera de carritos).

Ningún cliente abandona el supermercado sin pasar por alguna de las colas de las cajas, cuando un cliente finaliza su compra (luego de haberle asignado un carrito), se coloca en la cola de la caja (de las 3 disponibles) que hay menos gente (cantidad de elementos en la cola) y no se cambia de cola.

En el momento en que un cliente paga en la caja (primero en la cola), el carro de la compra que tiene queda disponible.

Representar las opciones de ingresar un cliente, cobrar en caja, mostrar estado de colas de cajas y mostrar el estado de los carritos y cola de espera de carritos. 

 

Cada vez que se ejecuta una opción de ingreso de cliente o cobro en caja, se actualizan todas las colas.

Secuencia 1: cuando ingresa un cliente mira si hay carritos disponibles, si hay toma uno, caso contrario queda en cola de espera de carros.

Secuencia 2: cuando se paga en caja, se libera la cola de caja y se liberan esos carritos. Los que están con carritos pasan a las cajas (manteniendo el orden de ingreso). Los que están en cola de espera de carritos pasan a tomar los disponibles.

Luego de cualquier secuencia, deberá limpiarse la pantalla, mostrar el estado general y luego de presionar una tecla deberá limpiarse la pantalla y mostrar el menú nuevamente.

Representar los carritos (y su cola de espera) de la compra y las cajas mediante colas, teniendo en cuenta las operaciones disponibles para este tipo de estructura de datos. Hacer un menu con las opciones de ejecución mencionadas.
```

## Autor
- Usui, José Fernando