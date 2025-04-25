<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <title>Academia Preuniversitaria Alfa</title>
  <link rel="stylesheet" href="estilos.css">
</head>
<body>
  <header>
    <h1>Academia Preuniversitaria Alfa</h1>
    <nav>
      <a href="#inicio">Inicio</a>
      <a href="#sobre">Sobre nosotros</a>
      <a href="#cursos">Cursos</a>
      <a href="#inscripciones">Inscripciones</a>
      <a href="#contacto">Contacto</a>
    </nav>
  </header>

  <section id="inicio">
    <h2>¡Prepárate para ingresar a la universidad!</h2>
    <p>Te ayudamos a alcanzar tu meta con clases, simulacros y asesoría personalizada.</p>
  </section>

  <section id="sobre">
    <h2>Sobre Nosotros</h2>
    <p>Somos una academia especializada en preparar estudiantes para los exámenes de admisión a universidades.</p>
  </section>

  <section id="cursos">
    <h2>Cursos Disponibles</h2>
    <ul>
      <li>Matemáticas para ingreso</li>
      <li>Química básica y avanzada</li>
      <li>Razonamiento verbal y lógico</li>
      <li>Simulacros tipo examen</li>
    </ul>
  </section>

  <section id="inscripciones">
    <h2>Inscripciones</h2>
    <p>Abiertas todo el año. Clases presenciales y virtuales. ¡Inscríbete hoy!</p>
    <button onclick="mostrarAlerta()">Inscribirme</button>
  </section>

  <section id="contacto">
    <h2>Contacto</h2>
    <p>Email: contacto@academiaalfa.com</p>
    <p>Teléfono: +51 987 654 321</p>
    <p>Dirección: Av. Universidad 123, Ciudad</p>
  </section>

  <footer>
    <p>&copy; 2025 Academia Alfa. Todos los derechos reservados.</p>
  </footer>

  <script src="script.js"></script>
</body>
</html>
body {
  font-family: sans-serif;
  background-color: #f9f9f9;
  margin: 0;
  padding: 0;
}

header {
  background-color: #004080;
  color: white;
  padding: 20px;
  text-align: center;
}

nav a {
  color: white;
  margin: 0 15px;
  text-decoration: none;
}

section {
  padding: 40px;
  margin: 20px;
  background-color: white;
  border-radius: 10px;
  max-width: 800px;
  margin-left: auto;
  margin-right: auto;
}

footer {
  text-align: center;
  padding: 10px;
  background-color: #004080;
  color: white;
}

button {
  padding: 10px 20px;
  background-color: #0080ff;
  color: white;
  border: none;
  border-radius: 5px;
  cursor: pointer;
}

button:hover {
  background-color: #0066cc;
}
function mostrarAlerta() {
  alert("Gracias por tu interés. Pronto nos pondremos en contacto contigo.");
}
