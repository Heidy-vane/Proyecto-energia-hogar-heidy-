# Proyecto-energia-hogar-heidy-
Este programa permite analizar el consumo eléctrico por hora durante 24 horas en un hogar y evaluar estrategias de ahorro energético. 
El sistema calcula:

El consumo total diario.
La hora pico (mayor consumo).
El costo según el precio por kWh.
Una simulación de ahorro, aplicando reducciones de consumo en horas específicas.

Funciones principales

Capturar consumo horario
Permite ingresar los valores de consumo (kWh) para cada una de las 24 horas del día.

Reporte base
Muestra una tabla con el consumo y el costo por hora, así como el total diario y la hora pico.

Simulación de ahorro
Aplica reducciones porcentuales en horas especificas:
00:00–06:00 → reducción X%
18:00–23:00 → reducción Y%

Comparativo base vs simulado
Muestra el ahorro total en kWh y en pesos entre el consumo base y el simulado.

Datos utilizados
Arreglo 1D de 24 posiciones: almacena los consumos horarios (kWh).
Precio del kWh: 2.5 MXN 
Reducción X e Y: porcentajes entre 0 y 100.

Requisitos técnicos
Lenguaje: C 
Compilador: Dev-C++ o Visual Studio
Sistema operativo: Windows
