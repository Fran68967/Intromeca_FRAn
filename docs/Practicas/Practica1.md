---
titulo: "Tarea: (P1) — Temporizdor 555"
fecha: 2026-09-05
autor: "Francisco Javier Pérez Hernández"
equipo: "Nombre del equipo (si aplica)"
estado: borrador   # borrador | completa
---

# Sesión ## — Título P1

## Objetivos


- [Construir un oscilador (555 astable) que haga parpadear un LED, calcular su frecuencia y duty teóricos, medirlos y comparar ✅] Objetivo 1 
- [Generar un pulso de duración fija cada vez que
presionas un botón: el principio detrás de retardos,
temporizadores y antirrebote por hardware ❌ ya no pude realizar el 555 en monoestable] Objetivo 2

## Materiales
*Lista corta: componentes y software. Si compraste algo, pon el costo.*

(1×) NE555 (DIP-8) <br>
(1×) LED
(1×) Resistor para LED (330 Ω o 470 Ω)
(2×) Resistores temporizadores: , 
RA = 1kΩ
RB = 10kΩ
(1×) Capacitor de temporización:  
C = 100µF (electrolítico)
C = 100nF (cerámico)
(1×) Capacitor 10 nF para pin 5 (CTRL) → estabilidad
Protoboard, cables, fuente 5V regulada

## Desarrollo
*2–4 fotos o capturas TUYAS, cada una con un pie de foto de una línea diciendo qué muestra.
Si mediste algo, va la tabla — la tabla ES la evidencia.*

![Pie de foto: qué muestra esta imagen](img/sesionN_1.jpg)

| Magnitud | Teórico | Medido | % error | ¿Con qué lo mediste?|
| Vcc (V) | 5 | 5 | 0% | Multímetro|
| V de salida en ALTO (V)| 3.5 | 4.42 | 26.28% | Osciloscopio|
|Frecuencia (Hz)| 0.69| 557.2| 80,653.62%| Osciloscopio|
|Duty (%)| 52.4| 49.3| 5.91%| Osciloscopio|
|I del LED (mA)| 4.55| 2.31| 49.23%| Multímetro|

## Fallas
*Mínimo una. Si de verdad nada falló, escribe qué te sorprendió.
Formato: síntoma → cómo lo encontré → solución.*

- **Síntoma: Durante la realización de la practica el led solo se queda prendido y tenia que apagarse y prender** ...
- **Cómo lo encontré: El foco se quedaba prendido y con ayuda de la maestra me ayudo a detectra la falla de la dirreción del temporizador estaba mal** ...
- **Solución: Cambiar de direccion el temporizador 555, guiandome por la muesca** ...

## Aprendizajes
*3 a 5 líneas, con tus palabras. No es resumen del tema: es qué entendiste TÚ que antes no.*
Aprendi a como utilizar el osciloscopio, la capacidad de las resistencia son de suma importancia ya que estas pueden afectar en el resultado desde no prender el led o varirar en los resultados, de igual manera pude comprender que estos circuitos son el principio para comprender sistemas mas complicados que incluso pueden integrarlos como en sistemas de alarmas

## Siguiente paso
*Una línea: qué sigue antes de la próxima sesión.*
Comprender mejor el circuito 555 en monoestable y el astable