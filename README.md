# Practica_8
## Integrantes:  
- Francisco Javier Godinez Lopez
- Pablo Axel Silva Fuentes
- Eduardo David Salas Ayala
## Introducción:  

El objetivo de la práctica es reutilizar las matrices para realizar una tarea diferente. Esta tarea consiste en acomodar los fusibles dentro de una matriz, ubicando cada fusible en un punto específico. La matriz debe tener un tamaño de 3x2, con un total de 6 puntos. Además, es necesario ajustar la velocidad y los puntos de movimiento del robot epson para asegurar su correcto funcionamiento.

## Instrucciones

El robot Epson debe ubicar 6 fusibles dentro de una matriz 3x2.

1. Definir las esquinas de la matriz.
2. programar la recoleccion de cada uno de los fusibles. 
3. Ajustar la altura necesaria en la recoleccion de fusibles para evitar posibles colisiónes.
4. Programar la ubicacion de cada uno de los fusibles dentro de la matriz.
5. Ejecutar la programacion para realizar la tarea asiganda.

De tal manera que el codigo desarrollado quedo de la siguiente manera:

```
Function main

Power High
Speed 10

Pallet 0, Esq1, Esq2, Esq3, 3, 2

Home
Go Fus1
On 2
Go FusGrab1
Off 2
Go Fus1 +Z(150)
Go Pallet(0, 1, 1)
On 2
Go Here +Z(220)
Go Fus2
Go FusGrab2
Off 2
Go Fus2 +Z(150)
Go Pallet(0, 1, 2)
On 2
Go Here +Z(220)
Go Fus3
Go FusGrab3
Off 2
Go Fus3 +Z(150)
Go Pallet(0, 2, 1)
On 2
Go Here +Z(220)
Go Fus4
Go FusGrab4
Off 2
Go Fus4 +Z(150)
Go Pallet(0, 2, 2)
On 2
Go Here +Z(220)
Go Fus5
Go FusGrab5
Off 2
Go Fus5 +Z(150)
Go Pallet(0, 3, 1)
On 2
Go Here +Z(220)
Go Fus6
Go FusGrab6
Off 2
Go Fus6 +Z(150)
Go Pallet(0, 3, 2)
On 2
Go Here +Z(220)
Home

Fend

```


En el siguiente video, se muestra cómo el robot Epson cumple con la tarea asignada, utilizando matrices para ubicar los fusibles en sus posiciones correspondientes. Este video también destaca la correcta configuración y programación implementada para lograr un funcionamiento preciso y eficiente del sistema.

https://github.com/user-attachments/assets/2c80f00e-a5c9-48f8-a264-c001ec6adee1

## Conclusiones:  
### Francisco Javier Godinez Lopez:



### Pablo Axel Silva Fuentes: 



### Eduardo David Salas Ayala: 



## Referencias bibliográficas
- Epson (2020). EPSON RC+ 7.0 Manual del usuario Administración y desarrollo de proyectos (Ver.7.3). https://files.support.epson.com/far/docs/epson_rc_pl_70_users_guide_spanish_(v73r2).pdf
