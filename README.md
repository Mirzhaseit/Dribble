# Project Responsive Web Design using Bootstrap
## Date:03-01-2025


## AIM:
To create a simplified clone of Dribbble (https://dribbble.com/) landing page.


## DESIGN STEPS:

### Step 1:
Clone the repository from GitHub.

### Step 2:
Create Django Admin project.

### Step 3:
Create a New App under the Django Admin project.

### Step 4:
Insert the necessary CSS and JavaScript files as external in order to use Bootstrap.

### Step 5:
Create a HTML file and include the needed Bootstrap components.

### Step 6:
Publish the website in the LocalHost.

## PROGRAM :
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Dribbble Clone</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
    <style>
        .navbar-nav .nav-link:hover {
            color: #28a745 !important;
        }
        .btn-signup {
            background-color: #ff5722;
            color: white;
        }
        .btn-signup:hover {
            background-color: #e64a19;
        }
        .hero-section {
            background: linear-gradient(135deg, #434242, #1e1e1e);
            padding: 5rem 1rem;
        }
        .hero-section img {
            border-radius: 50%;
        }
        .featured-journey img:hover {
            transform: scale(1.05);
            transition: transform 0.3s ease;
        }
        footer .social-icons i {
            font-size: 1.5rem;
            margin: 0 0.5rem;
            color: white;
        }
        footer .social-icons i:hover {
            color: #2dc3ec;
        }
        .section-title {
            font-size: 2rem;
            font-weight: bold;
            color: #ffffff;
        }
        .hero-title {
            font-size: 3rem;
            font-weight: 600;
            color: #ffffff;
        }
        .hero-subtitle {
            font-size: 1.25rem;
            color: #ffffff;
        }
        .feature-image {
            border-radius: 15px;
            transition: transform 0.3s ease;
        }
    </style>
</head>
<body class="bg-dark text-light">
    <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
        <div class="container">
            <a class="navbar-brand" href="#">Dribbble Clone</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav ms-auto">
                    <li class="nav-item">
                        <a class="nav-link" href="#home">Home</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#about">About</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#features">Features</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#contact">Contact</a>
                    </li>
                    <li class="nav-item">
                        <a href="#signup" class="btn btn-signup ms-2">Sign Up</a>
                    </li>
                </ul>
            </div>
        </div>
    </nav>

    <section class="hero-section text-center">
        <div class="container">
            <h1 class="hero-title">Charting Your Next Milestone</h1>
            <p class="hero-subtitle">Your Journey to Success Begins Here</p>
            <img src="pic 1.png" width="300px" height="300px" alt="Travel" class="rounded-circle">
            <p>Setting New Standards for Growth and Progress</p>
        </div>
    </section>

    <section class="py-4 bg-dark">
        <div class="container">
            <h2 class="section-title text-center mb-4">Mapping Your Next Step</h2>
            <div class="row g-4">
                <div class="col-6 col-md-4 col-lg-3">
                    <img src="pic 5.png" class="img-fluid feature-image" alt="pic 1">
                </div>
                <div class="col-6 col-md-4 col-lg-3">
                    <img src="pic 6.png" class="img-fluid feature-image" alt="pic 2">
                </div>
                <div class="col-6 col-md-4 col-lg-3">
                    <img src="pic 3.png" class="img-fluid feature-image" alt="pic 3">
                </div>
                <div class="col-6 col-md-4 col-lg-3">
                    <img src="pic 7.png" class="img-fluid feature-image" alt="pic 4">
                </div>
            </div>
        </div>
    </section>

    <footer class="bg-secondary text-light py-3">
        <div class="container text-center">
            <p>Designed and developed by MIRZHA FATHIMA S</p>
            <div class="social-icons">
                <a href="#"><i class="bi bi-facebook"></i></a>
                <a href="#"><i class="bi bi-twitter"></i></a>
                <a href="#"><i class="bi bi-instagram"></i></a>
            </div>
        </div>
    </footer>

    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/bootstrap-icons/1.10.5/font/bootstrap-icons.min.css"></script>
</body>
</html>
```


## OUTPUT:
![alt text](<output 1.png>)
![alt text](<output 2.png>)

## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
