# EX-02-Commercial-Website
## Date:31.10.2026
```
Name:Abinaya P
Registered Number:212225230003
```

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
```

<!DOCTYPE html>
<html>
<head>
    <title>Shopping Website</title>
    <link rel="stylesheet" href="exp2.css">
</head>
<body>

    <!-- Header -->
    <header>
        <h1>Style Store</h1>
        <p>Your Fashion, Your Style!</p>
    </header>

    <!-- Navigation Bar -->
    <nav>
        <a href="#home">Home</a>
        <a href="#products">Products</a>
        <a href="#about">About Us</a>
        <a href="#contact">Contact</a>
        <a href="#account">Account</a>
    </nav>

    <!-- Home Section -->
    <section id="home" class="home">
        <h2>Welcome to Style Store</h2>
        <p>Discover the latest fashion collections at affordable prices.</p>
        <button onclick="alert('Welcome to Style Store!')">
            Shop Now
        </button>
    </section>

    <!-- Products Section -->
    <section id="products">
        <h2>Our Products</h2>

        <div class="products">

            <div class="card">
                <img src="https://placehold.co/250x160?text=T-Shirts" alt="T-Shirts">
                <h3>T-Shirts</h3>
                <p>Price: Rs. 499</p>
                <button>Buy Now</button>
            </div>

            <div class="card">
                <img src="https://placehold.co/250x160?text=Shoes" alt="Shoes">
                <h3>Shoes</h3>
                <p>Price: Rs. 999</p>
                <button>Buy Now</button>
            </div>

            <div class="card">
                <img src="https://placehold.co/250x160?text=Bags" alt="Bags">
                <h3>Hand Bags</h3>
                <p>Price: Rs. 799</p>
                <button>Buy Now</button>
            </div>

        </div>
    </section>

    <!-- About Section -->
    <section id="about">
        <h2>About Us</h2>
        <p>Style Store provides quality fashion products at affordable prices.</p>
    </section>

    <!-- Contact Section -->
    <section id="contact">
        <h2>Contact Us</h2>
        <p>Email: stylestore@gmail.com</p>
        <p>Phone: 9876543210</p>
    </section>

    <!-- Account Section -->
    <section id="account">
        <h2>User Account</h2>
        <input type="text" placeholder="Enter Username">
        <input type="password" placeholder="Enter Password">
        <button onclick="alert('Login button clicked!')">Login</button>
    </section>

    <!-- Footer -->
    <footer>
        <p>Follow us: Instagram | Facebook | Twitter</p>
        <p>&copy; 2026 Style Store. All Rights Reserved.</p>
    </footer>

</body>
</html>

```
#css
```

/* Global Styles */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: Arial, sans-serif;
}

/* Header */
header {
    background-color: #333;
    color: white;
    text-align: center;
    padding: 25px;
}

/* Navigation */
nav {
    background-color: #555;
    display: flex;
    justify-content: center;
    padding: 15px;
}

nav a {
    color: white;
    text-decoration: none;
    margin: 0 20px;
}

nav a:hover {
    color: yellow;
}

/* Sections */
section {
    padding: 30px;
    text-align: center;
}

/* Home */
.home {
    background-color: #f2e6ff;
    padding: 60px;
}

/* Products using Flexbox */
.products {
    display: flex;
    justify-content: center;
    gap: 25px;
    flex-wrap: wrap;
    margin-top: 20px;
}

/* Product Cards */
.card {
    background-color: white;
    border: 1px solid #ddd;
    padding: 15px;
    width: 250px;
    border-radius: 10px;
    transition: 0.3s;
}

.card:hover {
    transform: scale(1.05);
    box-shadow: 0 4px 10px gray;
}

.card img {
    width: 100%;
    border-radius: 8px;
}

button {
    background-color: #7b2cbf;
    color: white;
    border: none;
    padding: 10px 20px;
    margin-top: 10px;
    cursor: pointer;
    border-radius: 5px;
}

button:hover {
    background-color: #4c087d;
}

/* Account */
input {
    padding: 10px;
    margin: 10px;
    border: 1px solid gray;
    border-radius: 5px;
}

/* Footer */
footer {
    background-color: #333;
    color: white;
    text-align: center;
    padding: 20px;
}

/* Responsive Design */
@media (max-width: 600px) {
    nav {
        flex-direction: column;
        align-items: center;
        gap: 15px;
    }

    .products {
        flex-direction: column;
        align-items: center;
    }
}
```


## OUTPUT

<img width="1920" height="1080" alt="Screenshot (24)" src="https://github.com/user-attachments/assets/7bcc9a50-17e3-43ff-9574-a38fa6285e4d" />



## RESULT
The program for creating commercial website using CSS Flexbox is executed successfully.
