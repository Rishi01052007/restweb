# Ex.07 Restaurant Website
## Date:15.05.2025

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
rest.html
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>DKS BAKERY</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            color: #333;
        }

        header {
            background-color: #a03f76;
            color: white;
            padding: 15px;
            text-align: center;
        }

        header h1 {
            font-weight: 400;
        }

        header nav ul {
            list-style-type: none;
            padding: 0;
            margin: 0;
        }

        header nav ul li {
            display: inline;
            margin: 0 15px;
        }

        header nav ul li a {
            color: white;
            text-decoration: none;
        }

        header nav ul li a:hover {
            color: rgb(251, 150, 110);
            font-weight: bold;
        }

        .container {
            width: 100%;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: space-around;
        }

        h2 {
            color: #3f45a0;
        }

        .menu-item {
            background-color: #fff;
            margin: 10px 0;
            padding: 15px;
            border-radius: 8px;
            display: flex;
            align-items: center;
            box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
        }

        .menu-item img {
            border-radius: 8px;
            margin-right: 15px;
            width: 100px;
            height: auto;
        }

        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 10px 0;
            position: fixed;
            bottom: 0;
            width: 100%;
        }

        footer p {
            margin: 5px 0;
        }

        ::-webkit-scrollbar {
            width: 0px;
        }
    </style>
</head>

<body>
    <header>
        <h1> DKS BAKERY </h1>
        <nav>
            <ul>
                <li><a href="rest.html">Home</a></li>
                <li><a href="menu.html">Menu</a></li>
                <li><a href="about.html">About Us</a></li>
                <li><a href="contact.html">Contact Us</a></li>
            </ul>
        </nav>
    </header>

    <section class="container">
        <h2>Welcome to Our Restaurant</h2>
        <p>Faites l’expérience de la meilleure cuisine avec nous. Profitez de notre délicieux menu, de notre excellent service et d’une atmosphère chaleureuse.</p>
        <img src="./PICTURE.jpg" alt="Restaurant Banner" style="width: 30%; border-radius: 10px;">
    </section>

    <footer>
        <div class="container">
            <p>&copy; 2025 DKS BAKERY| Designed by NISHALINI R (24900414) </p>
        </div>
    </footer>
</body>

</html>

contact.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contact Us - DKS BAKERY</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #eaeaea;
            color: #333333;
        }

        header {
            background-color: #0b1cad;
            color: white;
            padding: 15px;
            text-align: center;
        }

        header h1 {
            font-weight: 400;
        }

        header nav ul {
            list-style-type: none;
            padding: 0;
            margin: 0;
        }

        header nav ul li {
            display: inline;
            margin: 0 15px;
        }

        header nav ul li a {
            color: white;
            text-decoration: none;
        }

        header nav ul li a:hover {
            color: rgb(251, 110, 234);
            font-weight: bold;
        }

        .contact-container {
            width: 60%;
            margin: 20px auto;
            padding: 20px;
            background: #fff;
            border-radius: 8px;
            box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
        }

        .contact-container h2 {
            text-align: center;
            margin-bottom: 20px;
        }

        .contact-item {
            margin-bottom: 15px;
        }

        .contact-item label {
            font-weight: bold;
        }

        .contact-item p {
            margin: 5px 0;
        }

        footer {
            background-color: #333333;
            color: white;
            text-align: center;
            padding: 10px 0;
            position: fixed;
            bottom: 0;
            width: 100%;
        }

        footer p {
            margin: 5px 0;
        }

        ::-webkit-scrollbar {
            width: 0px;
        }
    </style>
</head>
<body>
<header>
    <h1>CONTACT US</h1>
    <nav>
        <ul>
            <li><a href="rest.html">Home</a></li>
            <li><a href="menu.html">Menu</a></li>
            <li><a href="about.html">About Us</a></li>
            <li><a href="contact.html">Contact Us</a></li>
        </ul>
    </nav>
</header>

<div class="contact-container">
    <h2>Get in Touch</h2>
    <div class="contact-item">
        <label>Email:</label>
        <p>info@dksbakery.com</p>
    </div>
    <div class="contact-item">
        <label>Phone:</label>
        <p>+9841345678</p>
    </div>
    <div class="contact-item">
        <label>Address:</label>
        <p>231 Cross Street,Dhara City, Chennai, Tamilnadu</p>
    </div>
