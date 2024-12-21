# Project Responsive Web Design using Bootstrap
# Date: 07/12/2024
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

HOME PAGE:

~~~
<html
<head>
    <title>Responsive Web Design with Image Popup and Details</title>
    <link href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" rel="stylesheet">
    <link href="C:\Users\admin\OneDrive\Desktop\web development\project\project.css" rel="stylesheet">
</head>
<body>
    <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
        <a class="navbar-brand mx-auto d-flex align-items-center" href="#">
            <img src="c:\Users\admin\OneDrive\Desktop\web development\project\pic 17.webp" alt="Logo" width="50" height="50" class="mr-2">
            <span class="display-4" style="font-size: 2rem; text-align: center;">Urban Threads</span>
        </a>
        <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav">
            <span class="navbar-toggler-icon"></span>
        </button>
        
        <div class="collapse navbar-collapse " id="navbarNav">
            <ul class="navbar-nav ml-auto">
                <li class="nav-item"><a class="nav-link" href="#">Home</a></li>
                <li class="nav-item"><a class="nav-link" href="C:\Users\admin\OneDrive\Desktop\web development\project\about.html">About</a></li>
                <li class="nav-item"><a class="nav-link" href="C:\Users\admin\OneDrive\Desktop\web development\project\contactus.html">Contact</a></li>
                <li class="nav-item"><a class="nav-link" href="C:\Users\admin\OneDrive\Desktop\web development\project\signin.html">Sign in</a></li>
                <li class="nav-item"><a class="nav-link" href="C:\Users\admin\OneDrive\Desktop\web development\project\signup.html">Sign Up</a></li>
            </ul>
            
        </div>
    
   </nav>
   <header class="bg-dark text-white text-center py-5 " style="margin-bottom: 30px;">
    <div class="container">
      <h1>Welcome to Urban Threads</h1>
      <p style="margin-bottom: 20px;">Threads That Define the Streets</p>
    </div>
  </header>

    <div class="container">
        <div class="row">
            <div class="col-md-3 mb-3" style="color: black;">
                <div class="card">
                    <img src="c:\Users\admin\OneDrive\Desktop\web development\project\pic 1.jpg" 
                         class="card-img-top popup-image" 
                         data-title="Highlander" 
                         data-description="Highlander Men Blue Straight fit Stretchable Jeans"
                         data-cost="$49.99"
                         data-link="C:\Users\admin\OneDrive\Desktop\web development\project\buy.html" 
                         alt="Product 1">
                    <div class="card-body">
                        <h5 class="card-title">Highlander</h5>
                        <p class="card-text">Men's Blue fit Jeans</p>
                    </div>
                </div>
            </div>
            <div class="col-md-3 mb-3">
                <div class="card" style="color: black;">
                    <img src="c:\Users\admin\OneDrive\Desktop\web development\project\pic 4.webp" 
                         class="card-img-top popup-image" 
                         data-title="Ketch Men Blue Tapered Fit Mildly Distressed Jeans" 
                         data-description="Ketch"
                         data-cost="$99.99"
                         data-link="C:\Users\admin\Desktop\web development\project\buy.html" 
                         alt="Product 2">
                    <div class="card-body">
                        <h5 class="card-title"> Ketch</h5>
                        <p class="card-text">Men's Tapered Jeans</p>
                    </div>
                </div>
            </div>
            <div class="col-md-3 mb-3">
                <div class="card" style="color: black;">
                    <img src="c:\Users\admin\OneDrive\Desktop\web development\project\pic 5.webp" 
                         class="card-img-top popup-image" 
                         data-title="Highlander" 
                         data-description="Highlander Men Black Slim Fit Highly Distressed Jeans"
                         data-cost="$29.99"
                         data-link="C:\Users\admin\Desktop\web development\project\buy.html" 
                         alt="Product 3">
                    <div class="card-body">
                        <h5 class="card-title">Highlander</h5>
                        <p class="card-text">Men's Slim fit Jeans</p>
                    </div>
                </div>
            </div>
            <div class="col-md-3 mb-3">
                <div class="card" style="color: black;">
                    <img src="c:\Users\admin\OneDrive\Desktop\web development\project\pic 6.webp" 
                         class="card-img-top popup-image" 
                         data-title="Highlander" 
                         data-description="Highlander Men Black Skinny Fit Clean Look Jeans"
                         data-cost="$29.99"
                         data-link="C:\Users\admin\Desktop\web development\project\buy.html" 
                         alt="Product 3">
                    <div class="card-body">
                        <h5 class="card-title">Highlander</h5>
                        <p class="card-text">Men Skinny Fit Jeans</p>
                    </div>
                </div>
            </div>
            <div class="col-md-3 mb-3">
                <div class="card" style="color: black;">
                    <img src="c:\Users\admin\OneDrive\Desktop\web development\project\pic 3.jpg" 
                         class="card-img-top popup-image" 
                         data-title="Locomotive" 
                         data-description="Locomotive Men Blue Solid Denim Jackets"
                         data-cost="$29.99"
                         data-link="C:\Users\admin\Desktop\web development\project\buy.html" 
                         alt="Product 3">
                    <div class="card-body">
                        <h5 class="card-title">Locomotive</h5>
                        <p class="card-text">Blue Denim</p>
                    </div>
                </div>
            </div>
            <div class="col-md-3 mb-3">
                <div class="card" style="color: black;">
                    <img src="c:\Users\admin\OneDrive\Desktop\web development\project\pic 7.webp" 
                         class="card-img-top popup-image" 
                         data-title="Highlander" 
                         data-description="Highlander Men White Solid Bomber Jackets"
                         data-cost="$29.99"
                         data-link="C:\Users\admin\Desktop\web development\project\buy.html" 
                         alt="Product 3">
                    <div class="card-body">
                        <h5 class="card-title">Highlander</h5>
                        <p class="card-text">Solid Bomber Jacketsb</p>
                    </div>
                </div>
            </div>
            <div class="col-md-3 mb-3">
                <div class="card" style="color: black;">
                    <img src="c:\Users\admin\OneDrive\Desktop\web development\project\pic 8.jpg" 
                         class="card-img-top popup-image" 
                         data-title="Ketch" 
                         data-description="Ketch Men Green Solid Denim Jackets"
                         data-cost="$29.99"
                         data-link="C:\Users\admin\Desktop\web development\project\buy.html" 
                         alt="Product 3">
                    <div class="card-body">
                        <h5 class="card-title">Ketch</h5>
                        <p class="card-text">Solid Denim Jackets</p>
                    </div>
                </div>
            </div>
            <div class="col-md-3 mb-3">
                <div class="card" style="color: black;">
                    <img src="c:\Users\admin\OneDrive\Desktop\web development\project\pic 9.webp" 
                         class="card-img-top popup-image" 
                         data-title="Locomotive" 
                         data-description="Locomotive Men Grey Solid Denim Jackets"
                         data-cost="$29.99"
                         data-link="C:\Users\admin\Desktop\web development\project\buy.html" 
                         alt="Product 3">
                    <div class="card-body">
                        <h5 class="card-title">Locomotive</h5>
                        <p class="card-text">Solid Denim Jackets</p>
                    </div>
                </div>
            </div>
            <div class="col-md-3 mb-3">
                <div class="card" style="color: black;">
                    <img src="c:\Users\admin\OneDrive\Desktop\web development\project\pic 10.avif" 
                         class="card-img-top popup-image" 
                         data-title="CRISTOFANO" 
                         data-description="Round-Toe Penny Loafers"
                         data-cost="$29.99"
                         data-link="C:\Users\admin\Desktop\web development\project\buy.html" 
                         alt="Product 3">
                    <div class="card-body">
                        <h5 class="card-title">CRISTOFANO</h5>
                        <p class="card-text">Loafers</p>
                    </div>
                </div>
            </div>
            <div class="col-md-3 mb-3">
                <div class="card" style="color: black;">
                    <img src="c:\Users\admin\OneDrive\Desktop\web development\project\pic 11.avif" 
                         class="card-img-top popup-image" 
                         data-title="Nike"
                         data-description="Men Revolution 7 Running Shoes"
                         data-cost="$29.99"
                         data-link="C:\Users\admin\Desktop\web development\project\buy.html" 
                         alt="Product 3">
                    <div class="card-body">
                        <h5 class="card-title">Nike</h5>
                        <p class="card-text">Sneakers
                        </p>
                    </div>
                </div>
            </div>
            <div class="col-md-3 mb-3">
                <div class="card" style="color: black;">
                    <img src="c:\Users\admin\OneDrive\Desktop\web development\project\pic 12.avif" 
                         class="card-img-top popup-image" 
                         data-title="RED TAPE" 
                         data-description="Men Knitted Lace-Fastening Sneakers with Round Toes"
                         data-cost="$29.99"
                         data-link="C:\Users\admin\Desktop\web development\project\buy.html" 
                         alt="Product 3">
                    <div class="card-body">
                        <h5 class="card-title"> RED TAPE</h5>
                        <p class="card-text">Sneakers</p>
                    </div>
                </div>
            </div>
            <div class="col-md-3 mb-3">
                <div class="card" style="color: black;">
                    <img src="c:\Users\admin\OneDrive\Desktop\web development\project\pic 13.avif" 
                         class="card-img-top popup-image" 
                         data-title="MACTREE" 
                         data-description="Men Round-Toe Slip-On Loafers"
                         data-cost="$29.99"
                         data-link="C:\Users\admin\Desktop\web development\project\buy.html" 
                         alt="Product 3">
                    <div class="card-body">
                        <h5 class="card-title">MACTREE</h5>
                        <p class="card-text">Loafers</p>
                    </div>
                </div>
            </div>
            <div class="col-md-3 mb-3">
                <div class="card" style="color: black;">
                    <img src="c:\Users\admin\OneDrive\Desktop\web development\project\pic 13.webp" 
                         class="card-img-top popup-image" 
                         data-title="Titan" 
                         data-description="Titan Neo Splash Blue Dial Quartz Multifunction Stainless Steel Strap watch for Men"
                         data-cost="$29.99"
                         data-link="C:\Users\admin\Desktop\web development\project\buy.html" 
                         alt="Product 3">
                    <div class="card-body">
                        <h5 class="card-title">Titan</h5>
                        <p class="card-text">Titan Neo Splash Blue Dial Quartz Multifunction Stainless Steel Strap watch for Men</p>
                    </div>
                </div>
            </div>
            <div class="col-md-3 mb-3">
                <div class="card" style="color: black;">
                    <img src="c:\Users\admin\OneDrive\Desktop\web development\project\pic 14.webp" 
                         class="card-img-top popup-image" 
                         data-title="Sonata" 
                         data-description="Sonata Poze Quartz Analog Black Dial Leather Strap Watch for Men"
                         data-cost="$29.99"
                         data-link="C:\Users\admin\Desktop\web development\project\buy.html" 
                         alt="Product 3">
                    <div class="card-body">
                        <h5 class="card-title">Sonata</h5>
                        <p class="card-text">Sonata Pose Quartz</p>
                    </div>
                </div>
            </div>
            <div class="col-md-3 mb-3">
                <div class="card" style="color: black;">
                    <img src="c:\Users\admin\OneDrive\Desktop\web development\project\pic 15.webp" 
                         class="card-img-top popup-image" 
                         data-title="Titan" 
                         data-description="Titan Quartz Analog Black Dial Leather Strap Watch for Men"
                         data-cost="$29.99"
                         data-link="C:\Users\admin\Desktop\web development\project\buy.html" 
                         alt="Product 3">
                    <div class="card-body">
                        <h5 class="card-title">Titan</h5>
                        <p class="card-text">Quartz Analog</p>
                    </div>
                </div>
            </div>
            <div class="col-md-3 mb-3">
                <div class="card" style="color: black;">
                    <img src="c:\Users\admin\OneDrive\Desktop\web development\project\pic 16.jpg" 
                         class="card-img-top popup-image" 
                         data-title="Casio" 
                         data-description="Casio Stainless Steel Men Vintage Digital"
                         data-cost="$29.99"
                         data-link="C:\Users\admin\Desktop\web development\project\buy.html3" 
                         alt="Product 3">
                    <div class="card-body">
                        <h5 class="card-title">Casio</h5>
                        <p class="card-text">Casio Stainless Steel Men Vintage Digital</p>
                    </div>
                </div>
            </div>
            
        </div>
    </div>

    <footer>
        <p> Deepak</p><br>

        <p>&copy; 2024 Urban Traders. All Rights Reserved.</p>
    </footer>

    <div class="modal fade" id="imageModal" tabindex="-1" role="dialog" aria-labelledby="imageModalLabel" aria-hidden="true">
        <div class="modal-dialog modal-lg" role="document">
            <div class="modal-content">
                <div class="modal-header">
                    <h5 class="modal-title" id="modalTitle">Product Details</h5>
                    <button type="button" class="close" data-dismiss="modal" aria-label="Close">
                        <span aria-hidden="true">&times;</span>
                    </button>
                </div>
                <div class="modal-body text-center">
                    
                    <img id="modalImage" src="" alt="Product Image" class="img-fluid mb-3">
                   
                    <p id="modalDescription" class="text-muted"></p>
                    <h4 id="modalCost" class="text-success"></h4>
                  
                    <a id="modalLink" href="#" target="_blank" class="btn btn-primary">Buy Now</a>
                </div>
            </div>
        </div>
    </div>
    <script src="C:\Users\admin\OneDrive\Desktop\web development\project\project.js"></script>

    <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.4.4/dist/umd/popper.min.js"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
    
