---
titulo: "Tarea: (P1) — Temporizdor 555"
fecha: 2026-09-05
autor: "Francisco Javier Pérez Hernández"
estado: Completa   # borrador | completa
---

# Sesión ## — Título P1

## Objetivos

- Objetivo 1: Construir un oscilador (555 astable) que haga parpadear un LED, calcular su frecuencia y duty teóricos, medirlos y comparar ✅  
- Objetivo 2: Generar un pulso de duración fija cada vez que
presionas un botón: el principio detrás de retardos,
temporizadores y antirrebote por hardware ❌ <br>
 ya no pude realizar el 555 en monoestable ya que al realizar el astable tuve una representacion visual de como realizar la practica y la imagen del monoestable no pude comprenderlo en su totalidad y al realizar la practica solo fue un poco mas dificil

## Materiales

(1×) NE555 (DIP-8) <br>
(1×) LED<br>
(1×) Resistor para LED (330 Ω o 470 Ω) <br>
(2×) Resistores temporizadores: , <br>
RA = 1kΩ <br> 
RB = 10kΩ <br>
(1×) Capacitor de temporización:  <br>
C = 100µF (electrolítico) <br>
C = 100nF (cerámico) <br>
(1×) Capacitor 10 nF para pin 5 (CTRL) → estabilidad <br>
Protoboard, cables, fuente 5V regulada <br>

## Desarrollo
<img width="1200" height="1600" alt="555 astable imagen" src="https://github.com/user-attachments/assets/974603d5-5acd-4e02-a783-7bd07fff8b41" />
Muestra la estructura y conexión del circuito 555 astable
<img width="621" height="476" alt="esquemático" src="https://github.com/user-attachments/assets/97eeabc0-3418-46d4-8569-a682590bfd07" />
Esquemático en Tinkerkad


| Magnitud | Teórico | Medido | % error | ¿Con qué lo mediste?|
|---|---|---|---|---|
| Vcc (V) | 5 | 5 | 0% | Multímetro|
| V de salida en ALTO (V)| 3.5 | 4.42 | 26.28% | Osciloscopio|
|Frecuencia (Hz)| 0.69| 557.2| 80,653.62%| Osciloscopio|
|Duty (%)| 52.4| 49.3| 5.91%| Osciloscopio|
|I del LED (mA)| 4.55| 2.31| 49.23%| Multímetro|

<video witdth="1200" height="1600" alt="555 astable oscilospio" src="https://github.com/user-attachments/assets/3535b8a8-af3c-4b4d-8e55-3b3a7b996e5b" />
Muestra el circuito 555 en funcionamiento y su conexión con el osciloscopio y el multímetro para realizar las mediciones de la señal generada. Durante la práctica del circuito 555 astable. En el osciloscopio conecté la señal de salida al pin 3 y el GND para visualizar la onda generada. Con la función de medición pude obtener valores como el voltaje alto, la frecuencia y Duty Cycle. También observé que el parpadeo del LED, permitió comprobar que el circuito estaba generando una señal periódica. Finalmente, utilicé el multímetro para medir el voltaje de alimentación y realizar las mediciones necesarias en el circuito.

## Fallas
- **Síntoma: Durante la realización de la practica el led solo se queda prendido y tenia que apagarse y prender** ...
- **Cómo lo encontré: El foco se quedaba prendido y con ayuda de la maestra me ayudo a detectra la falla de la dirreción del temporizador estaba mal** ...
- **Solución: Cambiar de direccion el temporizador 555, guiandome por la muesca** ...

## Aprendizajes

Aprendi a como utilizar el osciloscopio, la capacidad de las resistencia son de suma importancia ya que estas pueden afectar en el resultado desde no prender el led o varirar en los resultados, de igual manera pude comprender que estos circuitos son el principio para comprender sistemas mas complicados que incluso pueden integrarlos como en sistemas de alarmas

## Siguiente paso

Comprender mejor el circuito 555 en monoestable y el astable
