# Rubyknapp13.github.io
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="styles.css">
    <title>Sticky Header Example</title>
</head>
<body>
    <header class="sticky-header">
        <h1>My Sticky Header</h1>
    </header>
    <div class="content">
        <!-- Your website content goes here -->
    </div>
    <script src="script.js"></script>
</body>
</html>
CSS (styles.css):

css
Copy code
body {
    margin: 0;
    padding: 0;
    font-family: Arial, sans-serif;
}

.sticky-header {
    background-color: #333;
    color: #fff;
    padding: 10px 0;
    position: fixed;
    top: 0;
    width: 100%;
    z-index: 100;
    transition: background-color 0.3s, padding 0.3s;
}

.sticky-header.sticky {
    background-color: #fff;
    color: #333;
    padding: 5px 0;
    box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
}
.content {
    padding: 20px;
    margin-top: 60px; /* Adjust this margin to avoid content overlapping with the header */
}
JavaScript (script.js):

javascript
Copy code
window.addEventListener("scroll", function () {
    const header = document.querySelector(".sticky-header");
    if (window.scrollY > 0) {
        header.classList.add("sticky");
    } else {
        header.classList.remove("sticky");
    }
});
This code creates a simple sticky header that becomes fixed to the top of the page when the user scrolls down. The header changes its background color and padding when it becomes sticky to create a visual effect. You can adjust the styles and appearance to match your website's design.