</body>
</html>
~~~
project.js
~~~
document.querySelectorAll('.popup-image').forEach(function(img) {
    img.addEventListener('click', function() {
        const modalImage = document.getElementById('modalImage');
        const modalTitle = document.getElementById('modalTitle');
        const modalDescription = document.getElementById('modalDescription');
        const modalCost = document.getElementById('modalCost');
        const modalLink = document.getElementById('modalLink');

        modalImage.src = this.src; 
        modalTitle.textContent = this.dataset.title; 
        modalDescription.textContent = this.dataset.description; 
        modalCost.textContent = this.dataset.cost; 
        modalLink.href = this.dataset.link; 

        $('#imageModal').modal('show');
    });
});
~~~

ABOUT:

~~~
<html>
    <head>
        <title>About</title>
        <style>
            body {
                background-image: url('c:/Users/admin/OneDrive/Desktop/web development/project/about.avif');
                background-size: cover;  
                background-position: center; 
                background-attachment: fixed;  
                margin: 0;
                font-family: Arial, sans-serif; 
                color: white;
            }
            
            .about-section {
                padding: 50px;
                background: rgba(0, 0, 0, 0.7); 
                border-radius: 10px;
                margin: 50px auto;
                max-width: 800px; 
                box-shadow: 0 8px 15px rgba(0, 0, 0, 0.3); 
            }
            
            h1, h3 {
                color: #ffcc00; 
            }
            
            p, ul {
                color: #f0f0f0; 
            }
            
            ul {
                padding-left: 20px; 
            }

            footer {
                background: #000;
                padding: 15px 0;
            }
        </style>
    </head>
