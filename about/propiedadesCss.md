🔹 Espaciado y cajas

margin: espacio afuera del elemento (lo separa de otros).

padding: espacio adentro entre el borde y el contenido.

border: línea que rodea el elemento.

border-radius: redondea las esquinas.

box-sizing: border-box: hace que width y height incluyan también el padding y el border.

🔹 Texto

color: color del texto.

font-family: tipo de letra.

font-size: tamaño de fuente.

line-height: altura de línea (espaciado vertical entre renglones).

letter-spacing: espacio entre letras.

text-align: alineación (izquierda, centro, derecha).

text-shadow: efecto de sombra en el texto.

strong { color: … }: cambia el color o estilo del texto en negrita.

🔹 Fondos y colores

background: color o gradiente de fondo.

background-color: solo color de fondo.

radial-gradient(...): fondo degradado en forma de círculo.

linear-gradient(...): fondo degradado en línea.

rgba(r,g,b,a): color con transparencia (el a es opacidad de 0 a 1).

🔹 Imágenes

object-fit: cover: recorta la imagen para llenar su contenedor (sin deformarse).

object-fit: contain: ajusta la imagen completa dentro del contenedor (pueden quedar bordes).

border-radius: 50%: hace la imagen circular.

filter: drop-shadow(...): agrega sombra a la imagen.

🔹 Layout (organización)

display: block: ocupa todo el ancho disponible (por defecto en divs).

display: flex: organiza elementos en fila o columna.

flex-direction: define si se ordenan en row (fila) o column (columna).

align-items: alinea elementos verticalmente dentro de un contenedor flex.

justify-content: alinea elementos horizontalmente dentro de un contenedor flex.

display: grid: activa el sistema de rejilla.

grid-template-columns: repeat(auto-fit, minmax(120px, 1fr)):

repeat(...): repite columnas automáticamente.

auto-fit: las ajusta al espacio disponible.

minmax(120px, 1fr): cada columna mide mínimo 120px y máximo todo lo que pueda (1fr).

gap: espacio entre filas y columnas en grid o flex.

🔹 Sombras y efectos

box-shadow: x y blur color: sombra en cajas.

x: desplazamiento horizontal.

y: desplazamiento vertical.

blur: qué tan difusa es.

transition: propiedad tiempo ease: anima cambios (ej: hover).

transform: translateY(-4px): mueve el elemento hacia arriba 4px.

hover: estado cuando el mouse pasa encima.

focus-visible: estado cuando navegas con teclado y el elemento está enfocado.

🔹 Responsividad

@media (max-width: 640px) { ... }: reglas para pantallas pequeñas (móviles).

clamp(min, preferido, max): hace que el tamaño sea responsivo, variando entre un mínimo y un máximo según la pantalla.

🔹 Accesibilidad y detalles

list-style: none: quita viñetas a listas.

cursor: pointer: cambia el cursor a mano (en botones/enlaces).

outline: contorno visible cuando un elemento está enfocado (importante para accesibilidad).