# Dise-osX<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Mi Portafolio - Diseño Gráfico</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      background: #f4f4f4;
      color: #333;
    }

    header {
      background-color: #111;
      color: #fff;
      padding: 2rem 1rem;
      text-align: center;
    }

    header h1 {
      margin: 0;
      font-size: 2.5rem;
    }

    header p {
      font-size: 1.2rem;
      color: #ccc;
    }

    section {
      padding: 2rem 1rem;
      max-width: 900px;
      margin: auto;
    }

    h2 {
      color: #222;
      margin-bottom: 1rem;
      border-bottom: 2px solid #ddd;
      padding-bottom: 0.5rem;
    }

    .gallery {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 1rem;
    }

    .gallery img {
      width: 100%;
      border-radius: 8px;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
    }

    form {
      display: flex;
      flex-direction: column;
      gap: 1rem;
    }

    input, textarea {
      padding: 0.8rem;
      border: 1px solid #ccc;
      border-radius: 5px;
      font-size: 1rem;
    }

    button {
      background-color: #111;
      color: #fff;
      padding: 0.8rem;
      border: none;
      border-radius: 5px;
      cursor: pointer;
    }

    button:hover {
      background-color: #333;
    }

    footer {
      text-align: center;
      padding: 1rem;
      background-color: #111;
      color: #aaa;
    }
  </style>
</head>
<body>

  <header>
    <h1>Joaquín Cabañas</h1>
    <p>Diseñador Gráfico | Freelance</p>
  </header>

  <section>
    <h2>Sobre mí</h2>
    <p>Soy un diseñador gráfico apasionado por crear contenido visual atractivo y profesional. Me especializo en logos, banners, contenido para redes sociales y más.</p>
  </section>

  <section>
    <h2>Servicios</h2>
    <ul>
      <li>✅ Diseño de logos</li>
      <li>✅ Post para redes sociales</li>
      <li>✅ Miniaturas para YouTube</li>
      <li>✅ Flyers y tarjetas de presentación</li>
    </ul>
  </section>

  <section>
    <h2>Galería</h2>
    <div class="gallery">
      <img src="https://via.placeholder.com/300x200?text=Logo+1" alt="Trabajo 1" />
      <img src="https://via.placeholder.com/300x200?text=Banner+2" alt="Trabajo 2" />
      <img src="https://via.placeholder.com/300x200?text=Miniatura+3" alt="Trabajo 3" />
    </div>
  </section>

  <section>
    <h2>Contáctame</h2>
    <form onsubmit="enviarMensaje(); return false;">
      <input type="text" placeholder="Tu nombre" required />
      <input type="email" placeholder="Tu correo" required />
      <textarea rows="5" placeholder="Tu mensaje" required></textarea>
      <button type="submit">Enviar mensaje</button>
    </form>
  </section>

  <footer>
    <p>© 2025 Joaquín Cabañas - Todos los derechos reservados</p>
  </footer>

  <script>
    function enviarMensaje() {
      alert("Gracias por tu mensaje. ¡Te responderé pronto!");
    }
  </script>

</body>
</html>
