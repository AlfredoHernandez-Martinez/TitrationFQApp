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

*Titulacion MOH-H2A base fuerte-ácido diprotico debil* : Escribe en ambas casillas los valores de pKa

Los colores de los puntos de la curva simulada se generan de forma aleatoria por lo que podria pasar que se grafique la curva con puntos de un color que es indistiguible de fondo. Basta con presionar de forma consecutiva "Calculate" hasta que se consiga un color apropiado.

Para hacer usos de la opción Add Experimental Data, debe tener conexión a internet. En el Primer Textbox debe pegar el Link de la hoja de Google Sheet donde
escribio los datos experimentales. Debe ajustar la privacidad de documento de PRIVADO a LECTOR, para poder usar los datos. 

Debe de estar escritos en dos columnas, ξ (avance de reacción) en la primera columna y pH en la segunda, no existe limite de numero de pares de datos.
Una vez pegado el link en la aplicación, escriba la cantidad de pares de datos que utilizó y presione "Add data", la aplicacion le indicara cuando puede presionar
"back" en su telefono. Despues solo debe seleccionar "Plot Experimental Data"

Para celular se sugiere tener la pantalla en vertical o portrait y en tablet o celulares de pantalla grande en horizontal o landscape. 

La version 2 incluye permite el calculo de diagramas de distribución de especies, solo debes escribir los pKas usando la misma sintaxis. Monoprotico: Debes escribir 00 (doble cero) en la casilla de pKa2 y en la casilla pKa1 el que deseas simular y Diprotico: Escribe en ambas casillas los valores de pKa.


Si tiene algun problema con la App, contactame en el correo alfredohm@quimica.unam.mx
