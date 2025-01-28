<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <title>Perfil Profesional - Desarrollador de Aplicaciones Multiplataforma</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f9;
        }
        header {
            background-color: #282c34;
            color: white;
            padding: 20px;
            text-align: center;
        }
        h1 {
            margin: 0;
        }
        nav {
            margin-top: 10px;
        }
        nav a {
            color: #61dafb;
            text-decoration: none;
            margin: 0 10px;
        }
        section {
            padding: 20px;
            max-width: 1000px;
            margin: auto;
        }
        .skills, .projects {
            display: flex;
            justify-content: space-between;
            flex-wrap: wrap;
        }
        .skill, .project {
            background-color: #fff;
            border: 1px solid #ddd;
            border-radius: 10px;
            padding: 15px;
            width: 30%;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            margin: 10px 0;
        }
        footer {
            text-align: center;
            padding: 10px;
            background-color: #282c34;
            color: white;
        }
    </style>
</head>
<body>

    <header>
        <h1>Juan Pérez</h1>
        <p>Desarrollador de Aplicaciones Multiplataforma y Programador</p>
        <nav>
            <a href="https://www.linkedin.com" target="_blank">LinkedIn</a>
            <a href="https://www.github.com" target="_blank">GitHub</a>
            <a href="mailto:juanperez@email.com">Contacto</a>
        </nav>
    </header>

    <section>
        <h2>Presentación</h2>
        <p>Soy un desarrollador de aplicaciones multiplataforma con más de 5 años de experiencia creando soluciones móviles y web escalables. Me especializo en el desarrollo con tecnologías como JavaScript, React Native, Flutter, y también poseo experiencia en backend con Node.js y bases de datos como MongoDB y MySQL. Mi enfoque está en la creación de aplicaciones eficientes, intuitivas y con una experiencia de usuario excelente.</p>
    </section>

    <section>
        <h2>Habilidades</h2>
        <div class="skills">
            <div class="skill">
                <h3>Lenguajes de Programación</h3>
                <p>JavaScript, TypeScript, Python, Dart, Java</p>
            </div>
            <div class="skill">
                <h3>Frameworks y Tecnologías</h3>
                <p>React Native, Flutter, Node.js, Express, Redux</p>
            </div>
            <div class="skill">
                <h3>Bases de Datos</h3>
                <p>MongoDB, MySQL, PostgreSQL</p>
            </div>
        </div>
    </section>

    <section>
        <h2>Proyectos Destacados</h2>
        <div class="projects">
            <div class="project">
                <h3>App de Gestión de Tareas</h3>
                <p>Aplicación móvil multiplataforma desarrollada en Flutter para gestionar tareas y proyectos. Incluye notificaciones, autenticación y sincronización en la nube.</p>
            </div>
            <div class="project">
                <h3>Sistema de Ventas Online</h3>
                <p>Desarrollé una solución de e-commerce utilizando Node.js y React, con carrito de compras, pasarela de pagos y panel de administración.</p>
            </div>
            <div class="project">
                <h3>Aplicación de Seguimiento de Hábitos</h3>
                <p>App nativa en React Native para monitorear hábitos diarios con integración de gráficos y estadísticas en tiempo real.</p>
            </div>
        </div>
    </section>

    <footer>
        <p>© 2025 Juan Pérez - Desarrollador de Aplicaciones Multiplataforma</p>
    </footer>

</body>
</html>
