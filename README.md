<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>MML Studios</title>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;500;700&display=swap" rel="stylesheet"
    <style>
        /* General Styles */
        body, html {
            font-family:'Poppins'', sans-serif;
            margin: 0;
            padding: 0;
            height: 100%;
            background-color: #111;
            color: #fff;
        }

        a {
            text-decoration: none;
            color: inherit;
        }

        /* Header Styles */
        header {
            background-color: 	#000000;
            text-align: center;
            padding: 2rem 0;
            position: sticky;
            top: 0;
            z-index: 1000;
        }

        /* Navigation Styles */
        nav {
            display: flex;
            justify-content: space-around;
            padding: 1rem 0;
            background-color: 	#C0C0C0;
        }

        nav a {
            padding: 0.5rem 1rem;
            border-radius: 5px;
            transition: background-color 0.3s;
        }

        nav a:hover {
            background-color: #555;
        }

        /* Main Content Styles */
        .content {
            max-width: 1200px;
            margin: 4rem auto;
            padding: 2rem;
            border-radius: 10px;
            background-color: rgba(255, 255, 255, 0.05);
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.3);
        }

        /* Footer Styles */
        footer {
            background-color: #8080808
            ;
            text-align: center;
            padding: 1.5rem 0;
            position: absolute;
            width: 100%;
            bottom: 1;
        }

        /* Smooth scroll */
        html {
            scroll-behavior: smooth;
        }
    </style>
</head>

<body>
    <header>
        <h1> 𝑴𝑴𝑳 𝑺𝒕𝒖𝒅𝒊𝒐𝒔 </h1>
    </header>

    <nav>
        <a href="#home">Home</a>
        <a href="#services">Services</a>
        <a href="#portfolio">Portfolio</a> 
        <a href="#about">About</a>
        <a href="#contact">Contact</a>
    
    </nav>

    <div class="content" id="home">
        <h2>Welcome to MML Studios</h2>
        <p>Welcome to MML Studios we strive to make perfect music for you. We make music for you to enjoy and use.</p>
    </div>

    <div class="content" id="services">
        <h2>Our Services</h2>
        <p> MML Studios offers music making, help you make your dream music and so much more.</p>
    </div>

    <div class="content" id="portfolio">
        <h2>Portfolio</h2>
        <p>Some of our best works is showcased here.</p>
   
         <iframe width="560" height="315" src="https://www.youtube.com/embed/xRqPrDfHEto" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe> 
   
        <iframe width="560" height="315" src="https://www.youtube.com/embed/GQChZFOJ72o" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
        
      <scroll-behavior: smooth;>
    </div>

    <div class="content" id="about">
        <h2>About Us</h2>
        <p>Welcome to MML Studios website we make music for you to buy use share and much nore we strive for great exprince and hope to have you on our jounery.</p>
    </div>

    <div class="content" id="contact">
        <h2>Contact</h2>
        <p>Reach out to us for collaborations, inquiries, or any other simplebeats654@gmail.com.</p>
   

     <footer>
        &copy; 2023 MML Studios. All rights reserved.
    </footer>

    <script>
        // Smooth scrolling for anchor links
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                e.preventDefault();

                document.querySelector(this.getAttribute('href')).scrollIntoView({
                    behavior: 'smooth'
                });
            });
        });
    </script>
    </body>
</html>
