
Link directo a la página: https://valentinmendezf.github.io/Practico-CSS-Desarrollo-de-Software---2024/

# Desarrollo del Trabajo Práctico

A continuación se detallan los pasos y las actividades que deben llevar a cabo:

## 4.1 Cabecera de nuestra página

### Descripción:
- Crea una sección en tu archivo HTML que contenga un párrafo y un bloque de cita (`blockquote`).
- En tu archivo CSS, aplica propiedades de texto como `font-size`, `text-align`, `text-transform`, y `text-decoration` al párrafo y a la cita.
- Asegúrate de que el texto esté alineado y transformado según se indique, y que el `blockquote` tenga un estilo distintivo.

## 4.2 Propiedades de Texto en CSS

### Descripción:
- Crea una sección en tu archivo HTML que contenga un párrafo y un bloque de cita (`blockquote`).
- En tu archivo CSS, aplica propiedades de texto como `font-size`, `text-align`, `text-transform`, y `text-decoration` al párrafo y a la cita.
- Asegúrate de que el texto esté alineado y transformado según se indique, y que el `blockquote` tenga un estilo distintivo.

## 4.3 Propiedades de Caja en CSS

### Descripción:
- Añade una sección en tu HTML con dos elementos `div` que representen "cajas".
- En el CSS, aplica propiedades como `padding`, `margin`, `border`, `box-shadow`, y `background-color` a estas cajas.
- Una de las cajas debe estar destacada con un borde más grueso y un fondo diferente, mostrando variaciones en las propiedades de la caja.

## 4.4 Posición Relativa en CSS y Posición Absoluta en CSS

### Descripción:

#### Caja relativa:
- Crea un contenedor `div` con clase `relativo` en tu archivo HTML.
- En el CSS, aplica la propiedad `position: relative;` y ajusta las propiedades `top`, `left`, `background-color`, y `padding` para posicionar y estilizar este contenedor.
- Asegúrate de que el contenedor tenga un margen inferior suficiente para evitar solapamientos con otras secciones.

#### Caja absoluta:
- Dentro del contenedor relativo creado en el punto anterior, añade un `div` con la clase `absoluto`.
- En el CSS, aplica `position: absolute;` a este `div`, ajustando las propiedades `top` y `left` para posicionarlo adecuadamente dentro del contenedor padre.
- Asegúrate de que el `div` absoluto esté bien posicionado y tenga un estilo distinto para que sea fácilmente identificable.

## 4.5 Media Queries en CSS

### Descripción:
- Añade una media query en tu archivo CSS para ajustar el diseño cuando la pantalla tenga un ancho máximo de 768px.
- Cambia el color de fondo del `body` y reduce el tamaño de la fuente del encabezado (`h1`) para pantallas pequeñas.
- Asegúrate de que la sección tenga un ancho ajustado y un `padding` reducido en dispositivos móviles.

## 4.6 Principios de Grid en CSS

### Descripción:
- Crea un contenedor `div` con clase `grid-container` y al menos cuatro elementos `div` dentro de él con la clase `grid-item`.
- En el CSS, utiliza `display: grid;` y define una cuadrícula con `grid-template-columns: repeat(auto-fit, minmax(150px, 1fr));`.
- Añade espacio entre los elementos con `gap` y estiliza los elementos de la cuadrícula con fondo, `padding`, y alineación de texto.

## 4.7 Principios de Animaciones en CSS

### Descripción:
- Añade dos `div` en una sección, uno con clase `animacion` y otro con clase `mover`.
- En el CSS, define una animación usando `@keyframes` para mover el `div` con clase `mover` de izquierda a derecha de manera continua.
- Aplica una transición de color al `div` cuadrado con clase `animacion` que cambie cuando se haga `hover` sobre él.
