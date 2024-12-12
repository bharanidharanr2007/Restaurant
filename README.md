# Ex.07 Restaurant Website
# Date:25/11/2024
# AIM:
To develop a static Restaurant website to display the food items and services provided by them.

# DESIGN STEPS:
## Step 1:
Requirement collection.

## Step 2:
Creating the layout using HTML and CSS.

## Step 3:
Updating the sample content.

## Step 4:
Choose the appropriate style and color scheme.

## Step 5:
Validate the layout in various browsers.

## Step 6:
Validate the HTML code.

## Step 7:
Publish the website in the given URL.

# PROGRAM:
```
HTML

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>MENU </title>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
</head>
<body>
  <!-- Navigation Bar -->
  <nav class="navbar navbar-expand-lg navbar-light bg-light">
    <div class="container-fluid">
      <a class="navbar-brand fw-bold" href="#">MENU</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav ms-auto">
          <li class="nav-item">
            <a class="nav-link active" href="#">Home</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">Explore</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">Sign Up</a>
          </li>
        </ul>
        <form class="d-flex ms-3">
          <input class="form-control me-2" type="search" placeholder="Search" aria-label="Search">
          <button class="btn btn-outline-primary" type="submit">Search</button>
        </form>
      </div>
    </div>
  </nav>

  <!-- Hero Section -->
  <section class="bg-primary text-white text-center py-5">
    <div class="container">
      <h1 class="display-4" style="color: aquamarine;">THE CHENNAI'S RESTUARENT</h1>
      <h4 class="display-4">Discover the world's top VEG & NON-VEG</h4>
      <p class="lead">WELCOME TO OUR RESTUARENT</p>
      <a href="#" class="btn btn-light btn-lg mt-3">EXPLORE</a>
    </div>
  </section>

  <!-- Content Section -->
  <section class="container my-5">
    <h2 class="text-center mb-4" style="color: red;">Explore Top FOODS</h2>
    <div class="row g-4">
      <!-- Placeholder Cards -->
      <div class="col-md-4">
        <div class="card">
          <img src="Chicken-Chettinad-resized.avif" class="card-img-top" alt="Design">
          <div class="card-body">
            <h5 class="card-title">Chettinad-Chicken</h5>
            <p class="card-text">amt=150 rupee</p>
          </div>
        </div>
      </div>
      <div class="col-md-4">
        <div class="card">
          <img src="dosa-016d40a3bafd4a1-resized.avif" class="card-img-top" alt="Design">
          <div class="card-body">
            <h5 class="card-title">Tamil Nadu-DOSA</h5>
            <p class="card-text">amt=40 rupee</p>
          </div>
        </div>
      </div>
      <div class="col-md-4">
        <div class="card">
          <img src="Idli-resize.avif" class="card-img-top" alt="Design">
          <div class="card-body">
            <h5 class="card-title">Tamil Nadu-IDLY</h5>
            <p class="card-text">amt=30 rupee</p>
          </div>
        </div>
      </div>
      <div class="col-md-4">
        <div class="card">
          <img src="Kootu-resized.avif" class="card-img-top" alt="Design">
          <div class="card-body">
            <h5 class="card-title">Kootu</h5>
            <p class="card-text">amt= 30rupee</p>
          </div>
        </div>
      </div>
      <div class="col-md-4">
        <div class="card">
          <img src="Lemon-Rice-resized.avif" class="card-img-top" alt="Design">
          <div class="card-body">
            <h5 class="card-title">Lemon Rice</h5>
            <p class="card-text">amt= 30rupee</p>
          </div>
        </div>
      </div>
      <div class="col-md-4">
        <div class="card">
          <img src="Mutton-Kola-Urundai-resized.avif" class="card-img-top" alt="Design">
          <div class="card-body">
            <h5 class="card-title">Mutton-Kola-Urundai</h5>
            <p class="card-text">amt= 50rupee</p>
          </div>
        </div>
      </div>
      <div class="col-md-4">
        <div class="card">
          <img src="paruppupay-8cd97c59911c135-resized.avif" class="card-img-top" alt="Design">
          <div class="card-body">
            <h5 class="card-title">Paruppupay</h5>
            <p class="card-text">amt= 40rupee</p>
          </div>
        </div>
      </div>
      <div class="col-md-4">
        <div class="card">
          <img src="pollachina-f828d27b903ca13-resized.avif" class="card-img-top" alt="Design">
          <div class="card-body">
            <h5 class="card-title">Pollachina</h5>
            <p class="card-text">amt= 60rupee</p>
          </div>
        </div>
      </div>
      <div class="col-md-4">
        <div class="card">
          <img src="pongal-res-766d9f558f36562-resized.avif" class="card-img-top" alt="Design">
          <div class="card-body">
            <h5 class="card-title">PONGAL</h5>
            <p class="card-text">amt= 50rupee</p>
          </div>
        </div>
      </div>
      <div class="col-md-4">
        <div class="card">
          <img src="Poriyal-resized.avif" class="card-img-top" alt="Design">
          <div class="card-body">
            <h5 class="card-title">Poriyal</h5>
            <p class="card-text">amt= 50rupee</p>
          </div>
        </div>
      </div>
      <div class="col-md-4">
        <div class="card">
          <img src="Puliyodarai-resized.avif" class="card-img-top" alt="Design">
          <div class="card-body">
            <h5 class="card-title">PULIYODARAI</h5>
            <p class="card-text">amt= 80rupee</p>
          </div>
        </div>
      </div>
      <div class="col-md-4">
        <div class="card">
          <img src="rasam-resi-3c48b50deb4c083-resized.avif" class="card-img-top" alt="Design">
          <div class="card-body">
            <h5 class="card-title">RASAM</h5>
            <p class="card-text">amt= 40rupee</p>
          </div>
        </div>
      </div>
    </div>
  </section>
  <center>
    <h4 style="color: rgb(13, 13, 14);"> Thanks for visiting our Hotel 
        visit again and enjoy
    </h4>
    <p style="color: blue;">Thandalam Queen land near to saveetha clg thandalam post  chennai 100003</p>
    <p style="color: rgb(2, 8, 14);"> For order or Enquirey <b style="color: aquamarine;">contact us:140-2340435</b></p>
   </center>
  <!-- Footer -->
  <footer class="bg-light text-center py-4">
    <div class="container">
      <p class="mb-1">© 2024 Dribbble Clone. All rights reserved.</p>
      <a href="#" class="text-dark me-3">About</a>
      <a href="#" class="text-dark me-3">Terms</a>
      <a href="#" class="text-dark">Privacy</a>
    </div>
  </footer>

  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>
  
</body>
</html>

```
```
CSS

@import url('https://fonts.googleapis.com/css2?family=Poppins:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&display=swap');

*{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: "Poppins", sans-serif;
}
#navbar{
    position: sticky;
    top: 0;
    left: 0;
    z-index: 100;
    padding: .5rem 5rem;
    box-shadow: 5px 5px 20px rgba(0,0,0,.5);
    background: black;
}
.navebar .navbar-brand
{
    font-size: 25px;
    font-weight: 800;
    color: #29f700 !important;
}
#navbarSupportedContent a{
    color: #fff;
    border-bottom: 2px solid transparent;
}
#navbarSupportedContent a:hover{
    border-bottom: 2px solid #29f700;
}
#navbarSupportedContent button{
    background: #29f700;
    width: 5rem;
    border-radius: 15px;
}
section{
    width: 100%;
    min-height: 100vh;
    display: flex;
    justify-content: center;
    align-items: center;
}
/***Home***/
#Home
{
    background: linear-gradient(rgba(0,0,0,.1),rgba(0,0,0,.1)),url(bg.jpg);
    background-size: cover;
    background-position: center;
}
#Home h1{
    font-size: 100px;
    color: #fff;
    letter-spacing:3px;
    font-family: Verdana, Geneva, Tahoma, sans-serif;
    text-shadow: 0px 1px 0px #ccc,
                 0px 2px 0px #ccc,
                 0px 3px 0px #ccc,
                 0px 4px 0px #ccc,
                 0px 5px 0px #ccc,
                 0px 6px 0px #ccc,
                 0px 7px 0px #ccc;
}


```
# OUTPUT:
![alt text](<Screenshot (102).png>)

![alt text](<Screenshot (103).png>)
# RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
