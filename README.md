# Project Responsive Web Design using Bootstrap
# Date: 28.05.2026
# AIM:
To create a simplified clone of Dribbble (https://dribbble.com/) landing page.

# DESIGN STEPS:
## Step 1:
Clone the repository from GitHub.

## Step 2:
Create Django Admin project.

## Step 3:
Create a New App under the Django Admin project.

## Step 4:
Insert the necessary CSS and JavaScript files as external in order to use Bootstrap.

## Step 5:
Create a HTML file and include the needed Bootstrap components.

## Step 6:
Publish the website in the LocalHost.
 
# PROGRAM :
```
index.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Dribbble Clone</title>

    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
</head>

<body>

<!-- Navbar -->

<nav class="navbar navbar-expand-lg navbar-dark bg-dark">

    <div class="container">

        <a class="navbar-brand fw-bold" href="#">
            Dribbble 
        </a>

        <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#menu">

            <span class="navbar-toggler-icon"></span>

        </button>

        <div class="collapse navbar-collapse" id="menu">

            <ul class="navbar-nav ms-auto">

                <li class="nav-item">
                    <a class="nav-link" href="#">Home</a>
                </li>

                <li class="nav-item">
                    <a class="nav-link" href="#">Designs</a>
                </li>

                <li class="nav-item">
                    <a class="nav-link" href="#">Artists</a>
                </li>

                <li class="nav-item">
                    <a class="nav-link" href="#">Contact</a>
                </li>

            </ul>

        </div>

    </div>

</nav>

<div class="container text-center py-5">

    <h1 class="display-4 fw-bold">
        Discover Creative Designers
    </h1>

    <p class="lead">
        Explore amazing UI and web inspirations.
    </p>

    <button class="btn btn-primary btn-lg">
        Explore
    </button>

</div>

<div class="container my-5">

    <div class="row g-4">

        <div class="col-md-4">

            <div class="card">

                <img src="https://picsum.photos/300/200?1" class="card-img-top">

                <div class="card-body">

                    <h5 class="card-title">
                        Mobile UI
                    </h5>

                    <p class="card-text">
                        Creative mobile interface designs.
                    </p>

                </div>

            </div>

        </div>

        <div class="col-md-4">

            <div class="card">

                <img src="https://picsum.photos/300/200?2" class="card-img-top">

                <div class="card-body">

                    <h5 class="card-title">
                        Website Design
                    </h5>

                    <p class="card-text">
                        Modern responsive web layouts.
                    </p>

                </div>

            </div>

        </div>

        <div class="col-md-4">

            <div class="card">

                <img src="https://picsum.photos/300/200?3" class="card-img-top">

                <div class="card-body">

                    <h5 class="card-title">
                        Dashboard UI
                    </h5>

                    <p class="card-text">
                        Professional admin dashboards.
                    </p>

                </div>

            </div>

        </div>

    </div>

</div>

<footer class="bg-dark text-white text-center p-3">

    Created by Deetchana

</footer>

<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>

</body>
</html>
```

# OUTPUT:

![alt text](<Screenshot (124).png>)
![alt text](<Screenshot (125).png>)
![alt text](<Screenshot (126).png>)
![alt text](<Screenshot (128).png>)
![alt text](<Screenshot (129).png>)

# RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
