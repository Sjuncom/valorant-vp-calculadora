# Calculadora de Valorant Points

Herramienta web para calcular la combinación **más barata** de paquetes de Valorant Points (VP) que necesitas comprar para llegar a la cantidad de VP que quieres tener.

## ¿Qué hace?

1. Le dices cuántos VP quieres tener en total y cuántos ya tienes.
2. La calculadora prueba todas las combinaciones posibles de paquetes disponibles.
3. Te devuelve la combinación que cubre lo que te falta al **menor costo posible** — y si dos combinaciones cuestan lo mismo, elige la que te da más VP.

## Uso

No necesita instalación ni servidor. Solo abre [`calculadora_vp.html`](./calculadora_vp.html) en cualquier navegador, o entra al link publicado con GitHub Pages.

Los paquetes (VP y precio) son editables directamente en la tabla, así que puedes ajustarlos si cambian de precio o si tu región tiene precios distintos.

## Cómo funciona

Todo corre en el navegador con HTML, CSS y JavaScript — no se conecta a ningún servidor ni API. El cálculo usa programación dinámica (similar al clásico problema de "dar cambio con monedas") para encontrar la combinación de paquetes de menor costo que cubra la cantidad de VP faltante.

## Aviso

Este proyecto no tiene ninguna afiliación con Riot Games. Los precios de los paquetes se editan manualmente porque no existe una API pública oficial para obtener los precios de la tienda de VALORANT.
