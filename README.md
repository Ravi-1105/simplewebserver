# EX01 Developing a Simple Webserver
## Date:
29.03.2024
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
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-QWTKZyjpPEjISv5WaRU9OFeRpok6YctnYmDr5pNlyT2bRjXh0JMhjY6hW+ALEwIH" crossorigin="anonymous">
    <div style="display: flex; margin: 100px;">
        <div class="card" style="margin: 10px; width: 25rem;">
        <img src="c:\Users\admin\Documents\Saveetha\WebDevelopment\Dassault-Rafale.webp" class="card-img-top" alt="...">
        <div class="card-body">
          <h5 class="card-title">Dassault-Rafale</h5>
          <p class="card-text">The Dassault Rafale (French pronunciation: [ʁafal], literally meaning "gust of wind",[2] or "burst of fire" in a more military sense)[3] is a French twin-engine, canard delta wing, multirole fighter aircraft designed and built by Dassault Aviation.</p>
          <a href="https://en.wikipedia.org/wiki/Dassault_Rafale" class="btn btn-primary">Read More</a>
        </div>
        </div>
        <div class="card" style="margin: 10px;width: 25rem;">
            <img src="c:\Users\admin\Documents\Saveetha\WebDevelopment\F-22_Raptor.jpg" class="card-img-top" alt="...">
            <div class="card-body">
              <h5 class="card-title">F-22</h5>
              <p class="card-text">The Lockheed Martin/Boeing F-22 Raptor is an American single-seat, twin-engine, supersonic all-weather stealth fighter aircraft developed for the United States Air Force (USAF).</p>
              <a href="https://www.lockheedmartin.com/en-us/products/f-22.html" class="btn btn-primary">Read More</a>
            </div>
        </div>
        <div class="card" style="margin: 10px;width: 25rem;">
          <img src="c:\Users\admin\Documents\Saveetha\WebDevelopment\SU-57-1.webp" class="card-img-top" alt="...">
          <div class="card-body">
            <h5 class="card-title">Su-57</h5>
            <p class="card-text">The Sukhoi Su-57 is a twin-engine stealth multirole fighter aircraft developed by Sukhoi. It is the product of the PAK FA programme, which was initiated in 1999 as a more modern and affordable alternative to the MFI.</p>
            <a href="https://en.wikipedia.org/wiki/Sukhoi_Su-57" class="btn btn-primary">Read More</a>
          </div>
      </div>
    </div>
</body>
</html>

## OUTPUT:
![alt text](ex01-op-1.png)

## RESULT:
The program for implementing simple webserver is executed successfully.
