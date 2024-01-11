# prism
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Prism Management - Furnished Rentals</title>
    <link rel="stylesheet" href="styles.css"> <!-- Link to your CSS file for styling -->
    <style>
        /* Add specific styling for this modern design */
        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        header {
            background: #333;
            color: #fff;
            padding: 20px;
            text-align: center;
        }

        nav {
            background: #555;
            color: #fff;
            padding: 10px;
            text-align: center;
        }

        nav ul {
            list-style: none;
            margin: 0;
            padding: 0;
        }

        nav li {
            display: inline;
            margin-right: 20px;
        }

        section {
            padding: 40px;
            text-align: center;
        }

        .property {
            margin-bottom: 40px;
            border: 1px solid #ddd;
            padding: 20px;
            border-radius: 8px;
            background: #fff;
        }

        .property img {
            max-width: 100%;
            border-radius: 8px;
        }

        .property-link {
            display: block;
            margin-top: 10px;
            background: #333;
            color: #fff;
            padding: 10px;
            text-decoration: none;
            border-radius: 5px;
        }

        footer {
            background: #333;
            color: #fff;
            padding: 20px;
            text-align: center;
        }
    </style>
</head>
<body>

    <!-- Header Section -->
    <header>
        <h1>Welcome to Prism Management</h1>
        <p>Your go-to destination for quality furnished rentals</p>
    </header>

    <!-- Navigation Section -->
    <nav>
        <ul>
            <li><a href="#home">Home</a></li>
            <li><a href="#property1">Property 1</a></li>
            <li><a href="#property2">Property 2</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </nav>

    <!-- Main Content Section -->
    <section id="home">
        <h2>Explore Our Furnished Rentals</h2>
        <p>Discover comfortable and stylish homes for your short or long-term stay.</p>
    </section>

    <!-- Property 1 Section -->
    <section id="property1" class="property">
        <h2>Property 1</h2>
        <img src="property1_cover.jpg" alt="Property 1 Cover Photo">
        <p>Description of Property 1 in Souderton and its features.</p>
        <a href="property1.html" class="property-link">View Details</a>
    </section>

    <!-- Property 2 Section -->
    <section id="property2" class="property">
        <h2>Property 2</h2>
        <img src="property2_cover.jpg" alt="Property 2 Cover Photo">
        <p>Description of Property 2 in East Norriton and its features.</p>
        <a href="property2.html" class="property-link">View Details</a>
    </section>

    <!-- Contact Section -->
    <section id="contact">
        <h2>Contact Us</h2>
        <p>Have questions or ready to rent? Get in touch with us!</p>
        <form action="submit_form.php" method="post">
            <!-- Your contact form goes here -->
        </form>
    </section>

    <!-- Footer Section -->
    <footer>
        <p>&copy; 2024 Prism Management. All rights reserved.</p>
    </footer>

</body>
</html>
