<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Small Business</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            line-height: 1.6;
        }
        header {
            background: #4CAF50;
            color: white;
            padding: 1rem 0;
            text-align: center;
        }
        nav {
            display: flex;
            justify-content: center;
            background: #333;
        }
        nav a {
            color: white;
            padding: 0.75rem 1.5rem;
            text-decoration: none;
        }
        nav a:hover {
            background: #575757;
        }
        .container {
            padding: 1rem 2rem;
        }
        .services, .contact {
            display: flex;
            flex-wrap: wrap;
            gap: 1rem;
        }
        .card {
            flex: 1 1 calc(33.333% - 1rem);
            background: #f4f4f4;
            padding: 1rem;
            border: 1px solid #ddd;
            border-radius: 5px;
            text-align: center;
        }
        footer {
            background: #333;
            color: white;
            text-align: center;
            padding: 1rem 0;
            margin-top: 1rem;
        }
        @media (max-width: 768px) {
            .card {
                flex: 1 1 calc(50% - 1rem);
            }
        }
        @media (max-width: 480px) {
            .card {
                flex: 1 1 100%;
            }
        }
    </style>
</head>
<body>
    <header>
        <h1>Welcome to My Small Business</h1>
        <p>Your trusted partner for quality services</p>
    </header>
    <nav>
        <a href="#services">Services</a>
        <a href="#about">About Us</a>
        <a href="#contact">Contact</a>
    </nav>
    <div class="container">
        <section id="services">
            <h2>Our Services</h2>
            <div class="services">
                <div class="card">
                    <h3>Service 1</h3>
                    <p>Describe your first service here.</p>
                </div>
                <div class="card">
                    <h3>Service 2</h3>
                    <p>Describe your second service here.</p>
                </div>
                <div class="card">
                    <h3>Service 3</h3>
                    <p>Describe your third service here.</p>
                </div>
            </div>
        </section>

        <section id="about">
            <h2>About Us</h2>
            <p>Write a brief description of your business, your mission, and what makes you unique.</p>
        </section>

        <section id="contact">
            <h2>Contact Us</h2>
            <div class="contact">
                <div>
                    <h3>Email</h3>
                    <p>email@yourbusiness.com</p>
                </div>
                <div>
                    <h3>Phone</h3>
                    <p>+123-456-7890</p>
                </div>
                <div>
                    <h3>Address</h3>
                    <p>123 Business Street, City, Country</p>
                </div>
            </div>
        </section>
    </div>
    <footer>
        <p>&copy; 2025 My Small Business. All Rights Reserved.</p>
    </footer>
</body>
</html>
