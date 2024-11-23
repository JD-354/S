<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tu Zapatería - Las Mejores Marcas</title>
    <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css" rel="stylesheet">
    <style>
        :root {
            --primary-color: #2c3e50;
            --secondary-color: #e74c3c;
            --text-color: #333;
            --light-bg: #f9f9f9;
        }

        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Arial', sans-serif;
            line-height: 1.6;
            color: var(--text-color);
        }

        .header {
            background-color: var(--primary-color);
            color: white;
            padding: 1rem;
            position: fixed;
            width: 100%;
            top: 0;
            z-index: 1000;
        }

        .nav-container {
            max-width: 1200px;
            margin: 0 auto;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }

        .logo {
            font-size: 1.5rem;
            font-weight: bold;
        }

        .nav-menu {
            display: flex;
            gap: 2rem;
        }

        .nav-menu a {
            color: white;
            text-decoration: none;
            transition: color 0.3s;
        }

        .nav-menu a:hover {
            color: var(--secondary-color);
        }

        .hero {
            background-image: url('/api/placeholder/1200/600');
            background-size: cover;
            background-position: center;
            height: 60vh;
            display: flex;
            align-items: center;
            justify-content: center;
            text-align: center;
            color: white;
            margin-top: 60px;
            position: relative;
        }

        .hero::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            right: 0;
            bottom: 0;
            background: rgba(0, 0, 0, 0.5);
        }

        .hero-content {
            position: relative;
            z-index: 1;
        }

        .hero h1 {
            font-size: 3rem;
            margin-bottom: 1rem;
        }

        .cta-button {
            display: inline-block;
            padding: 1rem 2rem;
            background-color: var(--secondary-color);
            color: white;
            text-decoration: none;
            border-radius: 5px;
            transition: background-color 0.3s;
        }

        .cta-button:hover {
            background-color: #c0392b;
        }

        .main-content {
            max-width: 1200px;
            margin: 2rem auto;
            padding: 0 1rem;
        }

        .section {
            margin: 4rem 0;
            padding: 2rem;
            background-color: var(--light-bg);
            border-radius: 10px;
        }

        .section h2 {
            color: var(--primary-color);
            margin-bottom: 1.5rem;
        }

        .services-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 2rem;
            margin-top: 2rem;
        }

        .service-card {
            padding: 1.5rem;
            background: white;
            border-radius: 8px;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
            text-align: center;
        }

        .service-card i {
            font-size: 2.5rem;
            color: var(--secondary-color);
            margin-bottom: 1rem;
        }

        .features {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 2rem;
        }

        .feature {
            padding: 1.5rem;
            background: white;
            border-radius: 8px;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
        }

        .footer {
            background-color: var(--primary-color);
            color: white;
            padding: 2rem 0;
            margin-top: 4rem;
        }

        .footer-content {
            max-width: 1200px;
            margin: 0 auto;
            padding: 0 1rem;
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 2rem;
        }

        .footer-section h3 {
            margin-bottom: 1rem;
        }

        .footer-section ul {
            list-style: none;
        }

        .footer-section ul li {
            margin-bottom: 0.5rem;
        }

        .footer-section a {
            color: white;
            text-decoration: none;
        }

        .social-links {
            display: flex;
            gap: 1rem;
            margin-top: 1rem;
        }

        .social-links a {
            font-size: 1.5rem;
        }

        @media (max-width: 768px) {
            .nav-menu {
                display: none;
            }

            .hero h1 {
                font-size: 2rem;
            }
        }
    </style>
</head>
<body>
    <header class="header">
        <nav class="nav-container">
            <div class="logo">Zapatería J.P.A.N</div>
            <div class="nav-menu">
                <a href="https://jd-354.github.io/z/">Inicio</a>
                <a href="#sobre-nosotros">Sobre Nosotros</a>
                <a href="#marcas">Marcas</a>
                <a href="#contacto">Contacto</a>
            </div>
        </nav>
    </header>

    <section class="hero">
        <div class="hero-content">
            <h1>Las Mejores Marcas de Calzado</h1>
            <p>Encuentra el par perfecto para cada ocasión</p>
            <a href="https://cdn.flightclub.com/750/TEMPLATE/012451/1.jpg" " class="cta-button">Ver Catálogo</a>
        </div>
    </section>

    <main class="main-content">
        <section id="sobre-nosotros" class="section">
            <h2>Sobre Nosotros</h2>
            <p>En Tu Zapatería, nos apasiona ayudarte a encontrar el calzado perfecto para cada paso de tu vida. Desde 2024, nos hemos consolidado como el destino preferido para los amantes del buen calzado, ofreciendo una cuidadosa selección de las mejores marcas nacionales e internacionales.</p>
            
            <div class="features">
                <div class="feature">
                    <h3>Nuestra Misión</h3>
                    <p>Nos dedicamos a proporcionar a nuestros clientes una experiencia de compra excepcional, combinando calidad, estilo y comodidad en cada par de zapatos.</p>
                </div>
                <div class="feature">
                    <h3>Calidad Garantizada</h3>
                    <p>Cada par de zapatos en nuestra tienda pasa por rigurosos controles de calidad. Trabajamos únicamente con proveedores certificados.</p>
                </div>
                <div class="feature">
                    <h3>Experiencia</h3>
                    <p>Nuestro equipo de expertos está capacitado para brindarte asesoramiento personalizado en la elección de tu calzado ideal.</p>
                </div>
            </div>
        </section>

        <section id="servicios" class="section">
            <h2>Nuestros Servicios</h2>
            <div class="services-grid">
                <div class="service-card">
                    <i class="fas fa-shoe-prints"></i>
                    <h3>Asesoramiento Profesional</h3>
                    <p>Expertos en calzado a tu disposición</p>
                </div>
                <div class="service-card">
                    <i class="fas fa-tape"></i>
                    <h3>Medición Experta</h3>
                    <p>Encuentra tu talla perfecta</p>
                </div>
                <div class="service-card">
                    <i class="fas fa-tools"></i>
                    <h3>Mantenimiento</h3>
                    <p>Servicios de cuidado del calzado</p>
                </div>
                <div class="service-card">
                    <i class="fas fa-box"></i>
                    <h3>Pedidos Especiales</h3>
                    <p>Modelos específicos bajo pedido</p>
                </div>
            </div>
        </section>
    </main>

    <footer class="footer">
        <div class="footer-content">
            <div class="footer-section">
                <h3>Contacto</h3>
                <p>Email: info@tuzapateria.com</p>
                <p>Teléfono: (123) 456-7890</p>
                <p>Dirección: Tu Dirección #123</p>
            </div>
            <div class="footer-section">
                <h3>Enlaces Rápidos</h3>
                <ul>
                    <li><a href="#inicio">Inicio</a></li>
                    <li><a href="#sobre-nosotros">Sobre Nosotros</a></li>
                    <li><a href="#marcas">Marcas</a></li>
                    <li><a href="#contacto">Contacto</a></li>
                </ul>
            </div>
            <div class="footer-section">
                <h3>Síguenos</h3>
                <div class="social-links">
                    <a href="#"><i class="fab fa-facebook"></i></a>
                    <a href="#"><i class="fab fa-instagram"></i></a>
                    <a href="#"><i class="fab fa-twitter"></i></a>
                </div>
            </div>
        </div>
    </footer>
    </body>
    </html>
