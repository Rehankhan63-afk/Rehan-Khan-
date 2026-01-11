<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>RK Drilling Company | Premier Drilling & Blasting Services</title>
    <style>
        /* --- General Styles --- */
        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            color: #333;
            line-height: 1.6;
        }
        
        /* --- Color Palette (Luxury/Industrial) --- */
        :root {
            --primary-color: #0c1c2e; /* Dark Navy */
            --accent-color: #d4af37; /* Gold */
            --text-light: #ffffff;
            --text-dark: #333333;
        }

        /* --- Header --- */
        header {
            background-color: var(--primary-color);
            color: var(--text-light);
            padding: 20px 0;
            position: sticky;
            top: 0;
            z-index: 1000;
            border-bottom: 3px solid var(--accent-color);
            box-shadow: 0 2px 10px rgba(0,0,0,0.3);
        }

        .container {
            width: 85%;
            margin: auto;
            overflow: hidden;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }

        .logo {
            font-size: 28px;
            font-weight: bold;
            text-transform: uppercase;
            color: var(--accent-color);
            letter-spacing: 2px;
        }

        nav ul {
            padding: 0;
            margin: 0;
            list-style: none;
            display: flex;
        }

        nav ul li {
            margin-left: 20px;
        }

        nav a {
            color: var(--text-light);
            text-decoration: none;
            font-size: 16px;
            font-weight: 500;
            transition: color 0.3s;
        }

        nav a:hover {
            color: var(--accent-color);
        }

        /* --- Hero Section --- */
        #hero {
            background: linear-gradient(rgba(12, 28, 46, 0.8), rgba(12, 28, 46, 0.8)), url('https://images.unsplash.com/photo-1578575437130-527eed3abbec?ixlib=rb-1.2.1&auto=format&fit=crop&w=1950&q=80'); /* Placeholder image representing a mine */
            background-size: cover;
            background-position: center;
            height: 80vh;
            color: var(--text-light);
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            text-align: center;
            padding: 0 20px;
        }

        #hero h1 {
            font-size: 50px;
            margin-bottom: 10px;
            text-transform: uppercase;
        }

        #hero p {
            font-size: 20px;
            margin-bottom: 30px;
            max-width: 600px;
        }

        .btn {
            display: inline-block;
            background: var(--accent-color);
            color: var(--primary-color);
            padding: 12px 30px;
            border: none;
            cursor: pointer;
            font-size: 18px;
            font-weight: bold;
            text-decoration: none;
            border-radius: 5px;
            transition: background 0.3s;
        }

        .btn:hover {
            background: #b5952f;
        }

        /* --- About Section --- */
        #about {
            padding: 60px 0;
            background-color: #fff;
            text-align: center;
        }

        .section-title {
            font-size: 35px;
            color: var(--primary-color);
            margin-bottom: 10px;
            text-transform: uppercase;
        }

        .line {
            width: 100px;
            height: 4px;
            background: var(--accent-color);
            margin: 0 auto 40px auto;
        }

        /* --- Services Section --- */
        #services {
            padding: 60px 0;
            background-color: #e9ecef;
        }

        .services-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 20px;
            width: 85%;
            margin: auto;
        }

        .service-card {
            background: #fff;
            padding: 30px;
            border-bottom: 4px solid var(--accent-color);
            box-shadow: 0 4px 8px rgba(0,0,0,0.1);
            transition: transform 0.3s;
        }

        .service-card:hover {
            transform: translateY(-5px);
        }

        .service-card h3 {
            color: var(--primary-color);
            margin-top: 0;
        }

        /* --- Contact/CTA Section --- */
        #contact {
            background-color: var(--primary-color);
            color: var(--text-light);
            padding: 50px 0;
            text-align: center;
        }

        .contact-info {
            font-size: 24px;
            margin: 20px 0;
        }

        .phone-number {
            color: var(--accent-color);
            font-weight: bold;
            font-size: 32px;
            text-decoration: none;
        }

        /* --- Footer --- */
        footer {
            background-color: #08121e;
            color: #ccc;
            text-align: center;
            padding: 20px 0;
            border-top: 1px solid #333;
        }

        /* --- Mobile Responsive --- */
        @media (max-width: 768px) {
            .container {
                flex-direction: column;
                text-align: center;
            }
            nav ul {
                margin-top: 20px;
            }
            #hero h1 {
                font-size: 36px;
            }
        }
    </style>
</head>
<body>

    <header>
        <div class="container">
            <div class="logo">RK Drilling Company</div>
            <nav>
                <ul>
                    <li><a href="#hero">Home</a></li>
                    <li><a href="#about">About</a></li>
                    <li><a href="#services">Services</a></li>
                    <li><a href="#contact">Contact</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <section id="hero">
        <h1>Unearthing Excellence</h1>
        <p>Premium Drilling, Blasting, and Excavation Services. Equipped with modern Tata Hitachi & Shakti Machinery.</p>
        <a href="tel:8459954248" class="btn">Call Now: 84599 54248</a>
    </section>

    <section id="about">
        <div class="container">
            <h2 class="section-title">About Our Company</h2>
            <div class="line"></div>
            <p style="max-width: 800px; margin: auto; font-size: 18px;">
                RK Drilling Company is a leader in heavy excavation and mining solutions. We specialize in precision rock drilling and controlled blasting. Our fleet includes heavy-duty <strong>Tata Hitachi excavators</strong> and high-performance <strong>Shakti drilling rigs</strong>, ensuring every project is completed with speed, safety, and efficiency.
            </p>
        </div>
    </section>

    <section id="services">
        <div class="container">
            <h2 class="section-title" style="text-align: center;">Our Services</h2>
            <div class="line"></div>
            <div class="services-grid">
                <div class="service-card">
                    <h3>🛠️ Heavy Drilling</h3>
                    <p>Using advanced Shakti 150 drilling rigs, we provide deep hole drilling for quarries, mines, and construction sites with high precision.</p>
                </div>
                <div class="service-card">
                    <h3>🧨 Controlled Blasting</h3>
                    <p>Expert blasting services designed to maximize rock fragmentation while maintaining the highest safety standards on-site.</p>
                </div>
                <div class="service-card">
                    <h3>🚜 Excavation & Loading</h3>
                    <p>Rapid removal and loading of materials using our powerful Tata Hitachi excavators. We handle the heavy lifting for you.</p>
                </div>
            </div>
        </div>
    </section>

    <section id="contact">
        <div class="container">
            <h2>Ready to Start Your Project?</h2>
            <p>Contact RK Drilling Company today for a quote.</p>
            
            <div class="contact-info">
                Call Us Directly:<br>
                <a href="tel:8459954248" class="phone-number">📞 +91 84599 54248</a>
            </div>
            
            <p>Available for projects across the region.</p>
        </div>
    </section>

    <footer>
        <p>&copy; 2024 RK Drilling Company. All Rights Reserved.</p>
    </footer>

</body>
</html>
