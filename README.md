# Diseño de niveles · Diplomatura en Desarrollo de Videojuegos

Presentación web para la línea de Producción y Diseño. Repositorio separado del módulo integrador, con una estética y controles similares.

## Clase 1

**El nivel como experiencia de juego.** 22 diapositivas y una planificación de 120 minutos, incluida una pausa y un taller de diseño en papel.

Contenidos: intención de experiencia, acciones del jugador, escala y cámara, aprendizaje, diseño sistémico, recorridos, orientación y decisiones. Referencias: Raph Koster, Will Wright, Dan Taylor y The Level Design Book.

Abrir `index.html` en un navegador. No requiere instalación, compilación ni dependencias. Los estilos, el contenido y la navegación están incluidos en `clase-1.html` para poder descargar una versión completa después de editar los videos.

## Controles

- Flechas izquierda/derecha, espacio o botones inferiores: avanzar y retroceder.
- Selector inferior: ir a una diapositiva.
- `O`: vista general de diapositivas.
- `N`: mostrar u ocultar notas docentes.
- `F`: pantalla completa.
- `Home` y `End`: primera y última diapositiva.

Las notas docentes se ocultan durante la presentación, pero forman parte del HTML público. No contienen información privada.

## Videos de YouTube

La portada y el caso de análisis incluyen una selección inicial de gameplay de Portal.

1. Ir a la diapositiva elegida.
2. Pulsar **Agregar video** o **Cambiar video**.
3. Pegar una URL de YouTube, indicar un título y el segundo inicial del fragmento.
4. Pulsar **Aplicar**.

El editor acepta enlaces `youtube.com/watch`, `youtu.be`, `shorts`, `live` y `embed`. Los cambios duran durante la sesión. Para conservarlos, pulsar **Descargar con cambios**. El navegador descarga un HTML autónomo llamado `index.html`: renombrarlo como `clase-1.html` y reemplazar el archivo del repositorio. La portada `index.html` del repositorio mantiene su función de entrada.

Se pueden incluir videos en cualquier diapositiva y quitarlos con **Quitar video**. Al cambiar de diapositiva se descarga el reproductor anterior, deteniendo su reproducción.

Los videos requieren internet y que el autor permita su inserción. Abrir el HTML directamente desde el disco puede impedir que YouTube valide el origen del reproductor. Para comprobar la inserción, usar GitHub Pages o un servidor HTTP local. Cada video ofrece **Abrir en YouTube** como alternativa. La reproducción embebida debe comprobarse después de publicar.

## GitHub Pages

1. Subir `index.html`, `clase-1.html` y `README.md` a la raíz del nuevo repositorio.
2. Abrir **Settings → Pages**.
3. Elegir **Deploy from a branch**.
4. Seleccionar **main** y **/(root)**.

GitHub mostrará la URL pública cuando termine la publicación.

## Edición del contenido

El bloque `<script id="slideData" type="application/json">` de `clase-1.html` contiene las diapositivas. Cada una tiene sección, título, contenido HTML, duración, notas y video opcional. Las duraciones suman 120 minutos.

La clase 2 todavía no está incluida. Podrá incorporarse como `clase-2.html` cuando se defina su contenido.
