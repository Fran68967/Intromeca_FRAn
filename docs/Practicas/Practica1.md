---
titulo: "Tarea: (P1) — Temporizdor 555"
fecha: 2026-09-05
autor: "Francisco Javier Pérez Hernández"
estado: Completa   # borrador | completa
---

# Sesión ## — Título P1

## Objetivos


- Objetivo 1: Construir un oscilador (555 astable) que haga parpadear un LED, calcular su frecuencia y duty teóricos, medirlos y comparar ✅  
-Objetivo 2: Generar un pulso de duración fija cada vez que
presionas un botón: el principio detrás de retardos,
temporizadores y antirrebote por hardware ❌ <br>
 ya no pude realizar el 555 en monoestable

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
*2–4 fotos o capturas TUYAS, cada una con un pie de foto de una línea diciendo qué muestra.
Si mediste algo, va la tabla — la tabla ES la evidencia.*

![Pie de foto: qué muestra esta imagen]
<video>
<source src= "555 astable.mp4" type="video/mp4">
</video>

| Magnitud | Teórico | Medido | % error | ¿Con qué lo mediste?|
|---|---|---|---|---|
| Vcc (V) | 5 | 5 | 0% | Multímetro|
| V de salida en ALTO (V)| 3.5 | 4.42 | 26.28% | Osciloscopio|
|Frecuencia (Hz)| 0.69| 557.2| 80,653.62%| Osciloscopio|
|Duty (%)| 52.4| 49.3| 5.91%| Osciloscopio|
|I del LED (mA)| 4.55| 2.31| 49.23%| Multímetro|

## Fallas


- **Síntoma: Durante la realización de la practica el led solo se queda prendido y tenia que apagarse y prender** ...
- **Cómo lo encontré: El foco se quedaba prendido y con ayuda de la maestra me ayudo a detectra la falla de la dirreción del temporizador estaba mal** ...
- **Solución: Cambiar de direccion el temporizador 555, guiandome por la muesca** ...

## Aprendizajes

Aprendi a como utilizar el osciloscopio, la capacidad de las resistencia son de suma importancia ya que estas pueden afectar en el resultado desde no prender el led o varirar en los resultados, de igual manera pude comprender que estos circuitos son el principio para comprender sistemas mas complicados que incluso pueden integrarlos como en sistemas de alarmas

## Siguiente paso

Comprender mejor el circuito 555 en monoestable y el astable
