<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Pooja Singh - Portfolio</title>
    <!-- Bootstrap CSS -->
    <link href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" rel="stylesheet">
    <!-- Custom CSS -->
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <!-- Navbar -->
    <nav class="navbar navbar-expand-lg navbar-light bg-light">
        <a class="navbar-brand text-navy" href="#">Pooja Singh</a>
        <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarNav">
            <ul class="navbar-nav ml-auto">
                <li class="nav-item">
                    <a class="nav-link text-navy border-navy" href="#home">Home</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link text-navy border-navy" href="#about">About</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link text-navy border-navy" href="#resume">Resume</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link text-navy border-navy" href="#projects">Projects</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link text-navy border-navy" href="#contact">Contact</a>
                </li>
            </ul>
        </div>
    </nav>

    <!-- Home Section -->
    <section id="home" class="container-fluid text-center text-navy py-5 bg-light-blue">
        <div class="container">
            <h1>Welcome to My Portfolio</h1>
            <p>I am a passionate Data Analyst and Developer.</p>
        </div>
    </section>

    <!-- About Section -->
    <section id="about" class="container text-center py-5">
        <h2 class="text-navy">About Me</h2>
        <img src="https://via.placeholder.com/150" alt="Profile Picture" class="rounded-circle my-3">
        <p class="text-navy">Hi, I'm Pooja Singh, a data enthusiast currently pursuing my master's in economics with a specialization in data analytics. I have experience in SQL, Python, Power BI, and more. I'm constantly learning and exploring new technologies.</p>
    </section>

    <!-- Resume Section -->
    <section id="resume" class="container-fluid bg-light py-5">
        <div class="container text-center">
            <h2 class="text-navy">Resume</h2>
            <p class="text-navy">You can view my resume <a href="https://www.example.com" target="_blank" class="text-navy">here</a>.</p>
        </div>
    </section>

    <!-- Projects Section -->
    <section id="projects" class="container text-center py-5">
        <h2 class="text-navy">Projects</h2>
        <div class="row">
            <div class="col-md-4">
                <div class="card border-navy">
                    <img src="https://via.placeholder.com/350" class="card-img-top" alt="Project 1">
                    <div class="card-body">
                        <h5 class="card-title text-navy">Carbon Emission Analysis</h5>
                        <p class="card-text text-navy">Analyzed global carbon emissions using SQL, Power BI, and Excel. Created a dashboard to visualize emissions data by region and sector.</p>
                    </div>
                </div>
            </div>
            <div class="col-md-4">
                <div class="card border-navy">
                    <img src="https://via.placeholder.com/350" class="card-img-top" alt="Project 2">
                    <div class="card-body">
                        <h5 class="card-title text-navy">Real Estate Data Analysis</h5>
                        <p class="card-text text-navy">Conducted data cleaning and analysis on real estate transactions. Developed a Power BI dashboard to showcase market trends.</p>
                    </div>
                </div>
            </div>
            <div class="col-md-4">
                <div class="card border-navy">
                    <img src="https://via.placeholder.com/350" class="card-img-top" alt="Project 3">
                    <div class="card-body">
                        <h5 class="card-title text-navy">Load Forecasting for Energy Management</h5>
                        <p class="card-text text-navy">Implemented time series forecasting models to predict energy demand using Python libraries like Pandas, NumPy, and Scikit-learn.</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="container-fluid bg-light-blue text-navy py-5">
        <div class="container text-center">
            <h2 class="text-navy">Contact Me</h2>
            <p>I'd love to hear from you! Feel free to reach out via email or connect with me on LinkedIn.</p>
            <p>Email: <a href="mailto:pooja.singh@example.com" class="text-navy">pooja.singh@example.com</a></p>
            <p><a href="https://www.linkedin.com/in/your-profile" class="text-navy">LinkedIn Profile</a></p>
        </div>
    </section>

    <!-- Bootstrap JS and dependencies -->
    <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.5.2/dist/umd/popper.min.js"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
</body>
</html>

/* General Styles */
body {
    font-family: Arial, sans-serif;
    background-color: #f0f8ff; /* Very light blue background */
}

/* Custom Colors */
.text-navy {
    color: #000080; /* Navy blue color */
}

.bg-light-blue {
    background-color: #e6f2ff; /* Light blue color */
}

.border-navy {
    border: 2px solid #000080; /* Navy blue border */
}

/* Navbar */
.navbar-light .navbar-brand {
    color: #000080;
}

.navbar-light .nav-link {
    color: #000080;
    border-radius: 5px;
    padding: 5px 10px;
    margin-left: 10px;
    border: 2px solid transparent;
}

.navbar-light .nav-link:hover {
    border-color: #000080;
}

/* Home Section */
#home h1 {
    font-size: 3rem;
    font-weight: bold;
}

#home p {
    font-size: 1.25rem;
}

/* About Section */
#about img {
    width: 150px;
    height: 150px;
    border: 5px solid #000080;
}

/* Projects Section */
#projects .card {
    margin-bottom: 20px;
}

#projects .card-body {
    border-top: 2px solid #000080;
}

/* Contact Section */
#contact a {
    color: #000080;
    text-decoration: none;
}

#contact a:hover {
    text-decoration: underline;
}
