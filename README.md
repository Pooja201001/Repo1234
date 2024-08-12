<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <!-- Bootstrap CSS -->
    <link href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" rel="stylesheet">
    <style>
        /* Custom CSS */

        /* Global styles */
        body {
            font-family: Arial, sans-serif;
            background-color: white; /* Set the global background color to white */
            color: black; /* Set global text color to black */
        }

        /* Navbar styling */
        .navbar {
            background-color: #cca677; /* Navbar background color */
        }

        .navbar-brand, .nav-link {
            color: black !important; /* Navbar text color */
        }

        .navbar-toggler {
            background-color: #cca677; /* Toggler button background color */
        }

        .navbar-toggler-icon {
            background-image: none; /* Remove default icon background */
            color: white; /* Toggler icon color */
        }

        /* Home section styling */
        #home {
            background-color: white; /* Home section background color */
            color: black; /* Home section text color */
        }

        #home h1, #home p {
            color: black; /* Set color for h1 and p tags in the home section */
        }

        /* About section styling */
        #about h2 {
            background-color: #cca677; /* About section title background color */
            padding: 10px;
            color: black;
        }

        /* Resume section styling */
        #resume {
            background-color: white; /* Resume section background color */
            color: black; /* Resume section text color */
        }

        #resume h2 {
            background-color: #cca677; /* Resume section title background color */
            padding: 10px;
            color: black;
        }

        /* Projects section styling */
        #projects h2 {
            background-color: #cca677; /* Projects section title background color */
            padding: 10px;
            color: black;
        }

        /* Contact section styling */
        #contact {
            background-color: #cca677; /* Contact section background color */
            color: black; /* Contact section text color */
        }

        #contact h2, #contact p {
            color: black;
        }

        #contact a {
            color: black; /* Links in the contact section */
            text-decoration: none;
        }

        #contact a:hover {
            text-decoration: underline; /* Hover effect for links */
        }
    </style>
</head>

<body>
    <!-- Navbar -->
    <nav class="navbar navbar-expand-lg">
        <a class="navbar-brand" href="#">Pooja Singh</a>
        <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon">☰</span>
        </button>
        <div class="collapse navbar-collapse" id="navbarNav">
            <ul class="navbar-nav ml-auto">
                <li class="nav-item active">
                    <a class="nav-link" href="#home">Home</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#about">About</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#resume">Resume</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#projects">Projects</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#contact">Contact</a>
                </li>
            </ul>
        </div>
    </nav>

    <!-- Home Section -->
    <section id="home" class="container-fluid text-center py-5">
        <div class="container">
            <div class="row">
                <div class="col-md-6 d-flex align-items-center">
                    <img src="https://drive.google.com/file/d/1OfDgmeKobJ2SJr8ZbNa2Q5s9C97otdhq/view?usp=drive_link" alt="Profile Picture" class="rounded-circle mx-auto d-block">
                </div>
                <div class="col-md-6 text-center text-md-left">
                    <h1>Pooja Singh</h1>
                    <p>MSc Economics with Data Analytics Specialization</p>
                    <p>From Symbiosis School of Economics</p>
                    <p>Pune</p>
                </div>
            </div>
        </div>
    </section>

    <!-- About Section -->
    <section id="about" class="container text-center py-5">
        <h2>About Me</h2>
        <p>Hello! I'm Pooja Singh, currently pursuing an MSc in Economics with a specialization in Data Analytics at Symbiosis School of Economics, Pune. I am passionate about leveraging data to drive meaningful insights and solutions. My academic journey began with a BSc in Economics, where I developed a strong foundation in economic theories and data analysis.</p>
        <p>I have gained practical experience through internships at Cybrom Technology Pvt. Ltd. and JS Baghel & Co., where I honed my skills in data cleaning, analysis, and visualization. My projects have included comprehensive analyses of carbon emissions and market trends, providing valuable insights for environmental and business decision-making.</p>
        <p>In addition to my technical skills in SQL, Python, R and data visualization tools like PowerBI and Tableau, I am committed to continuous learning and professional growth. Feel free to connect with me via email or LinkedIn to explore opportunities or discuss data-driven solutions!</p>
    </section>

    <!-- Resume Section -->
    <section id="resume" class="container-fluid py-5">
        <div class="container">
            <h2 class="text-center">Resume</h2>
            <p class="text-center">You can view my resume <a href="https://drive.google.com/file/d/1iOictfDzrIiqKhH9R_D4_MvKoGYQbGRl/view?usp=drive_link" target="_blank">here</a>.</p>
        </div>
    </section>

    <!-- Projects Section -->
    <section id="projects" class="container text-center py-5">
        <h2>Projects</h2>
        <div class="row">
            <div class="col-md-4">
                <div class="card">
                    <img src="https://via.placeholder.com/350" class="card-img-top" alt="Project 1">
                    <div class="card-body">
                        <h5 class="card-title">Carbon Emission Analysis</h5>
                        <p class="card-text">Analyzed global carbon emissions using Excel. Created a dashboard to visualize emissions data by region and sector.</p>
                    </div>
                </div>
            </div>
            <div class="col-md-4">
                <div class="card">
                    <img src="https://via.placeholder.com/350" class="card-img-top" alt="Project 2">
                    <div class="card-body">
                        <h5 class="card-title">Real Estate Data Analysis</h5>
                        <p class="card-text">Conducted data cleaning and analysis on real estate transactions. Developed a Power BI dashboard to showcase market trends.</p>
                    </div>
                </div>
            </div>
            <div class="col-md-4">
                <div class="card">
                    <img src="https://via.placeholder.com/350" class="card-img-top" alt="Project 3">
                    <div class="card-body">
                        <h5 class="card-title">Load Forecasting for Energy Management</h5>
                        <p class="card-text">Implemented time series forecasting models to predict energy demand using Python libraries like Pandas, NumPy, and Scikit-learn.</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="container-fluid py-5">
        <div class="container text-center">
            <h2>Contact Me</h2>
            <p>I'd love to hear from you! Feel free to reach out via email or connect with me on LinkedIn.</p>
            <p>Email: <a href="mailto:poojasingh.work20@gmail.com" class="text-light">poojasingh.work20@gmail.com
            </a></p>
            <p><a href="http://www.linkedin.com/in/poojasingh2010" class="text-light">LinkedIn Profile</a></p>
        </div>
    </section>

    <!-- Bootstrap JS and dependencies -->
    <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.5.2/dist/umd/popper.min.js"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
</body>
</html>


