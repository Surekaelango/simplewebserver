# EX01 Developing a Simple Webserver
## Date:30/03/24

## AIM:
To develop a simple webserver to serve html pages.

## DESIGN STEPS:
### Step 1: 
HTML content creation.

### Step 2:
Design of webserver workflow.

### Step 3:
Implementation using Python code.

### Step 4:
Serving the HTML pages.

### Step 5:
Testing the webserver.

## PROGRAM:
```
<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Document</title>
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.11.3/font/bootstrap-icons.min.css">
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet"
    integrity="sha384-QWTKZyjpPEjISv5WaRU9OFeRpok6YctnYmDr5pNlyT2bRjXh0JMhjY6hW+ALEwIH" crossorigin="anonymous">
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet"
    integrity="sha384-QWTKZyjpPEjISv5WaRU9OFeRpok6YctnYmDr5pNlyT2bRjXh0JMhjY6hW+ALEwIH" crossorigin="anonymous">
</head>
<style>
  a {
    padding: 10px;
    text-decoration: none;
    color: red;
    font-family: Arial;
    font-size: 18px;
  }

  a:hover {
    color: gray;
  }
</style>

<body>
  <div style="display:flex;">
    <div style="width: 25%;">
      <img style="width: 100%" src="image 1.png" alt="" />
    </div>
    <div style="width: 55%;padding-top: 13px;">
      <a href="">Home</a>
      <a href="">About</a>
      <a href="">Departments</a>
      <a href="">Life at SEC</a>
      <a href="">Admissions</a>
      <a href="">Placements</a>
    </div>
    <div style="width: 20%;padding-top: 8px;">
      <input style="width: 80%;
            height: 30px;
            
            background-size: contain;
            background-repeat: no-repeat;
            border-radius: 15px;
            padding-left: 40px;" type="text" placeholder="Search" />



    </div>
</div>
<div id="carouselExampleIndicators" class="carousel slide" data-bs-ride="carousel" data-bs-interval="2000">
  <div class="carousel-indicators">
    <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="0" class="active" aria-current="true" aria-label="Slide 1"></button>
    <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="1" aria-label="Slide 2"></button>
    <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="2" aria-label="Slide 3"></button>
  </div>
  <div class="carousel-inner">
    <div class="carousel-item active">
      <img src="1.png" class="d-block w-100" alt="...">
    </div>
    <div class="carousel-item">
      <img src="2.png" class="d-block w-100" alt="...">
    </div>
    <div class="carousel-item">
      <img src="3.png" class="d-block w-100" alt="...">
    </div>
  </div>
  <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide="prev">
    <span class="carousel-control-prev-icon" aria-hidden="true"></span>
    <span class="visually-hidden">Previous</span>
  </button>
  <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide="next">
    <span class="carousel-control-next-icon" aria-hidden="true"></span>
    <span class="visually-hidden">Next</span>
  </button>
</div>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"
      integrity="sha384-YvpcrYf0tY3lHB60NNkmXc5s9fDVZLESaAA55NDzOxhy9GkcIdslK1eN7N6jIeHz"
      crossorigin="anonymous"></script>

</body>

</html>
```


## OUTPUT:
![Screenshot (60)](https://github.com/Surekaelango/simplewebserver/assets/127727904/ae041ac2-7fcb-45ea-8237-dfc0fe54370e)

## RESULT:
The program for implementing simple webserver is executed successfully.
