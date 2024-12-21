<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Plataforma oficial de ADECONES: Innovación y atención al servicio comunitario">
    <title>ADECONES - Plataforma Comunitaria</title>
    <link rel="stylesheet" href="styles.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">
    <style>
        body {
            font-family: 'Century Gothic', Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f9;
        }

        header {
            background: linear-gradient(to right, #1d3557, #457b9d);
            color: white;
            text-align: center;
            padding: 1.5rem;
        }

        header h1 {
            font-size: 2.5rem;
            margin: 0;
        }

        nav ul {
            display: flex;
            justify-content: center;
            padding: 0;
            list-style: none;
        }

        nav ul li {
            margin: 0 15px;
        }

        nav ul li a {
            color: white;
            text-decoration: none;
            font-weight: bold;
            font-size: 1rem;
        }

        nav ul li a:hover {
            text-decoration: underline;
        }

        .banner {
            padding: 2rem;
            background-image: url('banner-image.jpg');
            background-size: cover;
            background-position: center;
            color: white;
            text-shadow: 2px 2px 5px rgba(0, 0, 0, 0.7);
        }

        .banner h2 {
            font-size: 1.8rem;
        }

        main {
            padding: 2rem;
            display: grid;
            grid-template-columns: 1fr;
            gap: 1.5rem;
        }

        .section {
            background: white;
            padding: 1.5rem;
            border-radius: 8px;
            box-shadow: 0px 4px 6px rgba(0, 0, 0, 0.1);
        }

        .section h2 {
            text-align: center;
            color: #1d3557;
            font-weight: bold;
            margin-bottom: 1rem;
        }

        .cta {
            text-align: center;
            margin-top: 1rem;
        }

        .cta a {
            background: #457b9d;
            color: white;
            padding: 0.7rem 1.2rem;
            border-radius: 5px;
            text-decoration: none;
            font-weight: bold;
        }

        .cta a:hover {
            background: #1d3557;
        }

        footer {
            background: #1d3557;
            color: white;
            text-align: center;
            padding: 1rem;
            margin-top: 2rem;
        }

        footer p {
            margin: 0;
        }
    </style>
</head>
<body>
    <header>
        <h1>ADECONES</h1>
        <p>Asociación para el Desarrollo Comunitario y la Inclusión Social</p>
        <nav>
            <ul>
                <li><a href="#inicio">Inicio</a></li>
                <li><a href="#noticias">Noticias</a></li>
                <li><a href="#atencion">Atención al Usuario</a></li>
                <li><a href="#foro">Foro</a></li>
                <li><a href="#contacto">Contacto</a></li>
            </ul>
        </nav>
    </header>

    <section class="banner">
        <h2>Unidos por el progreso y el bienestar de nuestra comunidad</h2>
        <div class="cta">
            <a href="#registro">¡Únete a Nosotros!</a>
        </div>
    </section>

    <main>
        <!-- Página Principal -->
        <section id="inicio" class="section">
            <h2>Página Principal</h2>
            <p>Descubre nuestra misión, visión y últimas noticias sobre proyectos comunitarios destacados.</p>
            <div class="cta">
                <a href="#noticias">Ver Noticias</a>
            </div>
        </section>

        <!-- Noticias -->
        <section id="noticias" class="section">
            <h2>Noticias</h2>
            <p>Accede a las noticias más recientes y relevantes sobre nuestras actividades y eventos.</p>
        </section>

        <!-- Atención al Usuario -->
        <section id="atencion" class="section">
            <h2>Atención al Usuario</h2>
            <p>Ofrecemos soporte personalizado para resolver tus dudas y atender tus solicitudes.</p>
        </section>

        <!-- Foro Comunitario -->
        <section id="foro" class="section">
            <h2>Foro Comunitario</h2>
            <p>Únete a las discusiones sobre temas de interés, comparte ideas y colabora con otros miembros de la comunidad.</p>
        </section>

        <!-- Contacto -->
        <section id="contacto" class="section">
            <h2>Contacto</h2>
            <p>Contáctanos a través de nuestros canales oficiales para recibir más información sobre nuestros proyectos y servicios.</p>
        </section>
    </main>

    <footer>
        <p>&copy; 2024 ADECONES. Todos los derechos reservados.</p>
    </footer>
</body>
</html>
