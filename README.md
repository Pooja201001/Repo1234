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
    <section id="home" class="container-fluid text-center text-navy py-5 bg-light-blue">
        <div class="container">
            <h1>Welcome to My Portfolio</h1>
            <p>I am a passionate Data Analyst and Developer.</p>
        </div>
    </section>

    <!-- About Section -->
    <section id="about" class="container text-center py-5">
        <h2 class="text-navy bg-dark-blue py-2 px-4 rounded">About Me</h2>
        <img src="https://via.placeholder.com/150" alt="Profile Picture" class="rounded-circle my-3 border-navy">
        <p class="text-navy">Hi, I'm Pooja Singh, a data enthusiast currently pursuing my master's in economics with a specialization in data analytics. I have experience in SQL, Python, Power BI, and more. I'm constantly learning and exploring new technologies.</p>
    </section>

    <!-- Resume Section -->
    <section id="resume" class="container-fluid bg-light-blue py-5">
        <div class="container text-center">
            <h2 class="text-navy bg-dark-blue py-2 px-4 rounded">Resume</h2>
            <p class="text-navy">You can view my resume <a href="https://drive.google.com/file/d/1iOictfDzrIiqKhH9R_D4_MvKoGYQbGRl/view?usp=sharing" target="_blank" class="text-navy">here</a>.</p>
        </div>
    </section>

    <!-- Projects Section -->
    <section id="projects" class="container text-center py-5">
        <h2 class="text-navy bg-dark-blue py-2 px-4 rounded">Projects</h2>
        <div class="row">
            <div class="col-md-4">
                <div class="card border-navy shadow-lg">
                    <img src="https://via.placeholder.com/350" class="card-img-top" alt="Project 1">
                    <div class="card-body">
                        <h5 class="card-title text-navy">Carbon Emission Analysis</h5>
                        <p class="card-text text-navy">Analyzed global carbon emissions using SQL, Power BI, and Excel. Created a dashboard to visualize emissions data by region and sector.</p>
                    </div>
                </div>
            </div>
            <div class="col-md-4">
                <div class="card border-navy shadow-lg">
                    <img src="https://via.placeholder.com/350" class="card-img-top" alt="Project 2">
                    <div class="card-body">
                        <h5 class="card-title text-navy">Real Estate Data Analysis</h5>
                        <p class="card-text text-navy">Conducted data cleaning and analysis on real estate transactions. Developed a Power BI dashboard to showcase market trends.</p>
                    </div>
                </div>
            </div>
            <div class="col-md-4">
                <div class="card border-navy shadow-lg">
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
    background-color: #e6f2ff; /* Light blue background */
    color: #000080; /* Navy blue text */
}

h1, h2, p {
    margin: 0;
}

/* Navbar */
.navbar-dark {
    background-color: #000080; /* Dark blue background */
}

.navbar-dark .navbar-brand {
    color: #fff;
}

.navbar-dark .nav-link {
    color: #fff;
    border-radius: 5px;
    padding: 10px;
    margin-left: 10px;
}

.navbar-dark .nav-link:hover {
    background-color: #003366; /* Darker blue on hover */
}

/* Home Section */
#home {
    background: url('https://via.placeholder.com/1920x1080') no-repeat center center/cover;
}

#home h1 {
    font-size: 3rem;
    font-weight: bold;
}

#home p {
    font-size: 1.25rem;
}

/* About Section */
#about {
    background-color: #e6f2ff;
}

#about img {
    width: 150px;
    height: 150px;
    border: 5px solid #000080; /* Navy blue border */
}

#about h2 {
    background-color: #000080; /* Dark blue background */
    color: #fff;
    padding: 10px;
    border-radius: 5px;
}

/* Resume Section */
#resume {
    background-color: #e6f2ff;
}

#resume h2 {
    background-color: #000080; /* Dark blue background */
    color: #fff;
    padding: 10px;
    border-radius: 5px;
}

/* Projects Section */
#projects {
    background-color: #e6f2ff;
}

#projects .card {
    border: 2px solid #000080; /* Navy blue border */
    margin-bottom: 20px;
    border-radius: 10px;
    transition: transform 0.3s ease-in-out;
}

#projects .card:hover {
    transform: scale(1.05);
}

#projects .card-body {
    border-top: 2px solid #000080; /* Navy blue border */
}

/* Contact Section */
#contact {
    background-color: #e6f2ff;
}

#contact h2 {
    background-color: #000080; /* Dark blue background */
    color: #fff;
    padding: 10px;
    border-radius: 5px;
}

/* Custom Classes */
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
