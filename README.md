<!doctype html>
<html lang="es">
  <!-- Declara el tipo de documento como HTML5 y define que el idioma es español. -->
  <head>
    <meta charset="UTF-8" />
    <!-- Define la codificación de caracteres como UTF-8, permitiendo caracteres especiales. -->
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <!-- Configura la página para que sea adaptable a dispositivos móviles. -->
    <title>Index.html</title>
    <!-- Título de la página que aparece en la pestaña del navegador. -->
    <style>
      body {
        font-family: "Monaco", monospace;
        background-color: beige;
        color: black;
      }
      /* Estilo general del cuerpo de la página: fondo beige y texto negro. */

      header {
        background-color: white;
        color: black;
        text-align: center;
        padding: 20px;
      }
      /* Encabezado con fondo blanco y texto negro, centrado con padding de 20px. */

      header h1 {
        font-family: "Baskerville", serif;
        font-size: 2.5em;
      }
      /* Título del encabezado con fuente 'Baskerville' y tamaño de 2.5 veces el tamaño estándar. */

      .gallery {
        display: flex;
        flex-direction: column;
        justify-content: space-around;
        padding: 20px;
        margin: 20px;
        border: 5px solid black;
      }
      /* Galería con disposición en columna, espacio uniforme entre los elementos, margen externo de 20px y borde negro de 5px alrededor. */

      .gallery div {
        display: flex;
        align-items: center;
        margin-bottom: 20px;
        border: 5px solid black;
        padding: 10px;
      }
      /* Cada elemento de la galería es un contenedor flexible en fila, con imágenes y textos alineados, borde negro de 5px y un padding de 10px para espacio interno. */

      .gallery img {
        width: 200px;
        height: 200px;
        object-fit: cover;
        margin-right: 20px;
        border: 5px solid black;
      }
      /* Las imágenes de la galería tienen un tamaño fijo de 200x200px, ajustadas con un borde negro de 5px y un margen derecho de 20px para espacio. */

      .parrafo1,
      .parrafo2,
      .parrafo3,
      .parrafo4,
      .parrafo5 {
        font-family: "Arial", sans-serif;
        color: black;
      }
      /* Todos los párrafos tendrán fuente 'Arial' y el color del texto será negro. */

      footer {
        font-family: "Didot", serif;
        background-color: white;
        color: black;
        text-align: center;
        padding: 10px;
        position: fixed;
        bottom: 0;
        width: 100%;
      }
      /* Pie de página con fuente 'Didot', fondo blanco, texto negro, centrado y fijado al fondo de la pantalla. */
    </style>
  </head>
  <body>
    <header>
      <h1>
        Mi nombre es Daniel D. Sanchez y estás son las fotografias que no
        considero suficientemente satisfactorias a mi opinión personal.
      </h1>
    </header>
    <!-- El encabezado contiene un título (h1) que introduce la temática de la página. -->

    <section>
      <h2
        style="
          text-align: center;
          font-family: &quot;Source Code Pro&quot;, monospace;
          color: black;
        "
      >
        Colección de recuerdos
      </h2>
      <!-- Subtítulo centrado con una fuente de estilo monospace y color negro. -->
      <div class="gallery">
        <div>
          <img src="file:///C:/Users/Hp/Pictures/gym.jpg" alt="Foto 1" />
          <!-- Primera imagen de la galería con una descripción textual asociada. -->
          <p class="parrafo1">
            En esta foto me encuentro posando en el espejo del comedor de mi
            casa.
          </p>
          <!-- Primer párrafo, con estilo definido en la clase 'parrafo1'. -->
        </div>
        <div>
          <img src="gym.jpg" alt="Foto 2" />
          <!-- Segunda imagen de la galería. -->
          <p class="parrafo2">
            Esta imagen fue tomada en el gimnasio al cual voy.
          </p>
          <!-- Segundo párrafo, con estilo definido en la clase 'parrafo2'. -->
        </div>
        <div>
          <img src="12.jpg" alt="Foto 3" />
          <!-- Tercera imagen de la galería. -->
          <p class="parrafo3">
            En esta fotografía me la tome después de salir de una función de
            cinemark.
          </p>
          <!-- Tercer párrafo, con estilo definido en la clase 'parrafo3'. -->
        </div>
        <div>
          <img src="cab.jpg" alt="Foto 4" />
          <!-- Cuarta imagen de la galería. -->
          <p class="parrafo4">
            Está foto me la tome en el baño del colegio en el evento de
            expo-universidades.
          </p>
          <!-- Cuarto párrafo, con estilo definido en la clase 'parrafo4'. -->
        </div>
        <div>
          <img src="piano.png" alt="Foto 5" />
          <!-- Quinta imagen de la galería. -->
          <p class="parrafo5">
            Esta selfie que capture el momento en el cual estuve en el último
            piso de la corhuila de prado alto.
          </p>
          <!-- Quinto párrafo, con estilo definido en la clase 'parrafo5'. -->
        </div>
      </div>
    </section>
    <!-- Contenedor de la galería de imágenes con párrafos descriptivos. -->

    <footer>
      <p>
        Gracias por guiarme en este proceso de programación en el campo del
        desarrollo web.
      </p>
    </footer>
    <!-- Pie de página con un mensaje de agradecimiento. -->
  </body>
</html>
