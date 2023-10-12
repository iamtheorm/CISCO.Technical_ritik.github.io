<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Your Cisco Community</title>
    <link rel="stylesheet" href="styles.css">
    <style>
        /* Add your CSS styles here */
    </style>
</head>
<body>
    <header>
        <h1>Your Cisco Community</h1>
        <p>Welcome to the Community!</p>
        <p>The Community is a hub for connecting with your peers and Cisco specialists to ask for help, share your expertise, build your network, and grow professionally.</p>
    </header>

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

    <div class="tab-content" id="home">
        <!-- Content for the Home page -->
    </div>

    <div class="tab-content" id="cisco-community">
        <!-- Content for the CISCO Community page -->
    </div>

    <div class="tab-content" id="our-programs">
        <!-- Content for the Our Programs page -->
    </div>

    <div class="tab-content" id="global-networks">
        <!-- Content for the Global Networks page -->
    </div>

    <div class="tab-content" id="event-calendar">
        <!-- Content for the Event Calendar page -->
    </div>

    <div class="tab-content" id="member-stories">
        <!-- Content for the Member Stories page -->
    </div>

    <div class="tab-content" id="contact-us">
        <h2>Contact Us</h2>
        <p>Contact Number: 7408297060</p>
        <p>Email: <a href="mailto:ritik.23bce10850@vitbhopal.ac.in">ritik.23bce10850@vitbhopal.ac.in</a></p>
    </div>

    <footer>
        <a href="#">Community Feedback</a>
        <a href="#">Terms and Conditions</a>
        <a href="#">Privacy Statement</a>
        <a href="#">Help</a>
        <img src="cisco-logo.png" alt="Cisco Logo" width="100">
    </footer>

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