<body>
    <div class="about-section text-center">
        <div class="container">
            <h1 class="mb-4" style="text-align: center;">About Us</h1>
            <p class="lead mb-5">
                Welcome to <strong>UrbanThreads</strong>, where creativity meets innovation. 
                We are passionate about crafting solutions that inspire, engage, and transform. 
                Whether you’re here to learn about our journey, explore our projects, or connect with us, you’ve come to the right place.
            </p>
            <div class="row">
                <div class="col-md-6 text-left">
                    <h3>Who We Are</h3>
                    <p>
                        We are a team of dedicated professionals with a shared mission to deliver excellence. 
                        From innovative designs to seamless functionality, we specialize in bringing ideas to life.
                    </p>
                    <h3>Our Vision</h3>
                    <p>
                        To create a world where technology and creativity coexist harmoniously, empowering businesses and individuals to achieve their goals.
                    </p>
                    <h3>Why Choose Us?</h3>
                    <ul>
                        <li>Expertise in cutting-edge technologies</li>
                        <li>Customer-centric approach</li>
                        <li>Commitment to quality and innovation</li>
                    </ul>
                </div>
            </div>
        </div>
    </div>

    <!-- Footer -->
    <footer class="bg-dark text-white text-center py-3" style="text-align: center;">
        <p>&copy; 2024 Urban Threads. All rights reserved.</p>
    </footer>
