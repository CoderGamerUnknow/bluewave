<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>BlueWave - Simple Websites for Small Businesses</title>
    <style>
        /* Reset and basic styles */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }

        body {
            line-height: 1.6;
            color: #333;
            background: #f5f9ff;
        }

        a {
            text-decoration: none;
            color: inherit;
        }

        /* Container */
        .container {
            max-width: 1000px;
            margin: auto;
            padding: 0 20px;
        }

        /* Header */
        header {
            background: #0077cc;
            color: #fff;
            padding: 60px 0;
            text-align: center;
            animation: fadeInDown 1s ease-out;
        }

        header h1 {
            font-size: 2.5rem;
            margin-bottom: 20px;
        }

        header p {
            font-size: 1.2rem;
        }

        /* Section titles */
        section h2 {
            text-align: center;
            margin-bottom: 40px;
            color: #0077cc;
            animation: fadeInUp 1s ease-out;
        }

        /* About & Services */
        section {
            padding: 60px 0;
        }

        .about, .services {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 30px;
        }

        .card {
            background: #fff;
            padding: 30px;
            border-radius: 10px;
            box-shadow: 0 8px 20px rgba(0,0,0,0.1);
            flex: 1 1 300px;
            transition: transform 0.3s, box-shadow 0.3s;
            animation: fadeIn 1s ease-out;
        }

        .card:hover {
            transform: translateY(-10px);
            box-shadow: 0 12px 25px rgba(0,0,0,0.15);
        }

        .card h3 {
            margin-bottom: 15px;
            color: #0077cc;
        }

        .card p {
            font-size: 1rem;
            line-height: 1.5;
        }

        /* Contact */
        .contact {
            background: #0077cc;
            color: #fff;
            padding: 60px 20px;
            text-align: center;
            animation: fadeIn 1.2s ease-out;
        }

        .contact a {
            color: #fff;
            background: #005fa3;
            padding: 12px 25px;
            border-radius: 5px;
            display: inline-block;
            margin-top: 20px;
            transition: background 0.3s;
        }

        .contact a:hover {
            background: #004f87;
        }

        /* Animations */
        @keyframes fadeInDown {
            0% { opacity: 0; transform: translateY(-50px);}
            100% { opacity: 1; transform: translateY(0);}
        }

        @keyframes fadeInUp {
            0% { opacity: 0; transform: translateY(50px);}
            100% { opacity: 1; transform: translateY(0);}
        }

        @keyframes fadeIn {
            0% { opacity: 0;}
            100% { opacity: 1;}
        }

        /* Responsive */
        @media(max-width:768px){
            header h1 {
                font-size: 2rem;
            }
        }
    </style>
</head>
<body>

    <!-- Header -->
    <header>
        <h1>BlueWave</h1>
        <p>Helping small businesses and creators get online with clean, easy-to-understand websites. <br>Affordable, fast delivery, and clear communication.</p>
    </header>

    <!-- About Section -->
    <section id="about">
        <div class="container">
            <h2>About</h2>
            <div class="about">
                <div class="card">
                    <h3>Our Mission</h3>
                    <p>We help small businesses and creators establish a professional online presence quickly and affordably.</p>
                </div>
                <div class="card">
                    <h3>Mobile-Friendly</h3>
                    <p>All websites are fully responsive, looking perfect on phones, tablets, and desktops.</p>
                </div>
                <div class="card">
                    <h3>Fast Delivery</h3>
                    <p>Your website is ready in 1–2 days, so you can focus on growing your business.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Services Section -->
    <section id="services">
        <div class="container">
            <h2>Services</h2>
            <div class="services">
                <div class="card">
                    <h3>Simple 1‑Page Website</h3>
                    <p>Starting at ₦1,000</p>
                    <p>Perfect for small businesses, creators, and anyone looking to get online quickly.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section class="contact" id="contact">
        <div class="container">
            <h2>Contact</h2>
            <p>Want a simple website for your business?</p>
            <a href="mailto:your@email.com">Email me at your@email.com</a>
        </div>
    </section>

</body>
</html>
