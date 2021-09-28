# Trabajo Practico de Sistema Solar

[Video explicando el enunciado](https://youtu.be/2GBGxF-i-iU)

[Pagina de version final](https://luisparedes1.github.io/Sistema-Solar/)

Se debe modelar el sistema solar, teniendo la tierra rotando alrededor del sol, la luna rotando al rededor de la tierra, y otros componentes.

Ejes de coordenadas y escalas
---

La grilla esta definida en el plano XZ, el eje +Y es normal al plano.
Cada celda de la grilla mida 20x20 unidades

## Consigna


Definir las matrices de transformacion de la Tierra, la Luna, la Estacion Espacial (ISS) y la nave Apollo, 
para recrear los  movimientos reales de cada cuerpo.

## Condiciones a cumplir:

1) NO ESTA PERMITIDO el uso de funciones trigonometricas (seno y coseno) para el cálculo de las orbitas, 
deben usar matrices de rotación y traslación para resolverlo

2) La tierra rota alrededor del sol sobre el plano XZ (ciclo anual)
3) La tierra tiene su eje inclinado de 23 grados respecto del eje +Y (arriba). 
4) La tierra rota sobre su eje (ciclo del día)

IMPORTANTE: tener en cuenta la relación de la inclinacion de 23 grados, con las estaciones del año
            ver imágenes en la carpeta img/ para mas detalles

4) Rotación de la luna alrededor de la tierra (una vuelta cada 30 días y siempre expone la misma cara hacia la tierra)
5) La nave Apolo debe estar ubicada sobre la cara oculta de la luna
6) La ISS debe orbital alrededor de la tierra pasando por encima y por debajo de la misma

La variable tiempo, son los segundos desde que arranco la aplicación
