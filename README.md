# Ex.07 Restaurant Website
## Date:09.12.24

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
administration.html

<html>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Administration - My Restaurant</title>
    <style>
     *{
        margin: 0;
        padding: 0;
        box-sizing: border-box;
      }

body {
    font-family: Arial, sans-serif;
    background-color: #f4f4f4;
    color: #333;
}

header {
    background-color: #333;
    color: #fff;
    padding: 20px 0;
    text-align: center;
}

header h1 {
    font-size: 2.5rem;
    margin-bottom: 10px;
}

nav ul {
    list-style-type: none;
    display: flex;
    justify-content: center;
    gap: 20px;
}

nav a {
    color: #fff;
    text-decoration: none;
    font-size: 1.2rem;
    transition: color 0.3s ease;
}

nav a:hover {
    color: #f4a261; 
}

main {
    padding: 40px 20px;
    text-align: center;
}

h2 {
    font-size: 2rem;
    margin-bottom: 20px;
    color: #333;
}


.team {
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(200px, 1fr));
    gap: 30px;
    justify-items: center;
    margin-top: 30px;
}

.member {
    background-color: #fff;
    padding: 20px;
    border-radius: 8px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
    text-align: center;
    transition: transform 0.3s ease, box-shadow 0.3s ease;
}

.member img {
    width: 100%;
    height: auto;
    border-radius: 50%;
    margin-bottom: 15px;
    border: 4px solid #f4a261; 
}

.member h3 {
    font-size: 1.5rem;
    margin-bottom: 10px;
    color: #333;
}

.member p {
    font-size: 1.1rem;
    color: #777;
}

.member:hover {
    transform: translateY(-5px);
    box-shadow: 0 6px 12px rgba(0, 0, 0, 0.15);
}

h3 {
    margin-bottom: 10px;
    font-size: 1.5rem;
    color: #333;
}

footer {
    background-color: #333;
    color: #fff;
    text-align: center;
    padding: 10px;
    position: fixed;
    bottom: 0;
    width: 100%;
}
</style>
</head>
<body>
    <header>
        <h1>Administration Team</h1>
        <nav>
            <ul>
                <li><a href="home.html">Home</a></li>
                <li><a href="menu.html">Menu</a></li>
                <li><a href="administration.html">Administration</a></li>
                <li><a href="contact.html">Contact Us</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <h2>Meet Our Team</h2>
        <div class="team">
            <div class="member">
                <img src="suki.jpg" alt="Member 1">
                <h3>Sukirthana.M</h3>
                <p>CEO</p>
            </div>
            <div class="member">
                <img src="member2.jpg" alt="Member 2">
                <h3>Jane<h3>
                <p>Marketing Manager</p>
            </div>
            <div class="member">
                <img src="member3.jpg" alt="Member 3">
                <h3>Henry<h3>
                <p>Operations Manager</p>
            </div>
            <div class="member">
                <img src="member4.jpg" alt="Member 4">
                <h3>Victor<h3>
                <p>HR Manager</p>
            </div>
            <div class="member">
                <img src="member5.jpg" alt="Member 5">
                <h3>Thomas<h3>
                <p>Executive Chef</p>
            </div>
            <div class="member">
                <img src="member6.jpg" alt="Member 6">
                <h3>Charles<h3>
                <p>Customer Service Manger</p>
            </div>
        </div>
    </main>
</body>
</html>

contact.html

<body>
  <style>
  *{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
  }

body {
  font-family: Arial, sans-serif;
  background-color: #f4f4f4;
  color: #333;
}
#contact {
  background-color: #fff;
  padding: 40px 20px;
  margin: 40px auto;
  max-width: 600px;
  border-radius: 8px;
  box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
  text-align: center;
}

#contact h2 {
  font-size: 2rem;
  margin-bottom: 20px;
  color: #333;
}

#contact p {
  font-size: 1.2rem;
  margin-bottom: 20px;
  color: #555;
}

address {
  font-size: 1.1rem;
  line-height: 1.6;
  color: #333;
}

address br {
  margin-bottom: 10px;
}

#contact:hover {
  transform: translateY(-5px);
  box-shadow: 0 6px 12px rgba(0, 0, 0, 0.15);
}
  </style>
   <section id="contact">
  <h2>Contact Us</h2>
  <p>Visit us at:</p>
  <address>
    123 Main Street, Cityville, India
    <br>
    Phone: (123) 456-7890
    <br>
    Email: info@myrestaurant.com
  </address>
</section>
</body>
</html>


home.html

