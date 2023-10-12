<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Your Cisco Community</title>
    <link rel="stylesheet" href="styles.css">
    <style>
        /* Inline CSS for demonstration purposes; consider using an external CSS file */
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 10px 0;
        }
        nav ul {
            list-style-type: none;
            margin: 0;
            padding: 0;
            text-align: center;
        }
        nav ul li {
            display: inline;
            margin-right: 20px;
        }
        nav a {
            color: #fff;
            text-decoration: none;
            transition: color 0.3s;
        }
        nav a:hover {
            color: #FFA500;
        }
        .tab-content {
            padding: 20px;
            background-color: #fff;
            text-align: center;
            display: none;
        }
        .active {
            display: block;
        }
    </style>
</head>
<body>
    <header>
        <h1>Your Cisco Community</h1>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#cisco-community">CISCO Community</a></li>
                <li><a href="#our-programs">Our Programs</a></li>
                <li><a href="#global-networks">Global Networks</a></li>
                <li><a href="#event-calendar">Event Calendar</a></li>
                <li><a href="#member-stories">Member Stories</a></li>
                <li><a href="#contact-us">Contact Us</a></li>
            </ul>
        </nav>
    </header>

    <div class="tab-content" id="home">
        <h2>Welcome to Our Cisco Community</h2>
        <p>This is where you can find all the information related to Cisco in our college.</p>
    </div>

    <div class="tab-content" id="cisco-community">
        <h2>CISCO Community</h2>
        <p>Explore our vibrant Cisco community and join us in our tech journey.</p>
    </div>

    <div class="tab-content" id="our-programs">
        <h2>Our Programs</h2>
        <p>Discover the exciting programs and opportunities we offer to our members.</p>
    </div>

    <div class="tab-content" id="global-networks">
        <h2>Global Networks</h2>
        <p>Connect with Cisco enthusiasts from around the world through our global networks.</p>
    </div>

    <div class="tab-content" id="event-calendar">
        <h2>Event Calendar</h2>
        <p>Stay updated on upcoming Cisco-related events, workshops, and seminars.</p>
    </div>

    <div class="tab-content" id="member-stories">
        <h2>Member Stories</h2>
        <p>Read inspiring stories and experiences shared by our Cisco community members.</p>
    </div>

    <div class="tab-content" id="contact-us">
        <h2>Contact Us</h2>
        <p>Have questions or feedback? Get in touch with us through the provided contact information.</p>
    </div>

    <script>
        // JavaScript to handle tab switching
        const tabs = document.querySelectorAll("nav a");
        const tabContents = document.querySelectorAll(".tab-content");

        tabs.forEach((tab, index) => {
            tab.addEventListener("click", () => {
                tabContents.forEach((content) => content.classList.remove("active"));
                tabContents[index].classList.add("active");
            });
        });
    </script>
</body>
</html>
