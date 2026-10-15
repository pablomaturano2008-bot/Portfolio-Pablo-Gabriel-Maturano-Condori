# Portfolio-Pablo-Gabriel-Maturano-Condori
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>Mi Portfolio Digital</title>

    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: Arial, sans-serif;
            background-color: #0f172a;
            color: white;
            line-height: 1.6;
        }

        header {
            background-color: #020617;
            padding: 25px;
            text-align: center;
        }

        header h1 {
            color: #38bdf8;
            font-size: 32px;
        }

        nav {
            margin-top: 15px;
        }

        nav a {
            color: white;
            text-decoration: none;
            margin: 0 12px;
        }

        nav a:hover {
            color: #38bdf8;
        }

        main {
            max-width: 900px;
            margin: auto;
            padding: 30px 20px;
        }

        section {
            background-color: #1e293b;
            padding: 25px;
            margin-bottom: 25px;
            border-radius: 12px;
        }

        h2 {
            color: #38bdf8;
            margin-bottom: 15px;
        }

        .presentacion {
            text-align: center;
            padding: 40px 25px;
        }

        .foto {
            width: 150px;
            height: 150px;
            border-radius: 50%;
            object-fit: cover;
            border: 4px solid #38bdf8;
            margin-bottom: 15px;
        }

        .boton {
            display: inline-block;
            background-color: #0284c7;
            color: white;
            padding: 10px 18px;
            margin-top: 15px;
            border-radius: 6px;
            text-decoration: none;
        }

        .boton:hover {
            background-color: #0369a1;
        }

        ul {
            padding-left: 25px;
        }

        footer {
            text-align: center;
            padding: 20px;
            background-color: #020617;
            color: #94a3b8;
        }
    </style>
</head>

<body>

    <header>
        <h1>Mi Portfolio Digital</h1>

        <nav>
            <a href="#sobre-mi">Sobre mí</a>
            <a href="#objetivos">Objetivos</a>
            <a href="#proyectos">Proyectos</a>
            <a href="#contacto">Enlaces</a>
        </nav>
    </header>

    <main>

        <section class="presentacion" id="sobre-mi">

            <img src="foto.jpg" alt="Mi fotografía" class="foto">

            <h2>¡Hola! Soy Gabriel</h2>

            <p>
                Soy estudiante de primero de FP de Grado Medio de Informática.
                Me interesa la tecnología, los ordenadores, las redes y los
                sistemas operativos.
            </p>

        </section>

        <section id="objetivos">

            <h2>🎯 Mi objetivo profesional</h2>

            <p>
                Mi objetivo es aprender más sobre informática, mejorar mis
                conocimientos sobre redes y sistemas operativos y adquirir
                experiencia para trabajar en el sector tecnológico.
            </p>

        </section>

        <section id="proyectos">

            <h2>💻 Mis proyectos</h2>

            <p>
                En este apartado iré añadiendo los trabajos y actividades
                que realice durante el curso.
            </p>

            <ul>
                <li>Prácticas de instalación de sistemas operativos.</li>
                <li>Configuración de redes y direccionamiento IP.</li>
                <li>Ejercicios de subnetting IPv4.</li>
                <li>Prácticas de máquinas virtuales.</li>
            </ul>

        </section>

        <section id="contacto">

            <h2>🔗 Enlaces de interés</h2>

            <p>Puedes consultar mis perfiles y proyectos aquí:</p>

            <a class="boton"
               href="https://github.com/"
               target="_blank"
               rel="noopener noreferrer">
                Mi GitHub
            </a>

            <br>

            <a class="boton"
               href="https://www.linkedin.com/"
               target="_blank"
               rel="noopener noreferrer">
                LinkedIn
            </a>

        </section>

    </main>

    <footer>
        <p>© 2026 Gabriel | Portfolio Digital</p>
        <p>Estudiante de Informática</p>
    </footer>

</body>
</html>
