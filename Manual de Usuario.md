BIENVENIDO AL MANUAL DE USUARIO "ENERGIA-HOGAR"

El programa permite registrar el consumo eléctrico por hora de un hogar durante 24 horas y evaluar estrategias de ahorro energético.

    Requisitos del sistema

Sistema operativo:     	Windows o Linux

Compilador:            	Dev-C++, Visual Studio

Lenguaje:              	C

Archivo fuente:        	energia_hogar.c

    ¿Cómo ejecutar el programa?

*Abre tu entorno de desarrollo (Dev-C++ o Visual Studio).

*Crea un nuevo proyecto en C.

*Copia el código fuente del archivo energia_hogar.c.

*Compila y ejecuta el programa.

    Al momento de ejecutar el programa esto es lo que veras en pantalla 
Principalmente te aparecera el menu de opciones que puedes realizar, escribiendo el numero de la opcion que desees:

<img width="339" height="163" alt="Menu principal" src="https://github.com/user-attachments/assets/504d939b-3b2e-4bc5-be8c-4e957b3464a5" />

    Opción 1: Capturar 24 horas

Permite ingresar los valores de consumo hora por hora (en kWh).

si ingresas un número negativo, el programa lo rechazará y pedirá que lo vuelvas a ingresar.

ejemplo: 

<img width="264" height="498" alt="Reporte base de consumo" src="https://github.com/user-attachments/assets/7eec0107-892a-4d48-892e-b92c75110fb0" />

    Opción 2: Reporte base

Muestra una tabla con los consumos y el costo por cada hora, la “hora pico” indica el momento del día con mayor consumo.

ejemplo: 

<img width="264" height="498" alt="Reporte base de consumo" src="https://github.com/user-attachments/assets/8993f198-1eb4-42b6-b686-aa63afa25bdf" />

    Opción 3: Simular ahorro

El programa pide dos porcentajes, uno %X y otro en %Y que depende del usuario cuanto quieres que sea la simulacion de ahorro, el porcentaje de simulacion en X solo se vera reflejado entre las 0-6 hrs. Y la simulacion del porcentaje Y se vera reflejado solo entre las 18-23 hrs.

<img width="470" height="207" alt="Simular ahorro" src="https://github.com/user-attachments/assets/ee80780a-89ea-42fc-9bee-c39452189040" />

    Opción 4: Comparativo base vs simulado

Muestra el ahorro energético y económico logrado después de aplicar las reducciones

*Consumo base → total sin reducciones.

*Consumo simulado → total con reducciones X% y Y%.

*Ahorro total → diferencia entre ambos, tanto en kWh como en pesos.

<img width="339" height="213" alt="Comparativo base VS simulado" src="https://github.com/user-attachments/assets/47936058-41ac-44f9-84c4-8a9d2722c176" />

    Opción 5: Salir

Finaliza la ejecución del programa.

Este programa fue elaborado con el fin de ayudar a comprender el impacto de los hábitos de consumo eléctrico en el ahorro energético y económico de un hogar. 
