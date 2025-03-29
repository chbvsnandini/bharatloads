# bharatloads
This is a high-converting, mobile-friendly landing page designed for the BharatLoads app. The page highlights the platform’s features, mission, and benefits while ensuring an intuitive and engaging user experience.
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>BharatLoads - Transforming Logistics</title>
    <style>
        body { font-family: 'Poppins', sans-serif; margin: 0; padding: 0; text-align: center; background: #f4f4f4; color: #333; }
        .hero { background: linear-gradient(135deg, #004aad, #002d6a); color: white; padding: 60px 20px; }
        .hero h1 { font-size: 2.5em; margin-bottom: 10px; font-weight: 600; }
        .hero p { font-size: 1.2em; margin-bottom: 20px; }
        .cta-button { display: inline-block; background: #ffcc00; padding: 12px 24px; margin-top: 15px; text-decoration: none; color: black; font-weight: bold; border-radius: 25px; transition: 0.3s; }
        .cta-button:hover { background: #ffaa00; }
        .section { padding: 60px 20px; }
        .features { background: white; display: flex; flex-wrap: wrap; justify-content: center; gap: 20px; }
        .features h2, .about h2, .mission h2, .download h2 { font-size: 2em; margin-bottom: 20px; color: #004aad; }
        .feature { background: #e3f2fd; padding: 20px; border-radius: 15px; max-width: 350px; box-shadow: 0 4px 8px rgba(0,0,0,0.1); text-align: center; }
        .feature img { width: 100px; height: auto; margin-bottom: 15px; }
        .feature h3 { color: #002d6a; }
        .download { background: #004aad; color: white; }
        .footer { background: #222; color: white; padding: 20px 0; font-size: 0.9em; }
    </style>
</head>
<body>
    <header class="hero">
        <nav>
            <img src="logo.png" alt="BharatLoads Logo" style="height: 60px; margin-bottom: 20px;">
        </nav>
        <h1>Revolutionizing Logistics with Technology</h1>
        <p>Connecting transporters and truck owners seamlessly for a more efficient and transparent logistics ecosystem.</p>
        <a href="#features" class="cta-button">Learn More</a>
    </header>

    <section id="about" class="section about">
        <h2>About BharatLoads</h2>
        <p>We are transforming India’s logistics by connecting transporters and truck owners through an innovative, map-based load-truck matching platform.</p>
    </section>

    <section id="features" class="section features">
        <h2>App Features</h2>
        <div class="feature">
            <img src="location-matching.png" alt="Location Matching">
            <h3>Location Load Truck Matching</h3>
            <p>Find the best matches based on real-time location data.</p>
        </div>
        <div class="feature">
            <img src="real-time-updates.png" alt="Real-Time Updates">
            <h3>Real-Time Updates</h3>
            <p>Get instant updates on available loads and trucks.</p>
        </div>
        <div class="feature">
            <img src="transparent-marketplace.png" alt="Transparent Marketplace">
            <h3>Transparent Marketplace</h3>
            <p>Access fair pricing, availability, and ratings with complete transparency.</p>
        </div>
    </section>

    <section id="mission" class="section mission">
        <h2>Our Mission & Vision</h2>
        <p>We strive to enhance efficiency, transparency, and profitability in logistics by leveraging cutting-edge technology.</p>
    </section>

    <!-- ✅ UPDATED DOWNLOAD BUTTON -->
    <section id="download" class="section download">
        <h2>Get Started with BharatLoads</h2>
        <p>Download the app now and streamline your logistics operations.</p>
        <a href="https://github.com/chbvsnandini/bharatloads/releases/download/v1.0/BharatLoads.apk" 
           class="cta-button" 
           download>
           Download APK
        </a>
    </section>

    <footer class="footer">
        <p>&copy; 2025 BharatLoads. All rights reserved.</p>
    </footer>
</body>
</html>
