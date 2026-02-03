<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Roberto de Frutos Jiménez - Perfil</title>
  <!-- Google Fonts -->
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700&display=swap" rel="stylesheet">
  <!-- Font Awesome for icons -->
  <script src="https://kit.fontawesome.com/a076d05399.js" crossorigin="anonymous"></script>
  <style>
    /* Reset y tipografía */
    * { margin: 0; padding: 0; box-sizing: border-box; }
    body { font-family: 'Inter', sans-serif; background: #f4f7fa; color: #333; }
    a { text-decoration: none; color: inherit; }

    /* Contenedor principal */
    .container { max-width: 1100px; margin: auto; padding: 20px; }

    /* Cabecera */
    header { text-align: center; padding: 50px 20px 30px; }
    header h1 { font-size: 2.8rem; margin-bottom: 10px; }
    header p { font-size: 1.2rem; color: #555; margin-bottom: 20px; }
    header a { color: #0a66c2; font-weight: 600; }

    /* Secciones */
    section { margin-bottom: 50px; }

    /* Sobre mí */
    .about p { margin: 10px 0; line-height: 1.6; }

    /* Tarjetas de skills */
    .skills { display: flex; flex-wrap: wrap; gap: 20px; justify-content: center; }
    .card {
      background: white; padding: 20px; border-radius: 12px; flex: 1 1 200px;
      box-shadow: 0 10px 20px rgba(0,0,0,0.05); transition: transform 0.3s, box-shadow 0.3s;
    }
    .card:hover { transform: translateY(-5px); box-shadow: 0 15px 25px rgba(0,0,0,0.1); }
    .card h3 { margin-bottom: 10px; font-size: 1.1rem; color: #0a66c2; }
    .card img { height: 25px; margin-right: 5px; vertical-align: middle; }

    /* Estadísticas */
    .stats { display: flex; flex-wrap: wrap; gap: 20px; justify-content: center; }
    .stats img { border-radius: 12px; }

    /* Contacto */
    .contact a { display: inline-block; margin: 10px; padding: 12px 20px; border-radius: 8px; color: white; font-weight: 600; transition: 0.3s; }
    .linkedin { background: #0a66c2; }
    .linkedin:hover { background: #084c8d; }
    .email { background: #d14836; }
    .email:hover { background: #a73628; }

    /* Footer */
    footer { text-align: center; padding: 30px 20px; color: #777; }
  </style>
</head>
<body>
  <div class="container">
    <!-- Cabecera -->
    <header>
      <h1>👋 ¡Hola! Soy Roberto de Frutos Jiménez</h1>
      <p>💻 Desarrollador FULL STACK · Backend con <strong>Java + Spring Boot</strong> · Frontend con <strong>React</strong></p>
      <p>🚀 Apasionado por construir soluciones eficientes, seguras y bien diseñadas</p>
      <p><a href="https://robertodfj.netlify.app/" target="_blank">Mi Portfolio</a></p>
    </header>

    <!-- Sobre mí -->
    <section class="about">
      <h2>🧠 Sobre mí</h2>
      <p>Soy un desarrollador web full stack, combinando un backend robusto con <strong>Spring Boot</strong> y un frontend interactivo con <strong>React</strong>.</p>
      <p>🔍 Me gusta trabajar en proyectos reales aplicando buenas prácticas de arquitectura, seguridad, diseño UI y consumo de APIs.</p>
      <p>📚 Siempre estoy aprendiendo nuevas tecnologías para construir aplicaciones más sólidas, funcionales y escalables.</p>
    </section>

    <!-- Idiomas -->
    <section>
      <h2>🌍 Idiomas</h2>
      <p>🇪🇸 Español — nativo</p>
      <p>🇬🇧 Inglés — intermedio</p>
    </section>

    <!-- Tecnologías -->
    <section>
      <h2>💻 Tecnologías que uso</h2>
      <div class="skills">
        <div class="card"><h3>Lenguajes & Frameworks</h3>
          <p><img src="https://img.shields.io/badge/Java-ED8B00?style=flat&logo=openjdk&logoColor=white"> Java</p>
          <p><img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black"> JavaScript</p>
          <p><img src="https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white"> HTML5</p>
          <p><img src="https://img.shields.io/badge/Spring%20Boot-6DB33F?style=flat&logo=spring&logoColor=white"> Spring Boot</p>
          <p><img src="https://img.shields.io/badge/React-61DAFB?style=flat&logo=react&logoColor=black"> React</p>
        </div>

        <div class="card"><h3>Bases de datos</h3>
          <p><img src="https://img.shields.io/badge/MySQL-4479A1?style=flat&logo=mysql&logoColor=white"> MySQL</p>
          <p><img src="https://img.shields.io/badge/MongoDB-4EA94B?style=flat&logo=mongodb&logoColor=white"> MongoDB</p>
          <p><img src="https://img.shields.io/badge/MariaDB-003545?style=flat&logo=mariadb&logoColor=white"> MariaDB</p>
        </div>

        <div class="card"><h3>Otras herramientas</h3>
          <p><img src="https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white"> GitHub</p>
          <p><img src="https://img.shields.io/badge/Vercel-000000?style=flat&logo=vercel&logoColor=white"> Vercel</p>
          <p><img src="https://img.shields.io/badge/Netlify-00C7B7?style=flat&logo=netlify&logoColor=white"> Netlify</p>
          <p><img src="https://img.shields.io/badge/NPM-CB3837?style=flat&logo=npm&logoColor=white"> NPM</p>
          <p><img src="https://img.shields.io/badge/TailwindCSS-38B2AC?style=flat&logo=tailwind-css&logoColor=white"> TailwindCSS</p>
        </div>
      </div>
    </section>

    <!-- Contacto -->
    <section class="contact" style="text-align:center;">
      <h2>🌐 Conecta conmigo</h2>
      <a class="linkedin" href="https://www.linkedin.com/in/roberto-de-frutos-jimenez-a9b591308/" target="_blank"><i class="fab fa-linkedin"></i> LinkedIn</a>
      <a class="email" href="mailto:robertodfj93@gmail.com"><i class="fas fa-envelope"></i> Email</a>
    </section>

    <!-- Footer -->
    <footer>
      <p>© 2026 Roberto de Frutos Jiménez</p>
    </footer>
  </div>
</body>
</html>