</body>
</html>

~~~
CONTACT
~~~
<html>
<head>
    <title>Contact Us</title>
    <link href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" rel="stylesheet">
    <style>
        body {
            margin: 0;
            padding: 0;
            background-color: #f8f9fa;
            font-family: Arial, sans-serif;
        }

        .navbar-logo-container {
            display: flex;
            justify-content: center; /* Centers the logo horizontally */
            align-items: center; /* Centers the logo vertically */
            height: 20vh; /* Sets the height of the logo container */
        }

        .navbar-brand {
            display: flex;
            align-items: center;
            text-align: center;
            font-size: 1.5rem;
            text-decoration: none;
        }

        .navbar-brand img {
            margin-right: 10px; 
            border-radius: 50%; 
        }

        .contact-container {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            align-items: flex-start; /* Align items at the top */
            background-color: white;
            padding: 40px;
            border-radius: 10px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
            max-width: 900px;
            width: 100%;
            margin: auto;
            gap: 20px; /* Adds space between flex children */
        }

        .contact-form, .contact-info {
            flex: 1;
            margin: 10px;
        }

    </style>
</head>
<body>

    <div class="navbar-logo-container">
        <a class="navbar-brand mx-auto d-flex align-items-center" href="#">
            <img src="c:\Users\admin\OneDrive\Desktop\web development\project\pic 17.webp" alt="Logo" width="80" height="80">
            <span class="display-4" style="font-size: 2rem;">Urban Threads</span>
        </a>
    </div>

    <div class="contact-container">
        <div class="contact-form">
            <h3 class="mb-4">Send Us a Message</h3>
            <form>
                <div class="form-group">
                    <label for="name">Full Name</label>
                    <input type="text" class="form-control" id="name" placeholder="Enter your full name" required>
                </div>
                <div class="form-group">
                    <label for="email">Email Address</label>
                    <input type="email" class="form-control" id="email" placeholder="Enter your email" required>
                </div>
                <div class="form-group">
                    <label for="message">Your Message</label>
                    <textarea class="form-control" id="message" rows="5" placeholder="Write your message" required></textarea>
                </div>
                <button type="submit" class="btn btn-primary btn-block">Submit</button>
            </form>
        </div>

        <div class="contact-info">
            <h3 class="mb-4">Get in Touch</h3>
            <p><strong>Phone:</strong> 9845715327</p>
            <p><strong>Email:</strong> UrbanThreads123@gmail.com</p>
            <h4 class="mt-4">Follow Us</h4>
          
        </div>
    </div>
