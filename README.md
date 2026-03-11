# silver-disco
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <title>Herrería y Aluminio Karlo</title>
  <style>
    body { font-family: Arial, sans-serif; margin:0; background:#f9f9f9; }
    nav { background:#333; padding:15px; text-align:center; }
    nav a { color:white; margin:0 15px; text-decoration:none; font-weight:bold; }
    header { background:url('portada.jpg') center/cover; color:white; padding:100px; text-align:center; }
    header h1 { font-size:3em; margin:0; }
    section { padding:50px; max-width:1000px; margin:auto; }
    h2 { color:#333; margin-bottom:20px; }
    ul { list-style:none; padding:0; }
    ul li { background:#eee; margin:10px 0; padding:10px; border-left:5px solid #333; }
    .galeria { display:flex; flex-wrap:wrap; justify-content:center; }
    .galeria img { width:250px; margin:10px; border:2px solid #ccc; border-radius:5px; }
    footer { background:#333; color:white; text-align:center; padding:20px; }
  </style>
</head>
<body>
  <nav>
    <a href="#inicio">Inicio</a>
    <a href="#servicios">Servicios</a>
    <a href="#galeria">Galería</a>
    <a href="#contacto">Contacto</a>
  </nav>

  <header id="inicio">
    <h1>Herrería y Aluminio Karlo</h1>
    <p>Puertas, ventanas y canceles de calidad</p>
  </header>

  <section id="servicios">
    <h2>Servicios</h2>
    <ul>
      <li>Puertas de aluminio</li>
      <li>Puertas de herrería</li>
      <li>Ventanas</li>
      <li>Canceles</li>
      <li>Diseños personalizados</li>
    </ul>
  </section>

  <section id="galeria" class="galeria">
    <h2>Galería de trabajos</h2>
    <img src="puerta1.jpg" alt="Puerta de aluminio">
    <img src="ventana1.jpg" alt="Ventana de herrería">
    <img src="cancel1.jpg" alt="Cancel moderno">
    <img src="puerta2.jpg" alt="Puerta de herrería clásica">
  </section>

  <section id="contacto">
    <h2>Contacto</h2>
    <p>Tel: 33-1234-5678</p>
    <p>Email: pinedacoronadok@gmail.com</p>
    <p>WhatsApp: 771-469-9994</p>
  </section>

  <footer>
    <p>© 2026 Herrería y Aluminio Karlo</p>
  </footer>
</body>
</html>