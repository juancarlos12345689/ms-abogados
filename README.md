<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>MS ABOGADOS</title>
  <style>
    body { font-family: Arial, sans-serif; margin: 0; padding: 0; background: #f9f9f9; color: #222; }
    header { background: #0f2c59; color: white; padding: 20px; text-align: center; }
    nav { background: #fff; padding: 10px 20px; text-align: right; box-shadow: 0 2px 4px rgba(0,0,0,0.1); }
    nav a { margin-left: 20px; text-decoration: none; color: #0f2c59; font-weight: bold; }
    .hero { padding: 60px 20px; text-align: center; background: #e9f0fa; }
    .hero h1 { font-size: 2.5em; color: #0f2c59; }
    .hero ul { list-style: none; padding: 0; }
    .hero ul li::before { content: '✓ '; color: #0f2c59; }
    .cta-button { margin-top: 20px; background: #0f2c59; color: white; padding: 12px 24px; border: none; cursor: pointer; font-size: 1em; }
    .section { padding: 40px 20px; text-align: center; }
    .section h2 { color: #0f2c59; margin-bottom: 20px; }
    .icons { display: flex; justify-content: center; flex-wrap: wrap; gap: 20px; }
    .icon-box { background: white; padding: 20px; border-radius: 8px; width: 120px; box-shadow: 0 2px 8px rgba(0,0,0,0.1); }
    .icon-box img { width: 40px; height: 40px; margin-bottom: 10px; }
    .testimonial { background: #fff; padding: 20px; margin: 20px auto; width: 80%; border-left: 5px solid #0f2c59; font-style: italic; }
    footer { background: #0f2c59; color: white; text-align: center; padding: 20px; margin-top: 40px; }
  </style>
</head>
<body>
  <header>
    <h1>MS ABOGADOS</h1>
  </header>
  <nav>
    <a href="#inicio">INICIO</a>
    <a href="#servicios">SERVICIOS</a>
    <a href="#nosotros">NOSOTROS</a>
  </nav>

  <div class="hero" id="inicio">
    <h1>Tu tranquilidad legal comienza aquí</h1>
    <ul>
      <li>Equipo con experiencia</li>
      <li>Atención personalizada</li>
      <li>Consultas accesibles</li>
    </ul>
    <button class="cta-button">AGENDAR CITA GRATUITA</button>
  </div>

  <div class="section" id="servicios">
    <h2>Áreas de Especialización</h2>
    <div class="icons">
      <div class="icon-box">
        <img src="https://img.icons8.com/ios-filled/50/000000/courthouse.png" alt="Civil">
        <p>Civil</p>
      </div>
      <div class="icon-box">
        <img src="https://img.icons8.com/ios-filled/50/000000/family.png" alt="Familiar">
        <p>Familiar</p>
      </div>
      <div class="icon-box">
        <img src="https://img.icons8.com/ios-filled/50/000000/gavel.png" alt="Penal">
        <p>Penal</p>
      </div>
      <div class="icon-box">
        <img src="https://img.icons8.com/ios-filled/50/000000/briefcase.png" alt="Laboral">
        <p>Laboral</p>
      </div>
      <div class="icon-box">
        <img src="https://img.icons8.com/ios-filled/50/000000/company.png" alt="Empresarial">
        <p>Empresarial</p>
      </div>
    </div>
  </div>

  <div class="section">
    <h2>Testimonios</h2>
    <div class="testimonial">
      "Excelente servicio y asesoría legal. Me ayudaron a resolver mi caso de manera rápida y eficaz."<br><br>
      <strong>- Laura M.</strong>
    </div>
  </div>

  <footer>
    &copy; 2025 MS ABOGADOS | Todos los derechos reservados
  </footer>
</body>
</html>
