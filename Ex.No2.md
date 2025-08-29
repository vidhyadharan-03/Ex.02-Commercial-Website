# Ex02 Commercial Website
## Date: 24/08/2025

## AIM
To create a commercial website using CSS Flexbox.

## ALGORITHM
### STEP 1
Create an HTML file (index.html)

### STEP 2
Create a CSS file (style.css)

### STEP 3
Include a navigation bar with links to different sections.

### STEP 4
Add structured sections for Homepage, Products / Services, About Us, Contact Details and User Account.

### STEP 5
Include social media links at the footer with copyright information.

### STEP 6
Define global styles for fonts, colors, and layout.

### STEP 7
Style the header, navigation bar, and sections.

### STEP 8
Use Flexbox for layout design.

### STEP 9
Add hover effects and transitions for interactivity.

### STEP 10
Add Images and Media.

### STEP 11
Use optimized images for a professional look.

### STEP 12
Open the HTML file in a browser to check layout and functionality.

### STEP 13
Fix styling issues and refine content placement.

### STEP 14
Deploy the website.

### STEP 15
Upload to GitHub Pages for free hosting.

## PROGRAM
#### index.html:
```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>FlexiShop</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <h1>FlexiShop</h1>
    <nav>
      <ul>
        <li><a href="#home">Home</a></li>
        <li><a href="#products">Products</a></li>
        <li><a href="#about">About Us</a></li>
        <li><a href="#account">Account</a></li>
        <li><a href="#contact">Contact</a></li>
      </ul>
    </nav>
  </header>

  <section id="home" class="hero">
    <h2>Welcome to FlexiShop</h2>
    <p>Your one-stop solution for quality products at the best prices.</p>
  </section>

  <section id="products" class="flex-section">
    <h2>Our Products</h2>
    <div class="card-container">
      <div class="card">
        <img src="i1.jpg" alt="Product 1">
        <p>Product 1</p>
      </div>
      <div class="card">
        <img src="i2.jpg" alt="Product 2">
        <p>Product 2</p>
      </div>
      <div class="card">
        <img src="i3.jpg" alt="Product 3">
        <p>Product 3</p>
      </div>
      <div class="card">
        <img src="i4.jpg" alt="Product 3">
        <p>Product 3</p>
      </div>
      <div class="card">
        <img src="i5.jpg" alt="Product 3">
        <p>Product 3</p>
      </div>
    </div>
  </section>

  <section id="about">
    <h2>About Us</h2>
    <p>FlexiShop is committed to delivering high-quality products with excellent customer service. Our goal is to make shopping flexible, fun, and affordable for everyone.</p>
  </section>


  <section id="contact">
    <h2>Contact Us</h2>
    <p>Email: support@flexishop.com</p>
    <p>Phone: +91 9876543210</p>
  </section>

  <footer>
    <div class="socials">
      <a href="#">Instagram</a> | 
      <a href="#">Facebook</a> | 
      <a href="#">Twitter</a>
    </div>
    <p>&copy; 2025 FlexiShop. All rights reserved.</p>
  </footer>
</body>
</html>


```


#### style.css:

```css
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
  }
  
  body {
    font-family: 'Segoe UI', sans-serif;
    background: #f5f5f5;
    color: #333;
    line-height: 1.6;
  }
  
  header {
    background: #222;
    color: #fff;
    text-align: center;
    padding: 20px;
  }
  
  nav ul {
    list-style: none;
    display: flex;
    justify-content: center;
    gap: 30px;
    padding: 15px 0;
    background: #333;
  }
  
  nav ul li a {
    color: #fff;
    text-decoration: none;
    transition: color 0.3s ease;
  }
  
  nav ul li a:hover {
    color: #fdd835;
  }
  
  .hero {
    padding: 60px 20px;
    background: #ffeb3b;
    text-align: center;
  }
  
  .flex-section {
    padding: 40px 20px;
    background: #fff;
    text-align: center;
  }
  
  .card-container {
    display: flex;
    justify-content: center;
    flex-wrap: wrap;
    gap: 20px;
    margin-top: 20px;
  }
  
  .card {
    background: #e0e0e0;
    padding: 20px;
    width: 200px;
    border-radius: 10px;
    transition: transform 0.3s ease;
  }
  
  .card:hover {
    transform: scale(1.05);
    background: #d6d6d6;
  }
  
  .card img {
    width: 100%;
    border-radius: 10px;
    margin-bottom: 10px;
  }
  
  section {
    padding: 40px 20px;
    text-align: center;
  }
  
  footer {
    background: #222;
    color: #fff;
    text-align: center;
    padding: 20px;
  }
  
  footer .socials a {
    color: #fdd835;
    text-decoration: none;
    margin: 0 10px;
  }
  
  footer .socials a:hover {
    text-decoration: underline;
  }
  

```


## OUTPUT
![image](https://github.com/user-attachments/assets/88acc2f0-379f-44cc-a209-c1d8c12c8b53)


## RESULT
The program for creating commercial website using CSS Flexbox is executed successfully.
