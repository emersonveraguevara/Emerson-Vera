# Emerson-Vera
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Emerson Vera Guevara</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            color: #333;
        }
        .container {
            width: 80%;
            margin: 0 auto;
        }
        header {
            background-color: #333;
            color: #fff;
            padding: 1rem 0;
            text-align: center;
        }
        nav {
            margin: 1rem 0;
            text-align: center;
        }
        nav a {
            margin: 0 1rem;
            color: #333;
            text-decoration: none;
            font-weight: bold;
        }
        section {
            margin: 2rem 0;
        }
        footer {
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 1rem 0;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
        h2 {
            color: #555;
        }
        .portfolio img {
            width: 100%;
            height: auto;
            display: block;
            margin: 1rem 0;
        }
        .contact-form {
            display: flex;
            flex-direction: column;
        }
        .contact-form input,
        .contact-form textarea {
            margin: 0.5rem 0;
            padding: 0.5rem;
            font-size: 1rem;
        }
        .contact-form button {
            padding: 0.5rem;
            font-size: 1rem;
            background-color: #333;
            color: #fff;
            border: none;
        }
    </style>
</head>
<body>
    <header>
        <h1>Emerson Vera Guevara</h1>
        <p>Artista Visual y Educador Artístico</p>
    </header>

    <nav>
        <a href="#about">Sobre mí</a>
        <a href="#portfolio">Portafolio</a>
        <a href="#contact">Contacto</a>
    </nav>

    <div class="container">
        <section id="about">
            <h2>Sobre mí</h2>
            <p>
                Emerson Jhair Vera Guevara (Chongoyape, Perú 2001) Artista Visual y Educador Artístico
                Integrante de Compañía MOON REAL.
            </p>
            <p>
                Identidad, memorias y revaloración cultural son temas principales para la concepción de mi obra. 
                Es de mi consideración la identidad como punto de partida para revalorar nuestra cultura, acompañado 
                de la educación, valores y pensamientos, los que forman nuestra persona, como individuos interesados 
                en el cuidado de los vestigios de las culturas precolombinas en sus distintas formas de expresión como: 
                arquitectura, textiles, leyendas, mitos, etc. Mi obra es el resultado de aquellas formas, iconografías, 
                espacios, diseños de las distintas culturas y parte de la historia del Perú, con un toque sutil 
                contemporáneo en la distribución de los elementos que forman parte de cada pieza artística.
            </p>
        </section>

        <section id="portfolio">
            <h2>Portafolio</h2>
            <div class="portfolio">
                <img src="tu-imagen-1.jpg" alt="Obra 1">
                <img src="tu-imagen-2.jpg" alt="Obra 2">
                <img src="tu-imagen-3.jpg" alt="Obra 3">
            </div>
        </section>

        <section id="contact">
            <h2>Contacto</h2>
            <form class="contact-form">
                <input type="text" name="name" placeholder="Tu nombre" required>
                <input type="email" name="email" placeholder="Tu email" required>
                <textarea name="message" rows="5" placeholder="Tu mensaje" required></textarea>
                <button type="submit">Enviar</button>
            </form>
        </section>
    </div>

    <footer>
        <p>&copy; 2024 Emerson Vera Guevara</p>
    </footer>
</body>
</html>
