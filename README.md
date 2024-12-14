<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portal Interactivo de la Asociación</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Bienvenidos a [Nombre de la Asociación]</h1>
        <nav>
            <ul>
                <li><a href="#inicio">Inicio</a></li>
                <li><a href="#nosotros">Nosotros</a></li>
                <li><a href="#actividades">Actividades</a></li>
                <li><a href="#solicitudes">Solicitudes</a></li>
                <li><a href="#contacto">Contacto</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <section id="inicio">
            <h2>Inicio</h2>
            <p>Información breve sobre la asociación.</p>
        </section>
        <section id="nosotros">
            <h2>Nosotros</h2>
            <p>Texto sobre la misión, visión y valores.</p>
        </section>
        <section id="actividades">
            <h2>Actividades</h2>
            <p>Descripción de las actividades y eventos.</p>
        </section>
        <section id="solicitudes">
            <h2>Solicitudes</h2>
            <form>
                <label for="nombre">Nombre:</label>
                <input type="text" id="nombre" name="nombre">
                <label for="email">Correo:</label>
                <input type="email" id="email" name="email">
                <label for="mensaje">Mensaje:</label>
                <textarea id="mensaje" name="mensaje"></textarea>
                <button type="submit">Enviar</button>
            </form>
        </section>
        <section id="contacto">
            <h2>Contacto</h2>
            <p>Información de contacto y redes sociales.</p>
        </section>
    </main>
    <footer>
        <p>&copy; 2024 [Nombre de la Asociación]. Todos los derechos reservados.</p>
    </footer>
</body>
</html>
