<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="utf-8" />
    <link rel="icon" href="%PUBLIC_URL%/favicon.ico" />
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta name="theme-color" content="#000000" />
    <meta name="description" content="Pooja Singh's personal portfolio website." />
    <!-- Manifest JSON (if needed) -->
    <link rel="manifest" href="%PUBLIC_URL%/manifest.json" />
    <!-- Custom CSS -->
    <link rel="stylesheet" href="%PUBLIC_URL%/styles.css">
    <!-- Bootstrap CSS -->
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

    <!-- Content Sections -->
    <section id="home" class="container-fluid text-center text-navy py-5 bg-light-blue">
        <div class="container">
            <h1>Welcome to My Portfolio</h1>
            <p>I am a passionate Data Analyst and Developer.</p>
        </div>
    </section>

    <section id="about" class="container text-center py-5">
        <h2 class="text-navy bg-dark-blue py-2 px-4 rounded">About Me</h2>
        <img src="%PUBLIC_URL%/profile-pic.jpg" alt="Profile Picture" class="rounded-circle my-3 border-navy">
        <p class="text-navy">Hi, I'm Pooja Singh, a data enthusiast currently pursuing my master's in economics with a specialization in data analytics. I have experience in SQL, Python, Power BI, and more. I'm constantly learning and exploring new technologies.</p>
    </section>

    <section id="resume" class="container-fluid bg-light-blue py-5">
        <div class="container text-center">
            <h2 class="text-navy bg-dark-blue py-2 px-4 rounded">Resume</h2>
            <p class="text-navy">You can view my resume <a href="https://drive.google.com/file/d/1iOictfDzrIiqKhH9R_D4_MvKoGYQbGRl/view?usp=sharing" target="_blank" class="text-navy">here</a>.</p>
        </div>
    </section>

    <section id="projects" class="container text-center py-5">
        <h2 class="text-navy bg-dark-blue py-2 px-4 rounded">Projects</h2>
        <div class="row">
            <div class="col-md-4">
                <div class="card border-navy shadow-lg">
                    <img src="%PUBLIC_URL%/project1.jpg" class="card-img-top" alt="Project 1">
                    <div class="card-body">
                        <h5 class="card-title text-navy">Carbon Emission Analysis</h5>
                        <p class="card-text text-navy">Analyzed global carbon emissions using SQL, Power BI, and Excel. Created a dashboard to visualize emissions data by region and sector.</p>
                    </div>
                </div>
            </div>
            <div class="col-md-4">
                <div class="card border-navy shadow-lg">
                    <img src="%PUBLIC_URL%/project2.jpg" class="card-img-top" alt="Project 2">
                    <div class="card-body">
                        <h5 class="card-title text-navy">Real Estate Data Analysis</h5>
                        <p class="card-text text-navy">Conducted data cleaning and analysis on real estate transactions. Developed a Power BI dashboard to showcase market trends.</p>
                    </div>
                </div>
            </div>
            <div class="col-md-4">
                <div class="card border-navy shadow-lg">
                    <img src="%PUBLIC_URL%/project3.jpg" class="card-img-top" alt="Project 3">
                    <div class="card-body">
                        <h5 class="card-title text-navy">Load Forecasting for Energy Management</h5>
                        <p class="card-text text-navy">Implemented time series forecasting models to predict energy demand using Python libraries like Pandas, NumPy, and Scikit-learn.</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

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
