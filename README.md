<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="utf-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta name="description" content="Pooja Singh's personal portfolio website." />
    <link rel="icon" href="favicon.ico" />
    <link rel="stylesheet" href="styles.css">
    <link href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" rel="stylesheet">
    <title>Pooja Singh - Portfolio</title>
</head>
<body>
    <!-- Navbar -->
    <nav class="navbar navbar-expand-lg navbar-dark bg-dark-blue">
        <a class="navbar-brand" href="#">Pooja Singh</a>
        <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarNav">
            <ul class="navbar-nav ml-auto">
                <li class="nav-item">
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
    <section id="home" class="hero bg-light-blue text-center text-navy d-flex align-items-center">
        <div class="container">
            <h1>Welcome to My Portfolio</h1>
            <p>I am a Data Analyst and Developer with a passion for technology.</p>
        </div>
    </section>

    <!-- About Section -->
    <section id="about" class="container text-center py-5">
        <h2 class="text-navy bg-dark-blue py-2 px-4 rounded">About Me</h2>
        <img src="profile-pic.jpg" alt="Profile Picture" class="rounded-circle my-3 border-navy" width="150">
        <p class="text-navy">Hi, I'm Pooja Singh. I specialize in data analytics and have experience with SQL, Python, Power BI, and more. I am constantly exploring new technologies and improving my skills.</p>
    </section>

    <!-- Resume Section -->
    <section id="resume" class="container-fluid bg-light-blue py-5">
        <div class="container text-center">
            <h2 class="text-navy bg-dark-blue py-2 px-4 rounded">Resume</h2>
            <p class="text-navy">View my resume <a href="https://drive.google.com/file/d/1iOictfDzrIiqKhH9R_D4_MvKoGYQbGRl/view?usp=sharing" target="_blank" class="text-navy">here</a>.</p>
        </div>
    </section>

    <!-- Projects Section -->
    <section id="projects" class="container text-center py-5">
        <h2 class="text-navy bg-dark-blue py-2 px-4 rounded">Projects</h2>
        <div class="row">
            <div class="col-md-4">
                <div class="card border-navy shadow-lg">
                    <img src="project1.jpg" class="card-img-top" alt="Project 1">
                    <div class="card-body">
                        <h5 class="card-title text-navy">Carbon Emission Analysis</h5>
                        <p class="card-text text-navy">Analyzed global carbon emissions using SQL, Power BI, and Excel. Created a dashboard to visualize emissions data by region and sector.</p>
                    </div>
                </div>
            </div>
            <div class="col-md-4">
                <div class="card border-navy shadow-lg">
                    <img src="project2.jpg" class="card-img-top" alt="Project 2">
                    <div class="card-body">
                        <h5 class="card-title text-navy">Real Estate Data Analysis</h5>
                        <p class="card-text text-navy">Conducted data cleaning and analysis on real estate transactions. Developed a Power BI dashboard to showcase market trends.</p>
                    </div>
                </div>
            </div>
            <div class="col-md-4">
                <div class="card border-navy shadow-lg">
                    <img src="project3.jpg" class="card-img-top" alt="Project 3">
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
            <h2 class="text-navy bg-dark-blue py-2 px-4 rounded">Contact Me</h2>
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
    margin: 0;
    padding: 0;
}

/* Navbar */
.navbar-dark .navbar-nav .nav-link {
    color: #fff;
}

.navbar-dark .navbar-nav .nav-link:hover {
    color: #d1d1d1;
}

/* Hero Section */
.hero {
    min-height: 100vh;
    display: flex;
    align-items: center;
    justify-content: center;
    color: #000080;
}

.hero h1 {
    font-size: 3rem;
    margin-bottom: 20px;
}

.hero p {
    font-size: 1.2rem;
}

/* About Section */
.rounded-circle {
    border: 4px solid #000080;
}

/* Cards */
.card {
    border: 2px solid #000080;
}

.card-img-top {
    height: 200px;
    object-fit: cover;
}

/* Custom Colors */
.bg-light-blue {
    background-color: #e6f2ff;
}

.bg-dark-blue {
    background-color: #000080;
}

.text-navy {
    color: #000080;
}

.border-navy {
    border: 2px solid #000080;
}
