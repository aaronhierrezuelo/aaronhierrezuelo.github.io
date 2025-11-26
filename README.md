<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Aarón Hierrezuelo</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      background: #f5f5f5;
      color: #333;
    }
    header {
      background: white;
      padding: 1.5rem 2rem;
      display: flex;
      justify-content: space-between;
      align-items: center;
      border-bottom: 1px solid #ddd;
    }
    nav a {
      margin-left: 1.2rem;
      text-decoration: none;
      font-weight: bold;
      color: #333;
    }
    nav a:hover {
      color: #007bff;
    }
    .hero {
      padding: 4rem 2rem;
      text-align: center;
      background: white;
      margin-bottom: 2rem;
    }
    .hero h1 {
      font-size: 2.3rem;
      margin-bottom: 0.5rem;
    }
    .section {
      background: white;
      margin: 1rem auto;
      padding: 2rem;
      max-width: 900px;
      border-radius: 8px;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
    }
    .project {
      margin-bottom: 1.5rem;
    }
    footer {
      text-align: center;
      padding: 2rem;
      color: #666;
      font-size: 0.9rem;
    }
  </style>
</head>

<body>
  <header>
    <div class="logo">Aarón Hierrezuelo</div>
    <nav>
      <a href="#sobre">Sobre mí</a>
      <a href="#proyectos">Proyectos</a>
      <a href="#cv">CV</a>
      <a href="#contacto">Contacto</a>
    </nav>
  </header>

  <div class="hero">
    <h1>Hola, soy Aarón</h1>
    <p>Científico de Datos • Machine Learning • Econometría • Python</p>
  </div>

  <section id="sobre" class="section">
    <h2>Sobre mí</h2>
    <p>Soy estudiante de la Maestría en Ciencia de Datos y me interesa el análisis de datos, modelos predictivos y la generación de valor a partir de la información. Me gusta resolver problemas reales y comunicar resultados de forma clara.</p>
  </section>

  <section id="proyectos" class="section">
    <h2>Proyectos</h2>

    <div class="project">
      <h3>📊 Proyecto 1</h3>
      <p>Descripción breve del proyecto. Tecnologías usadas.</p>
      <a href="https://github.com/tuusuario/proyecto1" target="_blank">Ver en GitHub</a>
    </div>

    <div class="project">
      <h3>🤖 Proyecto 2</h3>
      <p>Descripción breve del proyecto.</p>
      <a href="https://github.com/tuusuario/proyecto2" target="_blank">Ver en GitHub</a>
    </div>

  </section>

  <section id="cv" class="section">
    <h2>CV</h2>
    <p>Puedes ver o descargar mi CV aquí:</p>
    <a href="cv.pdf" target="_blank">📄 Descargar CV</a>
  </section>

  <section id="contacto" class="section">
    <h2>Contacto</h2>
    <p>Email: aaron@example.com</p>
    <p>GitHub: <a href="https://github.com/aaronhierrezuelo" target="_blank">@aaronhierrezuelo</a></p>
  </section>

  <footer>
    © 2025 Aarón Hierrezuelo. Todos los derechos reservados.
  </footer>
</body>
</html>
