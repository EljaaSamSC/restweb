# Ex.06 Restaurant Website
## Date:01/12/25

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
index.html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Taste Haven Restaurant</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <h1>Taste Haven Restaurant</h1>
    <nav>
      <ul>
        <li><a href="#">Home</a></li>
        <li><a href="#">Menu</a></li>
        <li><a href="#">Services</a></li>
        <li><a href="#">Contact</a></li>
      </ul>
    </nav>
  </header>

  <section class="hero">
    <h2>Delicious Meals, Perfect Ambience</h2>
    <p>Come and enjoy our chef’s special dishes made with love.</p>
    <button>Order Now</button>
  </section>

  <section class="menu">
    <h2>Our Popular Dishes</h2>
    <div class="menu-items">
      <div class="item">
        <img src="https://via.placeholder.com/200" alt="Pizza">
        <h3>Cheese Burst Pizza</h3>
        <p>₹250</p>
      </div>
      <div class="item">
        <img src="https://via.placeholder.com/200" alt="Burger">
        <h3>Classic Veg Burger</h3>
        <p>₹180</p>
      </div>
      <div class="item">
        <img src="https://via.placeholder.com/200" alt="Pasta">
        <h3>Italian White Sauce Pasta</h3>
        <p>₹200</p>
      </div>
    </div>
  </section>

  <footer>
    <p>© 2025 Taste Haven Restaurant | All Rights Reserved</p>
  </footer>
</body>
</html>

style.css
body {
  font-family: Arial, sans-serif;
  margin: 0;
  background-color: #fff8f0;
  color: #333;
}

header {
  background-color: #b83b5e;
  color: white;
  padding: 15px 0;
  text-align: center;
}

nav ul {
  list-style: none;
  padding: 0;
}

nav ul li {
  display: inline;
  margin: 0 15px;
}

nav ul li a {
  color: white;
  text-decoration: none;
  font-weight: bold;
}

.hero {
  text-align: center;
  padding: 50px;
  background-image: linear-gradient(rgba(0,0,0,0.5), rgba(0,0,0,0.5)), url('https://via.placeholder.com/1200x400');
  background-size: cover;
  color: white;
}

.hero button {
  background-color: #f08a5d;
  border: none;
  padding: 10px 20px;
  color: white;
  font-size: 16px;
  border-radius: 5px;
  cursor: pointer;
}

.menu {
  padding: 40px;
  text-align: center;
}

.menu-items {
  display: flex;
  justify-content: center;
  gap: 20px;
}

.item {
  background: #fff;
  border-radius: 10px;
  padding: 15px;
  box-shadow: 0 2px 5px rgba(0,0,0,0.1);
  width: 220px;
}

.item img {
  width: 100%;
  border-radius: 10px;
}

footer {
  text-align: center;
  padding: 15px;
  background-color: #b83b5e;
  color: white;
  margin-top: 30px;
}

```

## OUTPUT:

![WhatsApp Image 2025-12-23 at 7 21 32 PM](https://github.com/user-attachments/assets/775d450e-4251-416b-848a-79b10f76cc94)

## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
