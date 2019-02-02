# Flexbox

Ejercicios para entender flexbox con sus conceptos más básicos


![Screenshot](basico.png)


# ¿Que es Flexbox?

Es un modelo de layotu -> conjunto de algoritmos que definen como aparecerá un elemento en un flujo.
Dentro de CSS2 existen:

1.-  Block
2.- Inline
3.- Table
4.- Position

Se agregan 
Flexbox
Gri

# Notas

Los Div ya son display block
Las imagenes ya son display inline

# Main Size y Cross Size (Dimensiones de los items (hijos))

Main Size => Main Axis (por default es el width) 
Cross Size => Cross Axis (por default es el hight) 

¿Como se calcula el Cross Size?

1.- Se ha definido el tamaño y se respeta
2.- No se ha definido el tamaño y no se ha definido align-items o align-content
3.- No se define un tamaño pero si de define align-items o align-content diferente de stretch

¿Como se calcula el Main Size?

1.- Espacio disponible (espacio NO ocupado por los items), espacio ocupado (espacio ocupado por los items)
2.- Los margenes nunca se colapsan (se consideran espacio ocupado)
3.- Los items se rigen por el modelo de caja (los padding y bottom suman al tamaño de la caja - box-sizing: border-box (se calculan por dentro de la caja))
4.- El espacio dispible pordría ser positivo o negativo (por defecto si los tamaño se desborda flex lo calcula y acomoda correcto)

¿Propiedades?

flex-basis -> es el valor predeterminado y es relativo al eje principal
flex-grow
flex-shrink