</body>
</html>
~~~
SIGN IN
~~~
<html>
<head>
    <title>Sign In</title>
    <!-- Bootstrap CSS -->
    <link href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" rel="stylesheet">
    <style>
        body {
            margin: 0;
            padding: 0;
            display: flex;
            flex-direction: column; 
            justify-content: center;
            align-items: center;
            height: 100vh;            
            background-image: url('c:/Users/admin/OneDrive/Desktop/web development/project/signin.webp');
            background-size: cover;
            background-position: center;
            background-attachment: fixed;
            font-family: Arial, sans-serif;
            color: white;
        }

        .navbar-logo-container {
            text-align: center;
            margin-bottom: 20px; /* Adds space between the logo and the sign-in form */
        }

        .navbar-brand img {
            margin-bottom: 10px;
            border-radius: 50%;
        }

        .signin-container {
            background: white;
            padding: 40px;
            border-radius: 10px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
            max-width: 400px;
            width: 100%;
            text-align: center;
        }

        .signin-container h3 {
            margin-bottom: 20px;
            color: #333;
        }
    </style>
</head>
<body>
    <!-- Logo Section -->
    <div class="navbar-logo-container">
        <a class="navbar-brand" href="#">
            <img src="c:\Users\admin\OneDrive\Desktop\web development\project\pic 17.webp" alt="Logo" width="80" height="80">
            <span class="display-4" style="font-size: 2rem; color: #333;">Urban Threads</span>
        </a>
    </div>

    <!-- Sign-in Form Section -->
    <div class="signin-container">
        <h3>Sign In</h3>
        <form>
            <div class="form-group">
                <label for="email">Email Address</label>
                <input type="email" class="form-control" id="email" placeholder="Enter your email" required>
            </div>
            <div class="form-group">
                <label for="password">Password</label>
                <input type="password" class="form-control" id="password" placeholder="Enter your password" required>
            </div>
            <button type="submit" class="btn btn-primary btn-block">Sign In</button>
            <p class="text-center mt-3">
                Don't have an account? <a href="signup.html">Sign Up</a>
            </p>
        </form>
    </div>

    <!-- JavaScript Libraries -->
    <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.4.4/dist/umd/popper.min.js"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
