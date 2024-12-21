<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Plataforma oficial de la Asociación de Desarrollo Comunitario">
    <title>Asociación Comunitaria</title>
    <link rel="stylesheet" href="styles.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">
</head>
<body>
    <!-- Página Principal -->
    <header>
        <div class="banner">
            <h1>Bienvenidos a la Asociación Comunitaria</h1>
            <p>Unidos por el desarrollo y bienestar de nuestra comunidad</p>
        </div>
        <nav>
            <ul>
                <li><a href="#noticias">Noticias</a></li>
                <li><a href="#atencion">Atención al Usuario</a></li>
                <li><a href="#foro">Foro</a></li>
                <li><a href="#registro">Registro</a></li>
            </ul>
        </nav>
    </header>

    <main>
        <!-- Noticias Destacadas -->
        <section id="noticias">
            <h2>Noticias Destacadas</h2>
            <div class="carousel">
                <div class="noticia">
                    <img src="noticia1.jpg" alt="Evento Comunitario">
                    <p>Gran evento comunitario este fin de semana. ¡Participa!</p>
                </div>
                <div class="noticia">
                    <img src="noticia2.jpg" alt="Nuevo Proyecto Educativo">
                    <p>Se lanza un nuevo proyecto educativo para niños y jóvenes.</p>
                </div>
                <div class="noticia">
                    <img src="noticia3.jpg" alt="Apoyo a Pescadores">
                    <p>Programa de apoyo a pescadores locales. Conoce más detalles.</p>
                </div>
            </div>
        </section>

        <!-- Atención al Usuario -->
        <section id="atencion">
            <h2>Atención al Usuario</h2>
            <div class="atencion">
                <div>
                    <h3>Chat en Línea</h3>
                    <p>Resuelve tus dudas con nuestro soporte instantáneo.</p>
                </div>
                <div>
                    <h3>Formulario de Contacto</h3>
                    <form>
                        <label for="nombre">Nombre:</label>
                        <input type="text" id="nombre" name="nombre" required>

                        <label for="email">Correo Electrónico:</label>
                        <input type="email" id="email" name="email" required>

                        <label for="mensaje">Mensaje:</label>
                        <textarea id="mensaje" name="mensaje" rows="4" required></textarea>

                        <button type="submit">Enviar</button>
                    </form>
                </div>
                <div>
                    <h3>Buzón de Sugerencias</h3>
                    <p>Envíanos tus ideas para mejorar la comunidad.</p>
                </div>
            </div>
        </section>

        <!-- Foro Comunitario -->
        <section id="foro">
            <h2>Foro Comunitario</h2>
            <p>Participa en debates y comparte tus opiniones sobre proyectos, actividades y más.</p>
            <div class="foro">
                <div class="hilo">
                    <h3>Proyectos Actuales</h3>
                    <p>Comparte tus ideas y comentarios sobre los proyectos en curso.</p>
                </div>
                <div class="hilo">
                    <h3>Educación</h3>
                    <p>Discute programas educativos y sus impactos.</p>
                </div>
            </div>
        </section>

        <!-- Registro e Inscripción -->
        <section id="registro">
            <h2>Registro e Inscripción</h2>
            <form>
                <label for="nombre">Nombre Completo:</label>
                <input type="text" id="nombre" name="nombre" required>

                <label for="cedula">Cédula:</label>
                <input type="text" id="cedula" name="cedula" required>

                <label for="email">Correo Electrónico:</label>
                <input type="email" id="email" name="email" required>

                <label for="documentos">Adjuntar Documentos:</label>
                <input type="file" id="documentos" name="documentos" multiple>

                <button type="submit">Enviar Solicitud</button>
            </form>
        </section>
    </main>

    <!-- Información y Contactos -->
    <footer>
        <section id="informacion">
            <h2>Información de Contacto</h2>
            <p><strong>Dirección:</strong> Calle 10-42, San Antero, Córdoba</p>
            <p><strong>Teléfono:</strong> +57 320 123 4567</p>
            <p><strong>Email:</strong> contacto@asociacioncomunitaria.org</p>
            <div class="mapa">
                <iframe src="https://www.google.com/maps/embed?..." width="600" height="450" style="border:0;" allowfullscreen="" loading="lazy"></iframe>
            </div>
        </section>
    </footer>
</body>
</html>
