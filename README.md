# TitrationFQApp
Hola a todos!
Esta es una aplicación de Android para simular curvas de titulación ácido-base MOH-HX/ MOH-HA / MOH-H2A, esta aplicación tambien permite graficar datos experimentales por medio Google Sheets. 
La aplicación permite introducir los valores de las concetraciones del ácido y la base, asi como los pKa del ácido. Se puede elegir entre quien será el titulante, son checkbox por lo que se debe elegir uno a la vez. 
Cada linea en el eje de pH esta a una distancia de 0.5 unidades de pH, y en el eje de avance de reacción las lineas azules gruesas indican un avance = 1, 2 y 3, (de derecha a izquierda de la pantalla). 
Esta programado para hacer un auto-resize, por lo que deberia verse relativamente bien en cualquier pantalla. 
La barra del slider sirve para graficar más o menos datos. 
Una vez seleccionados los paramentros de la simulación se presiona "Calculate", las graficas se iran sobre poniendo por lo que para borrarlas, debes presionar "Reset Graph"

*Titulación MOH-HX base fuerte-acido fuerte* : Debes escribir 00 (doble cero) en ambas casillas de pKa

*Titulación MOH-HA base fuerte-acido monoprotico debil* : Debes escribir 00 (doble cero) en la casilla de pKa2 y en la casilla pKa1 el que deseas simular

*Titulacion MOH-H2A base fuerte-ácido diprotico debil* : Escribe en amabas casillas los valores de pKa

Los colores de los puntos de la curva simulada se generan de forma aleatoria por lo que podria pasar que se grafique la curva con puntos de un color que es indistiguible de fondo. Basta con presionar de forma consecutiva "Calculate" hasta que se consiga un color apropiado.

Si tiene algun problema con la App, contactame en el correo alfredohm@quimica.unam.mx
