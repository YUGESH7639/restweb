# Ex.07 Restaurant Website
## Date:12-12-2024

## AIM:
To develop a static Restaurant website to display the food items and services provided by them.

## DESIGN STEPS:

### Step 1:
Requirement collection.

### Step 2:
Creating the layout using HTML and CSS.

### Step 3:
Updating the sample content.

### Step 4:
Choose the appropriate style and color scheme.

### Step 5:
Validate the layout in various browsers.

### Step 6:
Validate the HTML code.

### Step 7:
Publish the website in the given URL.

## PROGRAM:
```
Home.html

<html>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title><b>Welcome to YUGI MESS</b></title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            text-align: center;
            background-image: url('BG.jpg');
            background-size: cover;
            background-attachment: fixed;
        }
        .banner {
            background-color: rgba(148, 145, 143, 0.9);
            padding: 15px;
            color: white;
        }
        .nav-links {
            list-style-type: none;
            padding: 0;
            background-color: #2a9d8f;
            margin: 0;
            overflow: hidden;
        }
        .nav-links li {
            display: inline;
            margin: 0;
        }
        .nav-links a {
            display: inline-block;
            padding: 8px 12px;
            color: rgb(34, 16, 16);
            text-decoration: none;
        }
        .nav-links a:hover {
            background-color: #0caded;
        }
        .welcome-section, .features-section {
            padding: 15px;
            background-color: rgba(223, 21, 21, 0.8);
            margin: 10px auto;
            width: 70%;
            border-radius: 8px;
        }
        footer {
            background-color: #264653;
            color: white;
            padding: 8px;
            position: relative;
            bottom: 0;
            width: 100%;
        }
        .food-images {
            display: flex;
            justify-content: center;
            gap: 8px;
            margin: 15px 0;
        }
        .food-images img {
            width: 180px;
            height: auto;
            border-radius: 8px;
        }
    </style>
</head>
<body>


    <!-- Header Section -->
    <div class="banner">
        <h1><b>Welcome to YUGI MEES</b></h1>
        <p>Experience the taste of excellence!</p>
    </div>

    <!-- Navigation Bar -->
    <ul class="nav-links">
        <li><a href="Home.html">Home</a></li>
        <li><a href="menu.html">Menu</a></li>
        <li><a href="administration.html">Administration</a></li>
        <li><a href="contact.html">Contact Us</a></li>
    </ul>

    <!-- Main Content Section -->
    <div class="welcome-section">
        <h2>ABOUT MESS </h2>
        <p>At YUGI MESS, Everything that we bring you is pure,</p>
        <P> delicious and authentic.</P>
        <P> At  YUGI MESS, we prepare only using the finest ingredients, following time-tested methods.</P>
        <P> Experience a perfect blend of timeless tradition and innovation in every bite.</p>
   

    <!-- Food Images Section -->
    <div class="food-images">
        <img src="D1.jpg" alt="Delicious Food 1">
        <img src="D2.jpg" alt="Delicious Food 2">
    </div>
    <br>
    <br>
    <br>
    <br>
    <br>

    <!-- Footer Section -->
    <footer>
        <p><b>&copy; DESIGNED BY: YUGESH M(24900164)</b></p>
    </footer>
</body>
</html>


Menu.html

<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Menu - Our Specialties</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            text-align: center;
            background-color: #f8f9fa;
        }
        h2 {
            background-color: #2a9d8f;
            color: white;
            padding: 20px;
        }
        table {
            width: 100%;
            max-width: 800px;
            margin: 20px auto;
            border-collapse: collapse;
        }
        th, td {
            padding: 10px;
            border: 1px solid #ddd;
            text-align: left;
        }
        img {
            width: 100px;
            height: auto;
            border-radius: 8px;
        }
        caption {
            font-size: 1.5em;
            margin: 10px 0;
        }
    </style>
</head>
<nav>
    <ul>
        <li><a href="#menu">Menu</a></li>
    </ul>
</nav>
<section id="menu">
    <h2>Our Menu</h2>
    <div class="menu-grid">
        
        <div class="menu-item">
            <h3><font color="red">CHICKEN GRAVY</font></h3>
            <img src="CG.jpg">
            <p><strong>RS.110</strong></p>
        
    </div>
        <div class="menu-item">
            <h3><font color="blue">MUTTON GRAVY</font></h3>
            <img src="MG.jpg">
            <p><strong>RS.130</strong></p>
        </div>
        <div class="menu-item">
            <h3><font color="yellow">FISH FRY</font></h3>
            <img src="FF.jpg">
            <p><strong>RS.90</strong></p>
        </div>
        <div class="menu-item">
            <h3><font color="aqua">BRIYANI</font></h3>
            <img src="briyani.jpg">
            <p><strong>RS.180</strong></p>
        </div>
        <div class="menu-item">
            <h3><font color="blue">NATTU KOZHI VARUVAL</font></h3>
            <img src="NV.jpg">
            <p><strong>RS.130</strong></p>
        </div>
        <div class="menu-item">
            <h3><font color="green">ICE CREAM</font></h3>
            <img src="IG.jpg">
            <p><strong>RS.250</strong></p>
        </div>
        <div class="menu-item">
            <h3><font color="violet">PODI IDLY</font></h3>
            <img src="ID.jpg">
            <p><strong>RS.30</strong></p>
        </div>
        <div class="menu-item">
            <h3><font color="golden">PODI DOSA</font></h3>
            <img src="PD.jpg">
            <p><strong>RS.65</strong></p>
        </div>
        <div class="menu-item">
            <h3><font color="red">IDIYAPPAM</font></h3>
            <img src="IDI.jpg">
            <p><strong>RS.40</strong></p>
        </div>
        <div class="menu-item">
            <h3><font color="black">CHAPPATHI ROLE</font></h3>
            <img src="CR.jpg">
            <p><strong>RS.60</strong></p>
        </div>
        <div class="menu-item">
            <h3><font color="red">KALAN</font></h3>
            <img src="KL.jpg">
            <p><strong>RS.60</strong></p>
        </div>
        <div class="menu-item">
            <h3><font color="green">FRESH JUICE</font></h3>
            <img src="FJ.jpg">
            <p><strong>RS.60</strong></p>
        </div>
    </div>
</section>


</body>
</html>

administration.html

<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Administration - Nourish Bistro</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            text-align: center;
            background-color: #f8f9fa;
        }
        .banner {
            background-color: #2a9d8f;
            padding: 20px;
            color: white;
        }
        .nav-links {
            list-style-type: none;
            padding: 0;
            background-color: #264653;
            margin: 0;
            overflow: hidden;
        }
        .nav-links li {
            display: inline;
        }
        .nav-links a {
            display: inline-block;
            padding: 10px 15px;
            color: white;
            text-decoration: none;
        }
        .nav-links a:hover {
            background-color: #2a9d8f;
        }
        .admin-section {
            padding: 20px;
        }
        .admin-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 20px;
            padding: 20px;
        }
        .admin-card {
            background-color: white;
            border: 1px solid #ddd;
            border-radius: 8px;
            padding: 15px;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
            text-align: center;
        }
        .admin-card img {
            width: 100px;
            height: 100px;
            border-radius: 50%;
            margin-bottom: 10px;
        }
        .admin-card h3 {
            font-size: 18px;
            margin: 10px 0;
        }
        .admin-card p {
            font-size: 14px;
            color: #555;
        }
        footer {
            background-color: #264653;
            color: white;
            padding: 10px;
            position: relative;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>
    <!-- Header Section -->
    <div class="banner">
        <h1>Meet Our Administration</h1>
        <p>The team yugi mess success</p>
    </div>

    <!-- Navigation Bar -->
    <ul class="nav-links">
        <li><a href="Home.html">Home</a></li>
        <li><a href="menu.html">Menu</a></li>
        <li><a href="administration.html">Administration</a></li>
        <li><a href="contact.html">Contact Us</a></li>
    </ul>

    <!-- Administration Section -->
    <div class="admin-section">
        <h2>Our Dedicated Team</h2>
        <div class="admin-grid">
            <div class="admin-card">
                <img src="IMAGE.png" alt="Admin 1">
                <h3>YUGESH M</h3>
                <p>C.E.O</p>
                <p>EMAIL:yugi@gmail.com</p>
            </div>
            <div class="admin-card">
                <img src="CH.jpg" alt="Admin 2">
                <h3>VENKATESH BHAT</h3>
                <p>Head Chef</p>
                <p>EMAIL:venky@gmail.com</p>
            </div>
            <div class="admin-card">
                <img src="VJ.jpg" alt="Admin 3">
                <h3>VIJAY</h3>
                <p>CHEIF GUEST</p>
                <p>EMAIL:vijay@gmail.com</p>
            </div>
            <div class="admin-card">
                <img src="JJ.jpg" alt="Admin 4">
                <h3>GERIUS</h3>
                <p>MARKETING MANAGER</p>
                <p>gerius@gmail.com</p>
            </div>
            <div class="admin-card">
                <img src="SS.jpg" alt="Admin 5">
                <h3>SANTHANAM</h3>
                <p>FINANCE MANAGER</p>
                <p>EMAIL:santa@gmail.com</p>
            </div>
        </div>
    </div>
</body>
</html>

contact.html

<!-- Contact Section -->
 <!-- Navigation Bar -->
 <ul class="nav-links">
    <li><a href="Home.html">Home</a></li>
    <li><a href="menu.html">Menu</a></li>
    <li><a href="administration.html">Administration</a></li>
    <li><a href="contact.html">Contact Us</a></li>
</ul>
<div class="contact-section">  
     
    <div class="contact-details">
        <h2><font  Our Address</h2>
        <p>543 THANDALAM ROAD</p>
        <p>CHENNAI</p>

        <h2>
            <font color="red">Phone</font>
        </h2>
        <p>78920678959</p>

        <h2>Email</h2>
        <p><a href="mailto:yugimess&gmail.com">yugimess@gmail.com</a></p>
    </div>

```

## OUTPUT:
![alt text](<Screenshot (92).png>)
![alt text](<Screenshot (93).png>)
![alt text](<Screenshot (94).png>)
![alt text](<Screenshot (95).png>)
![alt text](<Screenshot (96).png>)
![alt text](<Screenshot (97).png>)
![alt text](<Screenshot (98).png>)

## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
