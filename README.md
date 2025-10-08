# Project Responsive Web Design using Bootstrap
# Date: 08/10/2025
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
home.html
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>ShopEase - Online Shopping</title>

  
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">

  
  <style>
    body {
      scroll-behavior: smooth;
      font-family: 'Poppins', sans-serif;
    }

    .navbar-brand {
      font-weight: bold;
      font-size: 1.6rem;
      color: #ffc107 !important;
    }

    .nav-link {
      font-weight: 500;
      transition: 0.3s;
    }

    .nav-link:hover {
      color: #ffc107 !important;
    }

    
    .hero {
  background: linear-gradient(to right, #ffecd2, #fcb69f);
  padding-top: 60px;
  padding-bottom: 80px;
  text-align: center;
}

    .hero h1 {
      font-weight: 700;
      font-size: 2.8rem;
    }

    .hero p {
      font-size: 1.2rem;
      margin-bottom: 20px;
    }

    
    .card img {
      height: 250px;
      
    }

    .card-title {
      font-weight: 200;
    }

    .btn-dark:hover {
      background-color: #ffc107;
      color: black;
      border: none;
    }

    
    #about {
      background-color: #f8f9fa;
      padding: 60px 0;
    }

    
    #contact {
      padding: 60px 0;
    }

    footer {
      background-color: #212529;
      color: #fff;
      text-align: center;
      padding: 15px 0;
      margin-top: 50px;
    }

    footer strong {
      color: #ffc107;
    }
  </style>
</head>
<body>

  
  <nav class="navbar navbar-expand-lg navbar-dark bg-dark sticky-top">
    <div class="container">
      <a class="navbar-brand" href="#">ShopEase</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
        <span class="navbar-toggler-icon"></span>
      </button>

      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav ms-auto">
          <li class="nav-item"><a class="nav-link active" href="#home">Home</a></li>
          <li class="nav-item"><a class="nav-link" href="#products">Products</a></li>
          <li class="nav-item"><a class="nav-link" href="#about">About</a></li>
          <li class="nav-item"><a class="nav-link" href="#contact">Contact</a></li>
        </ul>
      </div>
    </div>
  </nav>

  
  <section id="home" class="hero">
    <div class="container">
      <h1>Welcome to EasyBuy</h1>
      <p>Your one-stop online store for fashion, gadgets, and more!</p>
      <a href="#products" class="btn btn-warning btn-lg">Shop Now</a>
    </div>
  </section>

  
  <section id="products" class="py-5">
    <div class="container text-center">
      <h2 class="mb-4">Featured Products</h2>
      <div class="row g-4">
        
        <div class="col-md-4">
          <div class="card shadow-sm h-100">
            <img src="airpod.webp" class="card-img-top" alt="Product 1">
            <div class="card-body">
              <h5 class="card-title">Stylish Headphones</h5>
              <p class="card-text">Enjoy rich sound with our wireless Bluetooth headphones.</p>
              <p class="fw-bold">Rs.2500</p>
              <a href="#" class="btn btn-dark">Add to Cart</a>
            </div>
          </div>
        </div>

        
        <div class="col-md-4">
          <div class="card shadow-sm h-100">
            <img src="shoe.webp" class="card-img-top" alt="Product 2">
            <div class="card-body">
              <h5 class="card-title">Trendy Sneakers</h5>
              <p class="card-text">Step out in style with our comfortable and modern sneakers.</p>
              <p class="fw-bold">799</p>
              <a href="#" class="btn btn-dark">Add to Cart</a>
            </div>
          </div>
        </div>

        
        <div class="col-md-4">
          <div class="card shadow-sm h-100">
            <img src="https://images.unsplash.com/photo-1526170375885-4d8ecf77b99f" class="card-img-top" alt="Product 3">
            <div class="card-body">
              <h5 class="card-title">Camera</h5>
              <p class="card-text">Track your fitness goals and stay connected on the go.</p>
              <p class="fw-bold">Rs.9999</p>
              <a href="#" class="btn btn-dark">Add to Cart</a>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>


  <section id="about">
    <div class="container text-center">
      <h2>About Us</h2>
      <p class="mt-3 mx-auto" style="max-width: 700px;">
        At EasyBuy, we bring you the latest fashion and tech products at the best prices.
        Our goal is to make your online shopping experience smooth, exciting, and reliable —
        offering premium quality products with excellent customer service.
      </p>
    </div>
  </section>


  <section id="contact" class="text-center">
    <div class="container">
      <h2>Contact Us</h2>
      <p class="mt-3">Need help or have questions? Reach us anytime.</p>
      <a href="mailto:support@shopease.com" class="btn btn-warning">Email Us</a>
    </div>
  </section>

  <footer>
    <p>Designed by <strong>Vanathi</strong> </p>
  </footer>

  
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>

</body>
</html>
```

# OUTPUT:
![alt text](<Screenshot 2025-10-08 204221.png>)
![alt text](<Screenshot 2025-10-08 204242.png>)
# RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
