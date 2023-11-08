# Rubyknapp13.github.io
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Law Firm Website</title>
    <style>
         /* Global Styles */
        body {
            font-family: Arial, sans-serif;
            background-color: #f5f5f5;
            color: #333;
            margin: 0;
            padding: 0;
        }

        header {
            background-color: #0a4e8f;
            color: #fff;
            padding: 20px;
        }

        nav ul {
            list-style: none;
            padding: 0;
        }

        nav li {
            display: inline;
            margin-right: 20px;
        }

        nav a {
            text-decoration: none;
            color: #fff;
        }

        /* Section Styles */
        section {
            padding: 20px;
            margin: 20px;
            background-color: #fff;
            border-radius: 5px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }

        #home {
            background-color: #f0f0f0;
        }

        #practice-areas {
            background-color: #e6e6e6;
        }

        #about-us {
            background-color: #f0f0f0;
        }

        #contact {
            background-color: #e6e6e6;
        }

        /* Button Styles */
        button {
            background-color: #0a4e8f;
            color: #fff;
            border: none;
            padding: 10px 20px;
            cursor: pointer;
        }

        button:hover {
            background-color: #004080;
        }

    </style>
</head>
<body>
    <header>
        <h1>Law Firm Name</h1>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#practice-areas">Practice Areas</a></li>
                <li><a href="#about-us">About Us</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>
    <section id="home">
        <h2>Welcome to Law Firm Name</h2>
        <p>We are committed to providing quality legal services.</p>
    </section>
    <section id="practice-areas">
        <h2>Practice Areas</h2>
        <ul>
            <li>Criminal Defense</li>
            <li>Family Law</li>
            <li>Personal Injury</li>
            <li>Real Estate</li>
        </ul>
    </section>
    <section id="about-us">
        <h2>About Us</h2>
        <p>We have a team of experienced lawyers who are dedicated to helping our clients.</p>
    </section>
    <section id="contact">
        <h2>Contact Us</h2>
        <p>Get in touch with us for legal assistance.</p>
        <button id="contact-button">Contact Now</button>
    </section>
    <script>
        // JavaScript for interactivity
        document.getElementById("contact-button").addEventListener("click", function () {
            alert("Please call us at 555-123-4567 or send us an email at info@lawfirmname.com.");
        });
    </script>
</body>
</html>
