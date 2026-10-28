# Clase 5 — Carrito F1 en MDF

En esta práctica, en pareja, diseñamos, cortamos y armamos un carrito tipo Fórmula 1 de MDF. Fue la primera vez que juntamos todo lo visto hasta ahora: el modelado en SolidWorks, los ensambles y la cortadora láser.

## 1. Diseño en SolidWorks

Modelamos el carrito desde cero. Partimos de una imagen de referencia y de las medidas de cada componente.

- **Espesor:** todas las piezas tienen **3 mm**, igual que la lámina de MDF. Así los encajes ajustan sin pegamento.
- **Simetría:** las piezas que se repiten de los dos lados (paneles laterales, soportes) se hicieron con simetría. Así salen iguales y ahorramos tiempo de modelado.

![Modelado de una pieza](https://andyy-py.github.io/Proyecto-inge/Bitacora/img_f1/pieza.png)

*Modelado de una de las piezas del chasis.*

## 2. Ensamble digital

Antes de cortar, armamos todo en un archivo de ensamble para comprobar que los encajes tipo rompecabezas coincidieran.

- El **volante** se armó como un subensamble que puede girar libremente.
- La **bisagra flexible** se dejó lista en vectores para doblarla después del corte.

![Ensamble 3D del carrito](https://andyy-py.github.io/Proyecto-inge/Bitacora/img_f1/ensamble.png)

*Ensamble completo en SolidWorks para revisar que todo encajara.*

## 3. Corte láser

Exportamos los planos 2D a **DXF** y los preparamos en **Falcon Design Space**. Ahí acomodamos las piezas para aprovechar mejor la lámina, sin cambiar su geometría.

| Parámetro | Valor |
|-----------|-------|
| Máquina | Creality Falcon A1 |
| Área de trabajo | 381 × 305 mm |
| Material | MDF de 3 mm |
| Velocidad | 25 mm/s |
| Potencia | 40 % |
| Tipo de corte | Vectorial lineal |

![Corte en la láser](https://andyy-py.github.io/Proyecto-inge/Bitacora/img_f1/maquina1.png)

*La cortadora láser durante el corte de las piezas.*

## 4. Armado físico

Armamos el carrito por partes, en este orden:

1. Chasis y ejes
2. Volante
3. Cubierta
4. Alerón y habitáculo
5. Frontal, llantas y paneles laterales

## 5. Problemas y solución

| Problema | Causa | Solución |
|----------|-------|----------|
| La cubierta no entraba en una ranura lateral | Interferencia de casi 1 mm entre las piezas | Limamos un poco el conector, con cuidado de no romper el MDF |

## Resultado final

![Carrito F1 terminado](https://andyy-py.github.io/Proyecto-inge/Bitacora/img_f1/final.png)

*Carrito F1 ya armado.*

## Aprendizajes

Aprendí que el ensamble digital ahorra mucho material, porque los errores se ven antes de cortar. También me di cuenta de que en el corte láser hay que dejar un pequeño margen de tolerancia: aunque en la computadora todo encaje perfecto, en el material real una diferencia de 1 mm ya hace que la pieza no entre.

## Archivos del proyecto

Piezas 3D, ensamble, planos 2D y archivos DXF:

[📦 Descargar archivos del Carrito F1 (.ZIP)](https://andyy-py.github.io/Proyecto-inge/Bitacora/ZIPS/Carrito.zip)
