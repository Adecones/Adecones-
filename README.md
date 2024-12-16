<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ADECONES - Sube tu Contenido</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>ADECONES</h1>
        <nav>
            <ul>
                <li><a href="index.html">Inicio</a></li>
                <li><a href="publicaciones.html">Publicaciones</a></li>
                <li><a href="subir.html">Sube tu Contenido</a></li>
            </ul>
        </nav>
    </header>

    <main>
        <section>
            <h2>Sube tu Contenido</h2>
            <p>Comparte tus noticias, eventos, imágenes o artículos con nuestra comunidad.</p>
            <form action="upload.php" method="POST" enctype="multipart/form-data">
                <label for="titulo">Título del Contenido:</label>
                <input type="text" id="titulo" name="titulo" required>
                
                <label for="descripcion">Descripción:</label>
                <textarea id="descripcion" name="descripcion" rows="5" required></textarea>
                
                <label for="categoria">Categoría:</label>
                <select id="categoria" name="categoria">
                    <option value="noticia">Noticia</option>
                    <option value="evento">Evento</option>
                    <option value="social">Social</option>
                    <option value="informativo">Informativo</option>
                </select>
                
                <label for="archivo">Subir Archivo:</label>
                <input type="file" id="archivo" name="archivo" accept="image/*,video/*,application/pdf" required>
                
                <button type="submit">Enviar</button>
            </form>
        </section>
    </main>

    <footer>
        <p>&copy; 2024 ADECONES. Todos los derechos reservados.</p>
    </footer>
</body>
</html>
body {
    font-family: 'Roboto', sans-serif;
    line-height: 1.6;
    margin: 0;
    padding: 0;
    background-color: #f4f4f4;
}

header {
    background: #0044cc;
    color: white;
    padding: 1rem 0;
    text-align: center;
}

nav ul {
    list-style: none;
    padding: 0;
    display: flex;
    justify-content: center;
    margin: 0;
}

nav ul li {
