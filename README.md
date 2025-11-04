# RUNEXX
Marca exclusivamente para la venta de prendas deportivas (Zapatillas, urbanas, casuales, runnes), tambien ropa deportivas (buzos, polos, short).
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <title>RUNEXX | Marca Deportiva</title>
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@700;900&display=swap" rel="stylesheet">
  <style>
    /* RESET Y FONDO */
    body {
      margin: 0;
      padding: 0;
      font-family: 'Montserrat', Impact, Arial, sans-serif;
      background-color: #000;
      color: #FFD600;
      min-height: 100vh;
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: flex-start;
    }
    /* CABECERA Y LOGO */
    header {
      width: 100%;
      text-align: center;
      padding-top: 40px;
      margin-bottom: 32px;
    }
    .logo-img {
      max-width: 250px;
      margin-bottom: 18px;
    }
    /* TÍTULO */
    h1 {
      font-size: 3em;
      letter-spacing: 2px;
      font-weight: 900;
      color: #FFD600;
      margin: 0 0 8px 0;
      text-shadow: 1px 2px 8px #222;
    }
    /* DESCRIPCIÓN PRINCIPAL */
    .description {
      font-size: 1.15em;
      color: #222;
      background: #FFD600;
      padding: 12px 28px;
      border-radius: 12px;
      display: inline-block;
      margin-top: 16px;
      font-weight: 700;
      box-shadow: 0 2px 18px #FFD60044;
    }
    /* SECCIÓN DE VALORES */
    .brand-values {
      margin: 44px 0 0 0;
      padding: 0;
      list-style: none;
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 36px;
    }
    .brand-values li {
      background: #1a1a1a;
      border: 2px solid #FFD600;
      border-radius: 8px;
      color: #FFD600;
      font-weight: 700;
      padding: 18px 30px;
      font-size: 1.1em;
      box-shadow: 0 4px 16px #FFD60033;
      transition: background 0.3s;
    }
    .brand-values li:hover {
      background: #FFD600;
      color: #1a1a1a;
      cursor: pointer;
    }
    /* ICONO ESTRELLA */
    .star-accent {
      font-size: 2.5em;
      color: #FFD600;
      margin-top: 28px;
    }
    /* SECCIÓN REDES SOCIALES */
    .social-links {
      margin-top: 44px;
      text-align: center;
    }
    .social-links a {
      color: #FFD600;
      margin: 0 16px;
      font-size: 2.1em;
      text-decoration: none;
      transition: color 0.2s;
    }
    .social-links a:hover {
      color: #fff200;
    }
    /* FOOTER */
    footer {
      margin-top: auto;
      width: 100%;
      text-align: center;
      padding: 28px 0 14px 0;
      color: #FFD600;
      font-size: 1em;
      background: #111;
      opacity: 0.82;
    }
    /* RESPONSIVE */
    @media (max-width: 550px) {
      .description {padding: 8px 8px;}
      h1 { font-size: 2em; }
      .brand-values { gap: 12px;}
      .brand-values li {padding: 10px 12px;}
      .logo-img {max-width: 140px;}
    }
  </style>
</head>
<body>
  <header>
    <!-- Si tienes un logo llamado logo.png, súbelo al repo y activa la línea de abajo -->
    <!-- <img src="logo.png" class="logo-img" alt="Logo RUNEXX"> -->

    <h1>RUNEXX</h1>
    <div class="description">
      Marca deportiva que une energía, estilo y funcionalidad.<br>
      BLACK & YELLOW como declaración de movimiento y pasión.
    </div>
    <div class="star-accent">★</div>
  </header>

  <ul class="brand-values">
    <li>Energía</li>
    <li>Velocidad</li>
    <li>Innovación</li>
    <li>Estilo Deportivo</li>
    <li>Superación</li>
  </ul>

  <section class="social-links">
    <!-- Agrega tus redes cambiando los links abajo -->
    <a href="https://instagram.com/runexx" target="_blank" title="Instagram">&#x1F47B;</a>
    <a href="https://facebook.com/runexx" target="_blank" title="Facebook">&#x1F426;</a>
    <a href="mailto:runexx@email.com" title="Email">&#x2709;&#xFE0F;</a>
    <!-- Puedes usar iconos SVG reales para mayor estilo! -->
  </section>

  <footer>
    &copy; 2025 RUNEXX · Todos los derechos reservados
  </footer>
</body>
</html>
