<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ANTARES - Soluciones Comunicacionales</title>
    <style>
        body {
            font-family: 'Arial Rounded MT Bold', Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f5f5f5;
            color: #333;
        }
        header {
            background-color: #113B49;
            color: #fff;
            padding: 20px 0;
            text-align: center;
        }
        header h1 {
            margin: 0;
            font-size: 2.5em;
        }
        nav {
            background-color: #319966;
            overflow: hidden;
        }
        nav a {
            float: left;
            display: block;
            color: white;
            text-align: center;
            padding: 14px 20px;
            text-decoration: none;
        }
        nav a:hover {
            background-color: #113B49;
        }
        section {
            padding: 20px;
            max-width: 1200px;
            margin: auto;
        }
        footer {
            background-color: #113B49;
            color: #fff;
            text-align: center;
            padding: 10px 0;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
        .social-icons a {
            margin: 0 10px;
            color: white;
            text-decoration: none;
        }
        .social-icons a:hover {
            color: #ffcc00;
        }
        .clients img {
            max-width: 100px;
            margin: 10px;
        }
    </style>
</head>
<body>
    <header>
        <h1>ANTARES</h1>
        <p>Soluciones Comunicacionales Digitales e Impresas</p>
    </header>
    <nav>
        <a href="#contact">Contactos</a>
        <a href="#about">Quiénes Somos</a>
        <a href="#blog">Blog</a>
        <a href="#clients">Clientes</a>
        <a href="#portfolio">Portafolio</a>
        <a href="#social">Redes Sociales</a>
    </nav>
    <section id="contact">
        <h2>Contactos</h2>
        <p>¿Tienes alguna pregunta o quieres trabajar con nosotros? Contáctanos:</p>
        <form action="mailto:contacto@antares.com" method="post" enctype="text/plain">
            <label for="name">Nombre:</label><br>
            <input type="text" id="name" name="name" required><br>
            <label for="email">Email:</label><br>
            <input type="email" id="email" name="email" required><br>
            <label for="message">Mensaje:</label><br>
            <textarea id="message" name="message" rows="4" required></textarea><br>
            <input type="submit" value="Enviar">
        </form>
    </section>
    <section id="about">
        <h2>Quiénes Somos</h2>
        <p>ANTARES es una agencia de comunicación dedicada a proporcionar soluciones comunicacionales digitales e impresas. Personalizamos todos nuestros servicios para satisfacer las necesidades específicas de nuestros clientes.</p>
    </section>
    <section id="blog">
        <h2>Blog</h2>
        <p>Lee nuestras últimas publicaciones sobre comunicación e innovación:</p>
        <!-- Aquí puedes agregar entradas de blog -->
    </section>
    <section id="clients">
        <h2>Clientes</h2>
        <p>Nos enorgullece trabajar con una amplia variedad de clientes. Aquí algunos de ellos:</p>
        <div class="clients">
            <!-- Ejemplo de clientes con logos -->
            <img src="logo1.png" alt="Cliente 1">
            <img src="logo2.png" alt="Cliente 2">
            <img src="logo3.png" alt="Cliente 3">
            <!-- Agrega más logos según sea necesario -->
        </div>
    </section>
    <section id="portfolio">
        <h2>Portafolio</h2>
        <p>Descubre algunos de nuestros proyectos más destacados:</p>
        <!-- Aquí puedes agregar ejemplos de trabajos realizados, imágenes y descripciones -->
    </section>
    <section id="social">
        <h2>Redes Sociales</h2>
        <p>Síguenos en nuestras redes sociales:</p>
        <div class="social-icons">
            <a href="https://www.facebook.com/antares" target="_blank">Facebook</a>
            <a href="https://www.twitter.com/antares" target="_blank">Twitter</a>
            <a href="https://www.linkedin.com/company/antares" target="_blank">LinkedIn</a>
        </div>
    </section>
    <footer>
        <p>&copy; 2024 ANTARES. Todos los derechos reservados.</p>
    </footer>
</body>
</html>