</body>
</html>
~~~
BUY PAGE:
~~~
<html>
<head>
    <title>Urban Threads - Buy Now</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f9f9f9;
            color: #333;
            margin: 0;
            padding: 0;
        }
        .container {
            max-width: 800px;
            margin: 50px auto;
            padding: 20px;
            background-color: #fff;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
            border-radius: 8px;
        }
        .product-image {
            max-width: 100%;
            border-radius: 8px;
        }
        .product-title {
            font-size: 24px;
            font-weight: bold;
            margin: 20px 0 10px;
        }
        .product-price {
            font-size: 20px;
            color: #28a745;
            font-weight: bold;
        }
        .product-description {
            margin: 15px 0;
            line-height: 1.6;
        }
        .form-group {
            margin: 15px 0;
        }
        label {
            font-weight: bold;
        }
        select, input[type="number"] {
            width: 100%;
            padding: 10px;
            margin-top: 5px;
            border: 1px solid #ccc;
            border-radius: 5px;
            font-size: 16px;
        }
        .btn-container {
            margin-top: 20px;
        }
        .btn {
            display: inline-block;
            padding: 10px 20px;
            font-size: 16px;
            font-weight: bold;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            text-decoration: none;
        }
        .btn-buy-now {
            background-color: #5a189a;
            color: white;
        }
        .btn-buy-now:hover {
            background-color: #3c096c;
        }
        .btn-add-to-cart {
            background-color: #6c757d;
            color: white;
            margin-left: 10px;
        }
        .btn-add-to-cart:hover {
            background-color: #5a6268;
        }
        footer {
            text-align: center;
            margin-top: 30px;
            font-size: 14px;
            color: #666;
        }
    </style>
</head>
<body>
    <header style="text-align: center;">
        <img src="c:\Users\admin\OneDrive\Desktop\web development\project\pic 17.webp" alt="Logo" width="50" height="50" class="mr-2">
        <h1>Urban Threads</h1>
    </header>
    <div class="container">
        <img src="c:\Users\admin\OneDrive\Desktop\web development\project\pic 1.jpg" alt="Product Image" class="product-image">
        <h1 class="product-title"> Highlander Blue Fit Jeans</h1>
        <p class="product-price">$200</p>
        

        <div class="form-group">
            <label for="size">Select Size:</label>
            <select id="size" name="size">
                <option value="S">Small</option>
                <option value="M">Medium</option>
                <option value="L">Large</option>
                <option value="XL">Extra Large</option>
            </select>
        </div>

        <div class="form-group">
            <label for="quantity">Quantity:</label>
            <input type="number" id="quantity" name="quantity" min="1" max="10" value="1">
        </div>

        <div class="btn-container">
            <a href="#" class="btn btn-buy-now">Buy Now</a>
            <a href="#" class="btn btn-add-to-cart">Add to Cart</a>
        </div>
    </div>

    <footer>
        &copy; 2024 Urban Threads. All Rights Reserved.
    </footer>
</body>
</html>
~~~

# OUTPUT:
HOME PAGE:
![Screenshot 2024-12-21 134010](https://github.com/user-attachments/assets/f1345cbe-e2eb-4070-a271-1338ac204d3b)

ABOUT :
![Screenshot 2024-12-21 134026](https://github.com/user-attachments/assets/bdf35f57-1553-4c03-912a-6d3c400e38bc)

CONTACT:
![Screenshot 2024-12-21 134043](https://github.com/user-attachments/assets/f331f4f9-a529-4c2b-89ee-8961f8bcc8c6)

SIGN IN:
  ![Screenshot 2024-12-21 134056](https://github.com/user-attachments/assets/d528e789-b78a-46ce-bd9d-965bf8526917)

  BUY:
  ![Screenshot 2024-12-21 134135](https://github.com/user-attachments/assets/0f82e18a-99c5-4d3b-86bd-c6b4f168d4ec)
  ![Screenshot 2024-12-21 134149](https://github.com/user-attachments/assets/8cc84136-18a5-4a6e-a4b8-c9dcffcb21de)





# RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
