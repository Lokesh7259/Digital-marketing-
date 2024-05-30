# Digital-marketing-<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>AI for Digital Marketing</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <div class="navbar">
            <div class="logo">AIDigital</div>
            <nav>
                <ul>
                    <li><a href="#home">Home</a></li>
                    <li><a href="#about">About</a></li>
                    <li><a href="#tools">AI Tools</a></li>
                    <li><a href="#contact">Contact</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <section id="home" class="hero">
        <div class="hero-text">
            <h1>Welcome to AIDigital</h1>
            <p>Your one-stop solution for AI-powered digital marketing tools and resources.</p>
            <a href="#tools" class="cta-button">Explore AI Tools</a>
        </div>
    </section>

    <section id="about" class="section">
        <h2>About Us</h2>
        <p>AIDigital is dedicated to providing cutting-edge AI tools and resources to help digital marketers enhance their campaigns, analyze data, and optimize their strategies for better results.</p>
    </section>

    <section id="tools" class="section">
        <h2>AI Tools</h2>
        <div class="tools-container">
            <div class="tool">
                <h3>AI Content Generator</h3>
                <p>Generate high-quality content for your blog, social media, or website using our AI-powered content generator.</p>
            </div>
            <div class="tool">
                <h3>AI Analytics</h3>
                <p>Analyze your marketing data and gain valuable insights with our advanced AI analytics tool.</p>
            </div>
            <div class="tool">
                <h3>AI Chatbots</h3>
                <p>Enhance customer engagement and support with AI-driven chatbots that provide instant responses to inquiries.</p>
            </div>
        </div>
    </section>

    <section id="contact" class="section">
        <h2>Contact Us</h2>
        <form action="submit-form.php" method="post">
            <label for="name">Name:</label>
            <input type="text" id="name" name="name" required>
            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required>
            <label for="message">Message:</label>
            <textarea id="message" name="message" rows="4" required></textarea>
            <button type="submit">Submit</button>
        </form>
    </section>

    <footer>
        <p>&copy; 2024 AIDigital. All rights reserved.</p>
    </footer>
</body>
</html>
