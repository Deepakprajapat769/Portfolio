# Deepak Prajapat's Portfolio

This repository contains the source code for Deepak Prajapat's personal portfolio website. Below are the details of the HTML, CSS, and additional JavaScript used to create the site.

## HTML

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Deepak Prajapat</title>
    <link href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" rel="stylesheet">
    <link rel="stylesheet" href="styles.css">
    <style>
        body {
            perspective: 1000px;
        }
        .card {
            transition: transform 0.5s;
            transform-style: preserve-3d;
        }
        .card:hover {
            transform: rotateY(10deg) rotateX(10deg);
        }
    </style>
</head>
<body>
    <header class="bg-dark text-white text-center py-5">
        <h1>Deepak Prajapat</h1>
        <nav class="navbar navbar-expand-lg navbar-dark">
            <div class="collapse navbar-collapse justify-content-center">
                <ul class="navbar-nav">
                    <li class="nav-item"><a class="nav-link" href="#about">About Me</a></li>
                    <li class="nav-item"><a class="nav-link" href="#projects">Projects</a></li>
                    <li class="nav-item"><a class="nav-link" href="#contact">Contact</a></li>
                </ul>
            </div>
        </nav>
    </header>
    <section id="about" class="container my-5">
        <h2>About Me</h2>
        <p>Brief description about yourself and your background in technology.</p>
    </section>
    <section id="projects" class="container my-5">
        <h2>Projects</h2>
        <div class="row">
            <!-- Repeat this block for each project -->
            <div class="col-md-4">
                <div class="card mb-4">
                    <img src="public/assets/06_mclaren_senna_black_livery_7_resized.jpg" class="card-img-top" alt="Project Image">
                    <div class="card-body">
                        <h5 class="card-title">Shoper Service</h5>
                        <p class="card-text">E-Commmerce Preoject are used Technology is MERN.</p>
                        <a href="" class="btn btn-primary">View Project</a>
                    </div>
                </div>
            </div>
        </div>
    </section>
    <section id="contact" class="container my-5">
        <h2>Contact</h2>
        <p>Email: Deepprajapat@gmail.com</p>
        <p>Mobile: +91 7694994790</p>
    </section>
    <footer class="bg-dark text-white text-center py-3">
        <p>&copy; 2024 Your Name</p>
    </footer>
    <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.5.4/dist/umd/popper.min.js"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
</body>
</html>
