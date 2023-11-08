# Rubyknapp13.github.io
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Law Firm Website</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#practice-areas">Practice Areas</a></li>
                <li><a href="#attorneys">Attorneys</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <section id="home">
        <h1>Welcome to XYZ Law Firm</h1>
        <p>Your trusted legal partner.</p>
    </section>

    <section id="practice-areas">
        <h2>Our Practice Areas</h2>
        <ul>
            <li>Criminal Defense</li>
            <li>Personal Injury</li>
            <li>Family Law</li>
            <li>Real Estate</li>
            <li>Corporate Law</li>
        </ul>
    </section>

    <section id="attorneys">
        <h2>Our Attorneys</h2>
        <div class="attorney">
            <img src="attorney1.jpg" alt="Attorney 1">
            <h3>John Doe</h3>
            <p>John Doe is a seasoned attorney with over 10 years of experience.</p>
        </div>
        <div class="attorney">
            <img src="attorney2.jpg" alt="Attorney 2">
            <h3>Jane Smith</h3>
            <p>Jane Smith specializes in family law and has a successful track record.</p>
        </div>
    </section>

    <section id="contact">
        <h2>Contact Us</h2>
        <p>If you need legal assistance, don't hesitate to get in touch with us.</p>
        <form id="contact-form">
            <label for="name">Name:</label>
            <input type="text" id="name" name="name" required>
            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required>
            <label for="message">Message:</label>
            <textarea id="message" name="message" required></textarea>
            <button type="submit">Send</button>
        </form>
    </section>

    <footer>
        <p>&copy; 2023 XYZ Law Firm. All rights reserved.</p>
    </footer>

    <script src="script.js"></script>
</body>
</html>
