<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>INFI - Instituto Nacional de Formación Integral</title>
    <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@400;600;700&display=swap" rel="stylesheet">
    <style>
        /* Estilos Generales */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Montserrat', sans-serif;
        }

        body {
            background-color: #ffffff;
            color: #2c3e50;
        }

        /* Header */
        header {
            position: fixed;
            top: 0;
            width: 100%;
            background-color: #2c3e50;
            padding: 1rem 2rem;
            display: flex;
            justify-content: space-between;
            align-items: center;
            z-index: 1000;
            box-shadow: 0 2px 10px rgba(0,0,0,0.1);
        }

        .logo-container {
            display: flex;
            align-items: center;
        }

        .logo {
            width: 60px;
            margin-right: 1rem;
        }

        .nav-links {
            display: flex;
            gap: 2rem;
        }

        .nav-links a {
            color: #ffffff;
            text-decoration: none;
            font-weight: 600;
            transition: color 0.3s;
        }

        .nav-links a:hover {
            color: #d4af37;
        }

        /* Hero Section */
        .hero {
            height: 100vh;
            background: linear-gradient(rgba(0,0,0,0.5), rgba(0,0,0,0.5)), 
                        url('hero-bg.jpg') center/cover;
            display: flex;
            align-items: center;
            justify-content: center;
            text-align: center;
            color: white;
            margin-top: 80px; /* Para compensar el header fijo */
        }

        .hero-content {
            max-width: 800px;
            padding: 2rem;
        }

        .hero h1 {
            font-size: 3rem;
            margin-bottom: 1.5rem;
        }

        .cta-button {
            background-color: #d4af37;
            color: #2c3e50;
            padding: 1rem 2rem;
            border: none;
            border-radius: 5px;
            font-size: 1.1rem;
            cursor: pointer;
            transition: transform 0.3s;
        }

        /* Sección Conocé más */
        .about-section {
            padding: 4rem 2rem;
            text-align: center;
            background-color: #f8f9fa;
        }

        .about-content {
            max-width: 800px;
            margin: 0 auto;
        }

        /* Sección Cursos */
        .courses-section {
            padding: 4rem 2rem;
        }

        .courses-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 2rem;
            margin-top: 2rem;
        }

        .course-card {
            background: white;
            border-radius: 10px;
            padding: 1.5rem;
            box-shadow: 0 3px 10px rgba(0,0,0,0.1);
            transition: transform 0.3s;
        }

        .course-card:hover {
            transform: translateY(-5px);
        }

        /* Footer */
        footer {
            background-color: #2c3e50;
            color: white;
            padding: 3rem 2rem;
            margin-top: 4rem;
        }

        .footer-content {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 2rem;
            max-width: 1200px;
            margin: 0 auto;
        }

        .social-icons {
            display: flex;
            gap: 1rem;
            margin-top: 1rem;
        }

        .social-icons img {
            width: 30px;
            filter: invert(1);
        }
    </style>
</head>
<body>
    <header>
        <div class="logo-container">
            <img src="INFI.webp" alt="Logo INFI" class="logo">
            <h1>INFI</h1>
        </div>
        <nav class="nav-links">
            <a href="index.html">Inicio</a>
            <a href="nosotros.html">Conocé más</a>
            <a href="cursos.html">Cursos</a>
            <a href="contacto.html">Contacto</a>
            <a href="certificados.html">Certificados</a>
        </nav>
    </header>
    <section class="hero">
        <div class="hero-overlay">
            <h1>Bienvenidos al Instituto Nacional de Formación Integral</h1>
        </div>
        <video autoplay loop muted playsinline>
            <source src="INFI VIDEO.mp4" type="video/mp4">
        </video>
        <a href="cursos.html" class="cta-button">Conocé nuestros cursos</a>
    </section>
    
    <style>
        .hero {
            position: relative;
            display: flex;
            align-items: center;
            justify-content: center;
            text-align: center;
            height: 100vh;
        }
    
        .hero-overlay {
            position: absolute;
            top: 20%;
            left: 50%;
            transform: translate(-50%, -50%);
            color: white;
            font-size: 2rem;
            font-weight: bold;
            z-index: 2;
        }
    
        .hero video {
            width: 100%;
            height: 100%;
            object-fit: cover;
            position: absolute;
            top: 0;
            left: 0;
            z-index: 1;
        }
    
        .cta-button {
            position: absolute;
            bottom: 10%;
            left: 50%;
            transform: translateX(-50%);
            z-index: 2;
        }
    </style>
    

    
    <section class="about-section" id="nosotros">
        <div class="about-content">
            <h2>Conocé más de nosotros</h2>
            <p>El INFI se compromete con la excelencia educativa, ofreciendo formación de calidad...</p>
            
        </div>
    </section>
        <div class="courses-grid">
        </div>
    </div>
    </section>

    <footer>
        <div class="footer-content">
            <div>
                <h3>Contacto</h3>
                <p>Tel: 0800-123-4567</p>
                <p>Email: info@infi.edu.ar</p>
            </div>
            <div>
                <h3>Redes Sociales</h3>
                <div class="social-icons">
                    <img src="Facebook.pnh.jfif.png" alt="Facebook">
                    <img src="instagram-icon.png" alt="Instagram">
                    <img src="linkedin-icon.png" alt="LinkedIn">
                </div>
            </div>
            <div>
                <h3>Políticas</h3>
                <!-- Se redirige a un HTML propio para Políticas y Condiciones -->
                <a href="politicas.html">Términos y condiciones</a>
                <a href="politicas.html">Política de privacidad</a>
            </div>
        </div>
    </footer>
</body>
</html>
