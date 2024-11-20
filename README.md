<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Rizza Technologies</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/css/bootstrap.min.css" rel="stylesheet">
    <script src="https://cdn.tailwindcss.com"></script>
    <style>
        
        body {
            background-color: #121212; 
            color: #e0e0e0; 
        }

        a {
            text-decoration: none;
            color: #38bdf8; 
        }

        a:hover {
            color: #9333ea; 
        }

        .navbar {
            background-color: #1f1f1f; 
        }

        
        .navbar-brand {
            font-size: 2rem;
            font-weight: 800;
            letter-spacing: 0.1em;
            background: linear-gradient(90deg, #9333ea, #38bdf8);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            text-transform: uppercase;
        }

        .navbar-brand:hover {
            text-shadow: 0px 0px 10px #9333ea;
            transition: text-shadow 0.3s ease-in-out;
        }

        .hero-bg {
            background: linear-gradient(90deg, #0f172a, #1e293b); 
        }

        .hero-title {
            font-size: 4rem;
            font-weight: 700;
            letter-spacing: 0.05em;
            text-transform: uppercase;
        }

        .btn-custom {
            background-color: #9333ea;
            color: white;
            border-radius: 50px;
            padding: 0.75rem 1.5rem;
        }

        .btn-custom:hover {
            background-color: #38bdf8;
            color: #121212;
        }

        .card {
            background-color: #1f1f1f; 
            color: #e0e0e0;
            border: none;
            border-radius: 10px;
        }

        .card:hover {
            box-shadow: 0 8px 20px rgba(0, 0, 0, 0.5);
            transform: translateY(-10px);
            transition: all 0.3s ease-in-out;
        }

        footer {
            background-color: #0f172a; 
            color: #e0e0e0;
        }

        .footer-links a {
            margin: 0 10px;
            color: #38bdf8;
        }

        .footer-links a:hover {
            color: #9333ea;
        }

        .carousel-indicators [data-bs-target] {
            background-color: #9333ea;
        }
    </style>
</head>
<body>

    <header>
        <nav class="navbar navbar-expand-lg navbar-dark">
            <div class="container">
                <a class="navbar-brand" href="#">Rizza Technologies</a>
                <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
                    <span class="navbar-toggler-icon"></span>
                </button>
                <div class="collapse navbar-collapse" id="navbarNav">
                    <ul class="navbar-nav ms-auto">
                        <li class="nav-item"><a class="nav-link" href="#features">Features</a></li>
                        <li class="nav-item"><a class="nav-link" href="#testimonials">Testimonials</a></li>
                        <li class="nav-item"><a class="nav-link" href="#contact">Contact</a></li>
                    </ul>
                </div>
            </div>
        </nav>
    </header>

    <section class="hero-bg text-white text-center py-20">
        <h1 class="hero-title">Innovate with Rizza</h1>
        <p class="mt-4">Empowering your business with cutting-edge technology solutions.</p>
        <button class="mt-6 btn-custom">Explore Now</button>
    </section>

    <section class="container my-5" id="features">
        <h2 class="text-center text-purple-500 mb-5">Our Features</h2>
        <div class="row">
            <div class="col-md-4 mb-4">
                <div class="card text-center p-4">
                    <h5>Advanced Analytics</h5>
                    <p>Leverage powerful data-driven insights to grow your business.</p>
                </div>
            </div>
            <div class="col-md-4 mb-4">
                <div class="card text-center p-4">
                    <h5>Cloud Solutions</h5>
                    <p>Secure and scalable cloud services for modern businesses.</p>
                </div>
            </div>
            <div class="col-md-4 mb-4">
                <div class="card text-center p-4">
                    <h5>24/7 Support</h5>
                    <p>Reliable customer support to ensure your success.</p>
                </div>
            </div>
        </div>
    </section>

    <section class="bg-dark py-5" id="testimonials">
        <div class="container">
            <h2 class="text-center text-purple-500 mb-4">Testimonials</h2>
            <div id="testimonialCarousel" class="carousel slide" data-bs-ride="carousel">
                <div class="carousel-indicators">
                    <button type="button" data-bs-target="#testimonialCarousel" data-bs-slide-to="0" class="active"></button>
                    <button type="button" data-bs-target="#testimonialCarousel" data-bs-slide-to="1"></button>
                </div>
                <div class="carousel-inner">
                    <div class="carousel-item active">
                        <p class="text-center">"Rizza Technologies transformed our workflow. Incredible service!"</p>
                    </div>
                    <div class="carousel-item">
                        <p class="text-center">"The best tech solutions we've ever experienced. Highly recommend!"</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <footer class="py-4">
        <div class="container text-center">
            <p>&copy; 2024 Rizza Technologies. All rights reserved.</p>
            <div class="footer-links">
                <a href="#">Facebook</a>
                <a href="#">Twitter</a>
                <a href="#">LinkedIn</a>
            </div>
        </div>
    </footer>

    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>