<html>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Home - My Restaurant</title>
    <style>
   *{
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

body {
    font-family: Arial, sans-serif;
    background-color: #f4f4f4;
    color: #333;
}

header {
    background-color: #333;
    color: #fff;
    padding: 20px 0;
    text-align: center;
}

header h1 {
    font-size: 2.5rem;
    margin-bottom: 10px;
}

nav ul {
    list-style-type: none;
    display: flex;
    justify-content: center;
    gap: 20px;
}

nav a {
    color: #fff;
    text-decoration: none;
    font-size: 1.2rem;
    transition: color 0.3s ease;
}

nav a:hover {
    color: #f4a261; 
}

main {
    text-align: center;
    padding: 40px 20px;
}

.banner {
    width: 100%;
    height: auto;
    max-height: 400px; 
    object-fit: cover; 
    margin-bottom: 30px;
}

h2 {
    font-size: 2rem;
    margin-bottom: 20px;
    color: #333;
}

p {
    font-size: 1.2rem;
    color: #777;
}

footer {
    background-color: #333;
    color: #fff;
    text-align: center;
    padding: 10px;
    position: fixed;
    bottom: 0;
    width: 100%;
}
</style>
</head>
<body>
    <header>
        <h1>Welcome to My Restaurant</h1>
        <nav>
            <ul>
                <li><a href="home.html">Home</a></li>
                <li><a href="menu.html">Menu</a></li>
                <li><a href="administration.html">Administration</a></li>
                <li><a href="contact.html">Contact Us</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <img src="banner.jpg" alt="Restaurant Banner" class="banner">
        <h2>Delicious Food Awaits You!</h2>
        <p>Experience the best dining experience with us.</p>
    </main>
    <footer>
        <p>&copy; 2024 Sukirthana</p>
    </footer>
</body>
</html>

menu.html

<html>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Menu - My Restaurant</title>
   <style>
    *{
        margin: 0;
        padding: 0;
        box-sizing: border-box;
     }

body {
    font-family: Arial, sans-serif;
    background-color: #f4f4f4;
    color: #333;
}

header {
    background-color: #333;
    color: #fff;
    padding: 20px 0;
    text-align: center;
}

header h1 {
    font-size: 2.5rem;
    margin-bottom: 10px;
}

nav ul {
    list-style-type: none;
    display: flex;
    justify-content: center;
    gap: 20px;
}

nav a {
    color: #fff;
    text-decoration: none;
    font-size: 1.2rem;
    transition: color 0.3s ease;
}

nav a:hover {
    color: #f4a261; /* Light orange on hover */
}

main {
    padding: 40px 20px;
    text-align: center;
}

h2 {
    font-size: 2rem;
    margin-bottom: 20px;
    color: #333;
}

.menu-list {
    list-style-type: none;
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(200px, 1fr));
    gap: 20px;
    justify-items: center;
}

.menu-list li {
    background-color: #fff;
    padding: 15px;
    border-radius: 8px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
    width: 100%;
    text-align: center;
}

.menu-list img {
    width: 100%;
    height: auto;
    border-radius: 5px;
    margin-bottom: 15px;
}

.menu-list li p {
    font-size: 1.1rem;
    color: #333;
    font-weight: bold;
}

.menu-list li:hover {
    transform: translateY(-5px);
    box-shadow: 0 6px 12px rgba(0, 0, 0, 0.15);
}


footer {
    background-color: #333;
    color: #fff;
    text-align: center;
    padding: 10px;
    position: fixed;
    bottom: 0;
    width: 100%;
}
</style>
</head>
<body>
    <header>
        <h1>Our Menu</h1>
        <nav>
            <ul>
                <li><a href="home.html">Home</a></li>
                <li><a href="menu.html">Menu</a></li>
                <li><a href="administration.html">Administration</a></li>
                <li><a href="contact.html">Contact Us</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <h2>Food Items</h2>
        <ul class="menu-list">
            <li><img src="pizza.jpg" alt="Food Item 1">Pizza - $10</li>
            <li><img src="burger.jpg" alt="Food Item 2">Burger - $8</li>
            <li><img src="pasat.jpg" alt="Food Item 3">Pasta - $12</li>
            <li><img src="salad.jpg" alt="Food Item 4">Salad - $7</li>
            <li><img src="nuggets.jpg" alt="Food Item 5">Nuggets - $15</li>
            <li><img src="icecream.jpg" alt="Food Item 6">Ice Cream - $5</li>
            <li><img src="sandwich.jpg" alt="Food Item 7">Sandwich - $6</li>
            <li><img src="french fries.jpg" alt="Food Item 8">French Fries - $4</li>
            <li><img src="soup.jpg" alt="Food Item 9">Soup - $5</li>
            <li><img src="chocolate cake.jpg" alt="Food Item 10">Chocolate Cake - $6</li>
            <li><img src="smiley fries.jpg" alt="Food Item 11">Smiley Fries - $6</li>
            <li><img src="brownie.jpg" alt="Food Item 12">Brownie - $6</li>

        </ul>
    </main>
    <footer>
        <p>&copy; 2024 Sukirthana</p>
    </footer>
</body>
</html>

```
## OUTPUT:
![alt text](<Screenshot (34).png>)
![alt text](<Screenshot (35).png>)
![alt text](<Screenshot (37).png>)
![alt text](<Screenshot (38).png>)
![alt text](<Screenshot (39).png>)

## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