</div>

<footer>
    <p>&copy; 2025 Designed by NISHALINI R (24900414)</p>
</footer>
</body>
</html>

menu.html
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Menu - DKS BAKERY</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f9f6f1;
            color: #333;
        }

        header {
            background-color: #3fa0a0;
            color: rgb(255, 255, 255);
            padding: 15px;
            text-align: center;
        }

        header h1 {
            font-weight: 400;
        }

        header nav ul {
            list-style-type: none;
            padding: 0;
            margin: 0;
        }

        header nav ul li {
            display: inline;
            margin: 0 15px;
        }

        header nav ul li a {
            color: white;
            text-decoration: none;
            padding: 3px;
        }

        header nav ul li a:hover {
            color: rgb(251, 150, 110);
            font-weight: bold;
        }

        .menu-container {
            width: 80%;
            margin: 20px auto 70px auto;
            display: flex;
            justify-content: space-around;
            flex-wrap:wrap;
            overflow: scroll;
        }

        .menu-item {
            width: 30%;
            display: flex;
            align-items: center;
            margin-bottom: 20px;
            padding: 10px;
            border: 1px solid #ddd;
            border-radius: 8px;
            background-color: #fff;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
        }

        .menu-item img {
            width: 100px;
            height: 100px;
            border-radius: 8px;
            margin-right: 15px;
        }

        .menu-item h3 {
            margin: 0;
            font-size: 1.2em;
        }

        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 10px 0;
            position: fixed;
            bottom: 0;
            width: 100%;
        }

        footer p {
            margin: 5px 0;
        }

        ::-webkit-scrollbar {
            width: 0px;
        }
    </style>
</head>
<body>
    <header>
        <h1>OUR MENU</h1>
        <nav>
            <ul>
                <li><a href="rest.html">Home</a></li>
                <li><a href="menu.html">Menu</a></li>
                <li><a href="about.html">About Us</a></li>
                <li><a href="contact.html">Contact Us</a></li>
            </ul>
        </nav>
    </header>

    <div class="menu-container">
        <div class="menu-item">
            <img src="./borcoris.jpg" alt="Croissant">
            <div>
                <h3>BUTTER CROISSANT</h3>
                <p>Flaky,golden,and buttery.</p>
            </div>
        </div>
        <div class="menu-item">
            <img src="./acoris.jpg" alt="Croissant1">
            <div>
                <h3>ALMOND CROISSANT<h3>
                <p>Filled with almond cream,dusted with powdered sugar.</p>
            </div>
        </div>
        <div class="menu-item">
            <img src="./ncake.jpg" alt="Cake">
            <div>
                <h3>NEW YORK CHEESE CAKE</h3>
                <p>Claasic with a graham cracker crust.</p>
            </div>
        </div>
        <div class="menu-item">
            <img src="./ccake.jpg" alt="Cake1">
            <div>
                <h3>CHOCOLATE FUDGE CAKE</h3>
                <p>Decadent layers with rich ganache.</p>
            </div>
        </div>
        <div class="menu-item">
            <img src="./expresso.jpg" alt="Coffee">
            <div>
                <h3>EXPRESSO</h3>
                <p>Single or double shot.</p>
            </div>
        </div>
        <div class="menu-item">
            <img src="./ameri.jpg" alt="Coffee1">
            <div>
                <h3>AMERICA</h3>
                <p>Expresso with hot water.</p>
            </div>
        </div>
        <div class="menu-item">
            <img src="./cap.jpg" alt="Coffee2">
            <div>
                <h3>CAPPUCCINO</h3>
                <p>Bold expresso,foamed milk.</p>
            </div>
        </div>
        <div class="menu-item">
            <img src="./hc.jpg" alt="Tea">
            <div>
                <h3>HOT CHOCOLATE</h3>
                <p>Rich cocia,whipped cream.</p>
            </div>
        </div>
        <div class="menu-item">
            <img src="./fj.jpg" alt="Beverages">
            <div>
                <h3>FRESH JUICES</h3>
                <p>Apple,Orange,Strawberry,Watermelon,Lime,Etc.</p>
            </div>
        </div>
        <div class="menu-item">
            <img src="./ssb.jpg" alt="sandwich">
            <div>
                <h3>SMOKED SALMON BAGEL</h3>
                <p>Cream cheese,capers,red onion.</p>
            </div>
        </div>
        <div class="menu-item">
            <img src="./cs.jpg" alt="Sandwich1">
            <div>
                <h3>CAPRESE SANDWICH</h3>
                <p>Fresh mozzarella,tomato,basil pesto.</p>
            </div>
        </div>
        <div class="menu-item">
            <img src="./at.jpg" alt="Sanwich2">
            <div>
                <h3>AVOCADO TOASTED SANDWICH</h3>
                <p>Multigrain bread,smashed avocado,poached egg.</p>
            </div>
        </div>
    </div>

    <footer>
        <p>&copy; 2025 Designed by NISHALINI R (24900414)</p>
    </footer>
