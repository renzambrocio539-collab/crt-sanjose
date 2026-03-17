<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CRT | Official Page</title>
    <style>
        /* Modern Blue & White Theme */
        :root {
            --primary-blue: #004a99;
            --light-blue: #e6f0ff;
            --white: #ffffff;
            --dark-blue: #002d62;
        }

        body {
            font-family: 'Segoe UI', Arial, sans-serif;
            margin: 0;
            padding: 0;
            line-height: 1.6;
            color: #333;
            background-color: var(--white);
        }

        /* Smooth Scrolling */
        html {
            scroll-behavior: smooth;
        }

        /* Navigation */
        nav {
            background: var(--primary-blue);
            color: var(--white);
            padding: 1.2rem;
            text-align: center;
            position: sticky;
            top: 0;
            z-index: 1000;
            box-shadow: 0 2px 10px rgba(0,0,0,0.1);
        }

        nav a {
            color: var(--white);
            text-decoration: none;
            margin: 0 20px;
            font-weight: 600;
            transition: opacity 0.3s;
        }

        nav a:hover {
            opacity: 0.7;
        }

        /* Hero Section */
        .hero {
            background: linear-gradient(135deg, var(--primary-blue), var(--dark-blue));
            color: var(--white);
            text-align: center;
            padding: 80px 20px;
        }

        .hero h1 {
            margin: 0;
            font-size: 2.5rem;
            letter-spacing: 1px;
        }

        /* Sections */
        section {
            padding: 60px 20px;
            max-width: 1000px;
            margin: auto;
        }

        h2 {
            color: var(--primary-blue);
            border-bottom: 3px solid var(--primary-blue);
            display: inline-block;
            margin-bottom: 30px;
        }

        #about {
            background-color: var(--white);
        }

        /* Photos Gallery */
        .gallery {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
            gap: 20px;
        }

        .gallery img {
            width: 100%;
            height: 250px;
            object-fit: cover;
            border-radius: 12px;
            border: 4px solid var(--light-blue);
            transition: transform 0.3s ease;
        }

        .gallery img:hover {
            transform: scale(1.03);
        }

        /* Map Styling */
        .map-container {
            border-radius: 15px;
            overflow: hidden;
            border: 5px solid var(--light-blue);
            box-shadow: 0 4px 15px rgba(0,0,0,0.1);
        }

        .map-container iframe {
            width: 100%;
            height: 400px;
            display: block;
        }

        /* Links Section */
        #links {
            background-color: var(--light-blue);
            border-radius: 20px;
            margin-bottom: 40px;
        }

        #links ul {
            list-style: none;
            padding: 0;
        }

        #links li {
            margin: 15px 0;
        }

        #links a {
            color: var(--primary-blue);
            text-decoration: none;
            font-weight: bold;
            font-size: 1.1rem;
        }

        #links a:hover {
            text-decoration: underline;
        }

        footer {
            background: var(--dark-blue);
            color: var(--white);
            text-align: center;
            padding: 30px;
        }
    </style>
</head>
<body>

    <nav>
        <a href="#about">About</a>
        <a href="#photos">Photos</a>
        <a href="#location">Location</a>
        <a href="#links">Links</a>
    </nav>

    <header class="hero">
        <h1>College for Research and Technology</h1>
        <p>Academic Portal & Information | San Jose Campus</p>
    </header>

    <section id="about">
        <h2>About Us</h2>
        <p>Welcome to the CRT San Jose information page. This institution focuses on providing quality education, including vocational certifications and specialized assessments in fields like Bookkeeping and Events Management.</p>
        <p><strong>#WOWCRT #IAMCONNECTED #CHOOSECRT</strong></p>
    </section>

    <section id="photos">
        <h2>Photos</h2>
        <div class="gallery">
            <img src="/1773711945732.jpg" alt="Campus Image 1">
            <img src="/1773710079710.jpg" alt="Classroom Image 2">
            <img src="/1773712220650.jpg" alt="Student Life Image 3">
        </div>
    </section>

    <section id="location">
        <h2>Our Location</h2>
        <p>Visit us at our campus in San Jose, Nueva Ecija.</p>
        <div class="map-container">
            <iframe 
                src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d61413.43542283921!2d120.94723146435307!3d15.785465551381333!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x339036f0f5b90209%3A0x67310f878f8d6890!2sSan%20Jose%20City%2C%20Nueva%20Ecija!5e0!3m2!1sen!2sph!4v1710000000000!5m2!1sen!2sph" 
                style="border:0;" 
                allowfullscreen="" 
                loading="lazy">
            </iframe>
        </div>
    </section>

    <section id="links">
        <h2>Quick Links</h2>
        <ul>
            <li><a href="https://www.facebook.com/share/1H8GWntjXs/" target="_blank">↗ Official Facebook Page</a></li>
            <li><a href="#about">↗ Student Portal Login</a></li>
            <li><a href="#about">↗ Assessment Schedules</a></li>
        </ul>
    </section>

    <footer>
        <p>© 2026 CRT SAN JOSE. All Rights Reserved.</p>
    </footer>

</body>
</html>
# crt-sanjose
initial upload
