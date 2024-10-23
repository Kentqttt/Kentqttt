<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Unique Website</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <!-- Navigation Bar -->
    <header>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#services">Services</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <!-- Hero Section -->
    <section id="home" class="hero-section">
        <div class="hero-content">
            <h1>Welcome to Your Unique Website</h1>
            <p>Creating digital experiences that matter.</p>
            <a href="#about" class="btn">Learn More</a>
        </div>
    </section>

    <!-- About Section -->
    <section id="about" class="about-section">
        <h2>About Us</h2>
        <p>We are a team of creative individuals passionate about delivering high-quality web solutions for our clients.</p>
    </section>

    <!-- Services Section -->
    <section id="services" class="services-section">
        <h2>Our Services</h2>
        <div class="service">
            <h3>Web Design</h3>
            <p>Creating visually stunning designs that engage users.</p>
        </div>
        <div class="service">
            <h3>Development</h3>
            <p>Developing functional, user-friendly websites and apps.</p>
        </div>
        <div class="service">
            <h3>SEO</h3>
            <p>Improving your website's visibility in search engines.</p>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="contact-section">
        <h2>Contact Us</h2>
        <p>Have a project in mind? Get in touch!</p>
        <a href="mailto:info@example.com" class="btn">Send an Email</a>
    </section>

    <!-- Footer -->
    <footer>
        <p>&copy; 2024 Your Unique Website | Designed by You</p>
    </footer>
</body>
</html>
<Style> /* General Reset */
* {
margin: 0;
padding: 0;
box-sizing: border-box;
}

/* Body Styling */
body {
font-family: Arial, sans-serif;
line-height: 1.6;
background-color: #f4f4f4;
}

/* Navigation Styling */
header {
background: #333;
color: #fff;
padding: 10px 0;
}

nav ul {
display: flex;
justify-content: center;
list-style: none;
}

nav ul li {
margin: 0 20px;
}

nav ul li a {
color: white;
text-decoration: none;
font-size: 18px;
}

nav ul li a:hover {
color: #ff5733;
}

/* Hero Section */
.hero-section {
background-image: url('https://source.unsplash.com/random/1600x900');
background-size: cover;
background-position: center;
height: 100vh;
display: flex;
justify-content: center;
align-items: center;
}

.hero-content {
text-align: center;
color: white;
}

.hero-content h1 {
font-size: 4em;
}

.hero-content p {
font-size: 1.2em;
margin: 20px 0;
}

.btn {
display: inline-block;
padding: 10px 20px;
background: #ff5733;
color: white;
border-radius: 5px;
text-decoration: none;
}

.btn:hover {
background: #ff2e00;
}

/* About Section */
.about-section {
padding: 50px;
text-align: center;
background-color: #fff;
}

.about-section h2 {
font-size: 2.5em;
margin-bottom: 20px;
}

/* Services Section */
.services-section {
padding: 50px;
text-align: center;
background-color: #f4f4f4;
}

.services-section h2 {
font-size: 2.5em;
margin-bottom: 20px;
}

.service {
margin-bottom: 30px;
}

.service h3 {
font-size: 1.8em;
margin-bottom: 10px;
}

.service p {
font-size: 1.1em;
}

/* Contact Section */
.contact-section {
padding: 50px;
text-align: center;
background-color: #fff;
}

.contact-section h2 {
font-size: 2.5em;
margin-bottom: 20px;
}

/* Footer */
footer {
text-align: center;
padding: 20px;
background-color: #333;
color: #fff;
}</Style