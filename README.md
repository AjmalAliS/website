# Ex.07 Restaurant Website
# Date: 06-05-2025
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
index.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>PANTHER RESTAURANT - Home</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="menu.html">Menu</a></li>
                <li><a href="administration.html">Administration</a></li>
                <li><a href="contact.html">Contact Us</a></li>
            </ul>
        </nav>
    </header>

    <section class="banner">
        <h2>30% Off This Weekend</h2>
        <p>Enjoy a special discount on all dishes this weekend. Come and treat yourself to delicious meals!</p>
    </section>

    <section class="features">
        <div class="card">
            <h3>Our New Menu</h3>
            <img src="menu.jpg" alt="New Menu">
            <p>Check out our exciting new dishes added to the menu this season.</p>
            <a href="menu.html">See our new menu</a>
        </div>
        <div class="card">
            <h3>Book a table</h3>
            <img src="table.jpg" alt="Book a Table">
            <p>Reserve your table in advance and enjoy your meal without waiting.</p>
            <a href="#">Book your table now</a>
        </div>
        <div class="card">
            <h3>Opening Hours</h3>
            <img src="chef.jpg" alt="Chef">
            <p>Mon - Fri: 2pm - 10pm<br>Sat: 2pm - 11pm<br>Sun: 2pm - 9pm</p>
        </div>
    </section>

    <footer>
        <p>Designed and Developed by AJMAL ALI S (24009653)</p>
    </footer>
</body>
</html>

```
```
menu.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Menu - PANTHER RESTAURANT</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>PANTHER RESTAURANT</header>
    <main class="menu">
        <h2>Our Menu</h2>
        <br>
        <div class="menu-grid">
            <div class="menu-item"><img src="item1.jpg"><h4>Peri Peri Chicken</h4><p>With herbs</p></div>
            <div class="menu-item"><img src="item2.jpg"><h4>Fettuccine Alfredo</h4><p>Classic Italian</p></div>
            <div class="menu-item"><img src="item3.jpg"><h4>BBQ Chicken Pizza</h4><p>Stone-baked</p></div>
            <div class="menu-item"><img src="item4.jpg"><h4>Greek Salad</h4><p>Fresh & crunchy</p></div>
            <div class="menu-item"><img src="item5.jpg"><h4>Double Cheeseburger</h4><p>Grilled to perfection</p></div>
            <div class="menu-item"><img src="item6.jpg"><h4>Shrimp Tacos</h4><p>With lime crema</p></div>
            <div class="menu-item"><img src="item7.jpg"><h4>Paneer Butter Masala</h4><p>Indian classic</p></div>
            <div class="menu-item"><img src="item8.jpg"><h4>Deluxe Sushi Platter</h4><p>Assorted rolls</p></div>
            <div class="menu-item"><img src="item9.jpg"><h4>Ribeye Steak</h4><p>Medium-rare</p></div>
            <div class="menu-item"><img src="item10.jpg"><h4>Blueberry Pancakes</h4><p>With maple syrup</p></div>
            <div class="menu-item"><img src="item11.jpg"><h4>Gourmet Ice Cream</h4><p>3 scoops variety</p></div>
            <div class="menu-item"><img src="item12.jpg"><h4>Tropical Fruit Bowl</h4><p>Seasonal mix</p></div>
        </div>
    </main>
    <footer>
        Developed by AJMAL ALI S (24009653)
    </footer>
</body>
</html>

```
```
administration.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Administration - PANTHER RESTAURANT</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>PANTHER RESTAURANT</header>
    <main class="admin">
        <h2>Meet Our Team</h2>
        <div class="admin-grid">
            <div class="admin-card"><img src="chef1.jpg"><h4>Rajesh Nair</h4><p>Head Chef</p></div>
            <div class="admin-card"><img src="chef2.jpg"><h4>Sophia Thomas</h4><p>Restaurant Manager</p></div>
            <div class="admin-card"><img src="chef3.jpg"><h4>Aliya Kapoor</h4><p>Pastry Chef</p></div>
            <div class="admin-card"><img src="chef4.png"><h4>Marcus Tan</h4><p>Marketing Head</p></div>
            <div class="admin-card"><img src="chef5.jpg"><h4>Nisha Verma</h4><p>Customer Relations</p></div>
            <div class="admin-card"><img src="chef6.jpg"><h4>David Chen</h4><p>Finance Officer</p></div>
        </div>
    </main>
    <footer>
        Developed by AJMAL ALI S (24009653)
    </footer>
</body>
</html>

```
```
contact.html

<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contact Us - PANTHER RESTAURANT</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>PANTHER RESTAURANT</header>
    <main class="contact">
        <h2>Contact Us</h2>
        <p><strong>Address:</strong> 369 side Street, Chennai, India</p>
        <p><strong>Phone:</strong> +91 2233445566</p>
        <p><strong>Email:</strong> contact@pantherrestaurant.com</p>
    </main>
    <footer>
        Developed by AJMAL ALI S (24009653)
    </footer>
</body>
</html>
```

# OUTPUT:


![screencapture-127-0-0-1-8000-static-index-html-2025-05-06-11_40_47](https://github.com/user-attachments/assets/52a37efa-99da-4287-86e4-f5b0f072090b)
![screencapture-127-0-0-1-8000-static-menu-html-2025-05-06-11_39_55](https://github.com/user-attachments/assets/34e7fcab-800a-4a4d-959a-91c8d451a727)
![screencapture-127-0-0-1-8000-static-administration-html-2025-05-06-11_41_18](https://github.com/user-attachments/assets/5a5e1b7c-5e05-4b1d-9dc2-ae62f9559d7f)
![screencapture-127-0-0-1-8000-static-contact-html-2025-05-06-11_41_33](https://github.com/user-attachments/assets/836aafca-abbc-439d-a7f4-fef2ded21d7d)





# RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
