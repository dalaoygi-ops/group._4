
         <style>
        :root {
            --primary: #8b263e;
            --secondary: #2c2c2c;
            --accent: #d4af37;
            --bg-light: #f9f8f6;
            --white: #ffffff;
        }

        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }

        body {
            background-color: var(--bg-light);
            color: var(--secondary);
            line-height: 1.6;
        }

        /* Hero Section */
        header {
            height: 100vh;
            background: linear-gradient(rgba(0, 0, 0, 0.4), rgba(0, 0, 0, 0.4)), url('Cavitess.jpg') no-repeat center center/cover;
            display: flex;
            flex-direction: column;
            justify-content: space-between;
            color: var(--white);
            text-align: center;
            padding: 2rem;
        }

        nav {
            display: flex;
            justify-content: space-between;
            align-items: center;
            max-width: 1200px;
            width: 100%;
            margin: 0 auto;
        }

        .logo {
            font-size: 1.5rem;
            font-weight: bold;
            letter-spacing: 2px;
            color: var(--white);
        }

        .hero-content {
            max-width: 800px;
            margin: 0 auto;
        }

        .hero-content h1 {
            font-size: 3.5rem;
            margin-bottom: 1rem;
            letter-spacing: 1px;
        }

        .hero-content p {
            font-size: 1.2rem;
            margin-bottom: 2rem;
            font-weight: 300;
        }

        .btn {
            display: inline-block;
            background-color: var(--primary);
            color: var(--white);
            padding: 0.8rem 2rem;
            border-radius: 30px;
            text-decoration: none;
            font-weight: bold;
            transition: background 0.3s ease;
        }

        .btn:hover {
            background-color: #6d1d30;
        }

        /* Container */
        .container {
            max-width: 1100px;
            margin: 0 auto;
            padding: 5rem 2rem;
        }

        /* Highlights Section */
        .section-title {
            text-align: center;
            font-size: 2.5rem;
            margin-bottom: 3rem;
            color: var(--secondary);
            position: relative;
        }

        .section-title::after {
            content: '';
            display: block;
            width: 60px;
            height: 3px;
            background-color: var(--primary);
            margin: 10px auto 0;
        }

        .grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 2rem;
        }

        .card {
            background: var(--white);
            border-radius: 8px;
            overflow: hidden;
            box-shadow: 0 4px 15px rgba(0,0,0,0.05);
            transition: transform 0.3s ease;
        }

        .card:hover {
            transform: translateY(-5px);
        }

        .card img {
            width: 100%;
            height: 220px;
            object-fit: cover;
        }

        .card-body {
            padding: 1.5rem;
        }

        .card-body h3 {
            margin-bottom: 0.5rem;
            color: var(--primary);
        }

        /* Call to Action Banner */
        .cta-banner {
            background-color: var(--primary);
            color: var(--white);
            text-align: center;
            padding: 4rem 2rem;
        }

        .cta-banner h2 {
            font-size: 2.5rem;
            margin-bottom: 1rem;
        }

        .cta-banner p {
            margin-bottom: 2rem;
            font-size: 1.1rem;
        }

        .cta-banner .btn {
            background-color: var(--white);
            color: var(--primary);
        }

        .cta-banner .btn:hover {
            background-color: #f0f0f0;
        }

        /* Footer */
        footer {
            background-color: var(--secondary);
            color: var(--white);
            text-align: center;
            padding: 2rem;
            font-size: 0.9rem;
        }
    </style>
</head>
<body>
    <header>
        <nav>
            <div class="logo">VISIT CAVITE</div>
        </nav>
        <div class="hero-content">
            <h1>Cavite: Where History Comes Alive</h1>
            <p>Experience the harmonious blend of ancient traditions, and breathtaking seasonal landscapes in Cavltural capital.</p>
            <a href="#explore" class="btn">Explore Cavite</a>
        </div>
        <div></div> 
    </header>

    <!-- Highlights Section -->
    <main class="container" id="explore">
        <h2 class="section-title">Iconic Experiences</h2>
        <div class="grid">
            <div class="card">
                <img src="Cabiters.webp">
                <div class="card-body">
                    <h3>Aguinaldo Shrine</h3>
                    <p>The Aguinaldo Shrine in Kawit, Cavite, is the historic ancestral home of General Emilio Aguinaldo, the first president of the Philippines. It features a grand hall with a historic balcony, secret passageways, and a tall tower. The property also houses a museum and Aguinaldo's final resting place..</p>
                </div>
            </div>
            <div class="card">
                <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSeKT1L5JcpgukdLqnhQMN82ETrSoFNJFoEtkTBQnadfc5GcLdfDPgqH-Br&s=10" alt="Ternate">
                <div class="card-body">
                    <h3>Ternate Beach Resort</h3>
                    <p>an affordable, quick seaside escape with rustic charm, calm sea breezes, and a peaceful break from city noise.</p>
                </div>
            </div>
        </div>
    </main>

    <!-- CTA Banner -->
    <section class="cta-banner">
        <h2>Your Journey Awaits</h2>
        <p>Start planning your unforgettable Cavite get away today.</p>
        <a href="#" class="btn">Book Your Trip</a>
    </section>

    <!-- Footer -->
    <footer>
        <p>&copy; 2026 Group 4. Kasaysayan</p>
    </footer>
