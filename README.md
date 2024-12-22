# Project Responsive Web Design using Bootstrap
# Date:
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
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Project</title>
    <link href="https://maxcdn.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" rel="stylesheet">
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Roboto', sans-serif;
            background-color:palevioletred;
            color: #333;
        }
        .jumbotron {
            background-color:pink;
            padding: 2rem 1rem;
            text-align: center;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
        }
        .card {
            margin-bottom: 1.5rem;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
        }
        footer {
            background-color: #333;
            color: white;
            padding: 1rem 0;
        }
        .container {
            max-width: 1200px;
           
        }
        div{
            background-color: palevioletred;
        
        }
        .info{
            margin-left: 30%;
            margin-right: 45%;
            border-width: 2px;
            border-style: dashed;
            padding: 10px;
        }
        .img{
            margin-left: 5%;
            height: 250px;
            width: 300px;
        }
        .img2{
            height: 250px;
            width: 300px;
            margin-left: 5%;
            margin-top: 5%;
        }
      
    </style>
</head>
<body>
    <nav class="navbar navbar-expand-lg navbar-secondary bg-dark">
        <a class="navbar-brand navbar">ChickenKitchen</a>
        <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
        </button>
        <nav class="collapse navbar-collapse" id="navbarNav">
            <ul class="navbar-nav ml-auto">
                <li class="nav-item">
                    <a class="nav-link" >Home</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link">About</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" >Services</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link">Contact</a>
                </li>
            </ul>
        </nav>
    </nav>

    <section class="jumbotron text-center">
        <h1 class="display-4">Welcome to ChickenKitchen</h1>
        <p class="lead">This is a Restaurant,"Where Every Bite is a Delight!".</p>
        <a class="btn btn-primary btn-lg"  role="button">Learn more</a>
        <a class="btn btn-success btn-lg"  role="button">Sign Up</a>
    </section>
    <center><section>
        <img src="C:\Users\admin\Pictures\Saved Pictures\chicken.jpg" class="img">
        <img src="C:\Users\admin\Pictures\Saved Pictures\chiFried.webp" class="img">
        <img src="c:\Users\admin\Pictures\Saved Pictures\legschi.jpg" class="img"><br>
        <img src="c:\Users\admin\Pictures\Saved Pictures\starter image.jpg"class="img2">
        <img src="c:\Users\admin\Pictures\Saved Pictures\manchurian.jpg" class="img2">
        <img src="c:\Users\admin\Pictures\Saved Pictures\wingschi.jpg" class="img2">
    </section></center>
    <section class="container mt-5">
        <h2>About Us</h2><br>
        <center><h4>Welcome to ChickenKitchen!</h4><br></center>
           <p> At ChickenKitchen, we believe that every meal should be a delicious adventure. Nestled in the heart of Coimbatore, our restaurant is dedicated to serving up the finest chicken dishes that will tantalize your taste buds and leave you craving for more.
            We take pride in our commitment to quality, ensuring that every bite you take is a testament to our dedication to delicious food and exceptional service. Whether you're dining in with us, picking up a meal to go, or having us cater your next event, we strive to exceed your expectations and make every visit to ChickenKitchen a delightful experience.

          <br>  Join us at ChickenKitchen, where great food and great company come together. We can't wait to serve you!   </p>
    </section>

    <section  class="container mt-5">
        <h2>Our Services</h2>
        <div class="row">
            <div class="col-md-4">
                <div class="card">
                    <div class="card-body">
                        <h5 class="card-title">Private Events:</h5>
                        <p class="card-text">Host your next event at ChickenKitchen. We offer private dining areas and event packages to accommodate your needs, whether it's a birthday celebration, business meeting, or any other special occasion.</p>
                    </div>
                </div>
            </div>
            <div class="col-md-4">
                <div class="card">
                    <div class="card-body">
                        <h5 class="card-title">Dine-In Experience:</h5>
                        <p class="card-text">Enjoy our cozy and vibrant ambiance, perfect for family dinners, friendly gatherings, and romantic dates. Our attentive staff is here to make your dining experience enjoyable and memorable.</p>
                    </div>
                </div>
            </div>
            <div class="col-md-4">
                <div class="card">
                    <div class="card-body">
                        <h5 class="card-title">Takeout & Delivery:</h5>
                        <p class="card-text">Craving our delicious chicken dishes We offer convenient takeout and delivery services. Order online or give us a call, and we'll have your meal ready for pickup or delivered straight to your door..</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <section  class="container mt-5">
        <h2>Contact Us</h2>
        <p>
            We love to hear from our customers! Whether you have a question, feedback, or just want to say hello, feel free to reach out to us. Here's how you can get in touch:</p>
            
         <div class="info"> 📞 +91 1234567890<br>
            🌐 www.P<sup>4</sup>Restaurant.com<br>
            📍 00,Any st,Any city,123.
        </div> 

    </section><br>
    <footer class="text-center">
        &copy;CHICKENKITCHEN. All rights reserved.
    </footer>

    <!-- Bootstrap JS, Popper.js, and jQuery -->
    <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.5.4/dist/umd/popper.min.js"></script>
    <script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
</body>
</html>
```
# OUTPUT:

![project(web)](https://github.com/user-attachments/assets/a120b0fc-5337-44dd-9dbf-33881c99f3cc)
![project(web)ii](https://github.com/user-attachments/assets/bb1070f4-5d4d-4cc7-b723-cd85e47f54d4)
![project(web)iii](https://github.com/user-attachments/assets/62d3cbbf-57e4-4476-aa53-4350f1585129)

# RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
