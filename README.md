# PRIYADETAILS
MY RESUME FROM A WEB AI DEVELOPMENT COUSE
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Priya Details</title>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
        }
        nav {
            background-color: #f2f2f2;
            padding: 10px 20px;
            position: sticky;
            top: 0;
            display: flex;
            justify-content: space-between;
            align-items: center;
            z-index: 1000;
        }
        .nav-links {
            display: flex;
            gap: 15px;
        }
        .nav-links a {
            text-decoration: none;
            color: #333;
            font-weight: bold;
        }
        .nav-links a:hover {
            color: #007BFF;
        }
        .menu-icon {
            display: none;
            font-size: 24px;
            cursor: pointer;
        }

        @media (max-width: 600px) {
            .nav-links {
                display: none;
                flex-direction: column;
                background-color: #f2f2f2;
                position: absolute;
                top: 60px;
                left: 0;
                width: 100%;
                padding: 10px 0;
            }
            .nav-links.show {
                display: flex;
            }
            .menu-icon {
                display: block;
            }
        }

        section {
            padding: 20px;
        }
    </style>
</head>
<body>

    <nav>
        <div class="menu-icon" onclick="toggleMenu()">☰</div>
        <div class="nav-links" id="navLinks">
            <a href="#home">Home</a>
            <a href="#about">About</a>
            <a href="#contact">Contact</a>
        </div>
    </nav>

    <section id="home">
        <h1>Welcome to Priya's Website</h1>
        <p>This is the homepage content.</p>
    </section>

    <section id="about">
        <h2>About Priya</h2>
        <p>Priya is a dedicated professional with a passion for design and development.</p>
    </section>

    <section id="contact">
        <h2>Contact</h2>
        <p>You can reach Priya at: <a href="mailto:priya@example.com">priya@example.com</a></p>
    </section>

    <script>
        function toggleMenu() {
            const nav = document.getElementById("navLinks");
            nav.classList.toggle("show");
        }
    </script>

</body>
</html>
