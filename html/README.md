# Estructura general proyectos

```html
<!DOCTYPE html>
<html lang="es">
<head>

<!--
<meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" /> 
-->

  <title>NombreProyecto — Félix Rodríguez</title>

<!--
  <link rel="stylesheet" href="https://use.typekit.net/rlo4oiq.css">
  <link rel="stylesheet" href="../style.css" />
-->

  <style>
    /* === ESTRUCTURA GENERAL === */
    body {
      font-family: 'Consolas', Consolas, serif;
      color: #111;
      background: #fff;
      margin: 0;
    }

    header {
      background: white;
      border-bottom: 1px solid #ddd;
      padding: 1.2rem 2rem;
    }

    nav {
      display: flex;
      justify-content: space-between;
      align-items: center;
    }

    nav a {
      text-decoration: none;
      color: #111;
      font-style: italic;
      font-size: 1.2rem;
    }

    nav h1 {
      font-weight: 500;
      font-size: 1.6rem;
      margin: 0;
    }

    /* === CONTENIDO DEL PROYECTO === */

    main {
      max-width: 1100px;
      margin: 6rem auto;
      padding: 0 4rem;
      text-align: center;
    }

    .titulo {
      font-weight: 700;
      font-size: 3rem;
      margin-bottom: 0.5rem;
      letter-spacing: -0.03em;
    }

    .subtitulo {
      font-weight: 400;
      font-size: 1rem;
      color: #555;
      margin-bottom: 2rem;
    }

    .descripcion {
      font-weight: 400;
      font-size: 1.1rem;
      line-height: 1.6;
      max-width: 700px;
      margin: 0 auto 4rem auto;
    }

    /* === GALERÍA === */
    .galeria {
      display: flex;
      flex-direction: column;
      align-items: center;
      gap: 3rem;
    }

    figure {
      margin: 0;
      max-width: 800px;
    }

    figure img {
      width: 100%;
      height: auto;
      display: block;
      border-radius: 6px;
    }

    figcaption {
      font-size: 0.9rem;
      color: #666;
      margin-top: 0.5rem;
      text-align: center;
      font-weight: 400;
    }

    @media (max-width: 900px) {
      main {
        padding: 0 2rem;
        margin: 4rem auto;
      }

      .titulo {
        font-size: 2.2rem;
      }

      .descripcion {
        font-size: 1rem;
      }
    }
  </style>
</head>

<body>

<!--
  <header>
    <nav>
      <a href="../projects.html" class="nav-left">projects</a>
      <h1><a href="index.html">janis sepúlveda vera</a></h1>
      <a href="../about.html" class="nav-right">about</a>
    </nav>
  </header>
-->

  <main>
    <!-- === INFORMACIÓN DEL PROYECTO === -->
    <h1 class="titulo">nombreProyecto</h1>
    <h2 class="subtitulo">año</h2>
    <p class="descripcion">
  Descripción de los proyectos.

<!--
      <a href="enlace" target="_blank" rel="noopener" class="link-subrayado">
        altText
      </a>.
    </p>
-->

<!--
    <!-- === GALERÍA DE IMÁGENES === -->
    <section class="galeria">
      <figure>
        <img src="direccion de la imagen" alt="Imagen # del proyecto">
        <figcaption>Texto descriptivo</figcaption>
      </figure>
    </section>
-->
  </main>

</body>
</html>
```