</body>

</html>
about.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Administration - DKS BAKERY</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f9;
            color: #333;
        }

        header {
            background-color: #3f51b5;
            color: white;
            padding: 15px;
            text-align: center;
        }

        header h1 {
            font-weight: 400;
        }

        header nav ul {
            list-style-type: none;
            padding: 0;
            margin: 0;
        }

        header nav ul li {
            display: inline;
            margin: 0 15px;
        }

        header nav ul li a {
            color: white;
            text-decoration: none;
        }

        header nav ul li a:hover {
            color: rgb(251, 150, 110);
            font-weight: bold;
        }

        .admin-container {
            width: 80%;
            margin: 20px auto;
            text-align: center;
        }

        .admin-card {
            display: inline-block;
            width: 200px;
            margin: 15px;
            padding: 15px;
            background-color: #fff;
            border: 1px solid #ddd;
            border-radius: 10px;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
            text-align: center;
        }

        .admin-card img {
            width: 100px;
            height: 100px;
            border-radius: 50%;
            margin-bottom: 10px;
        }

        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 10px 0;
            position: fixed;
            bottom: 0;
            width: 100%;
        }

        footer p {
            margin: 5px 0;
        }

        ::-webkit-scrollbar {
            width: 0px;
        }
    </style>
</head>
<body>
<header>
    <h1>ADMINISTRATION TEAM</h1>
    <nav>
        <ul>
            <li><a href="rest.html">Home</a></li>
            <li><a href="menu.html">Menu</a></li>
            <li><a href="about.html">About Us</a></li>
            <li><a href="contact.html">Contact Us</a></li>
        </ul>
    </nav>
</header>

<div class="admin-container">
    <div class="admin-card">
        <img src="./zarra.jpg" alt="Dirtector">
        <h3> ZAARA</h3>
        <p>Founder & Visionary Director</p>
    </div>
    <div class="admin-card">
        <img src="./gaggan.jpg" alt="Chef">
        <h3> GAGGAN ANAND </h3>
        <p>Head Chef</p>
    </div>
    <div class="admin-card">
        <img src="./vikas.jpg" alt="Sous Chef">
        <h3>VIKAS KHANNA </h3>
        <p>General Manager</p>
    </div>
    <div class="admin-card">
        <img src="./ranveer.jpg" alt="Waiter">
        <h3>RANVEER BRAR</h3>
        <p>Executive Chef</p>
    </div>
    <div class="admin-card">
        <img src="./alain.jpg" alt="Bartender">
        <h3>ALAIN DUCASSE</h3>
        <p>Guest Experience Manager</p>
    </div>
    <div class="admin-card">
        <img src="./pierre.jpg" alt="Receptionist">
        <h3>PIERRE GAGNAIRE</h3>
        <p>HR Manager</p>
    </div>
</div>

<footer>
    <p>&copy; 2025  Designed by NISHALINI R (24900414)</p>
</footer>
</body>
</html>
```
## OUTPUT:
![alt text](<Screenshot 2025-05-16 182144.png>)
![alt text](<Screenshot 2025-05-16 182214.png>)
![alt text](<Screenshot 2025-05-16 182241.png>)
![alt text](<Screenshot 2025-05-16 182305.png>)
## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
