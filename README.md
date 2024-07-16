# CSS-Basic-Project
### Aim: To design a Website using CSS.
### Program:
#### Index.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ROOPTECH</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <div class="logo">SOMIREDDYTECH</div>
        <nav>
            <ul>
                <li><a href="index.html">HOME</a></li>
                <li><a href="products.html">PRODUCTS</a></li>
                <li><a href="council.html">PEOPLE</a></li>
                <li><a href="contact.html">CONTACT</a></li>
            </ul>
            <div class="search-box">
                <input type="text" placeholder="Enter to Search">
                <button>Search</button>
            </div>
        </nav>
    </header>

    <main>
        <section class="hero">
            <h1>"Driving progress through precision engineering and boundless creativity."</h1>
            <div class="buttons">
                <button class="login">Log In</button>
                <button class="signup">Sign Up</button>
            </div>
        </section>
    </main>

    <footer>
        <p>DESIGNED AND DEVELOPED BY S HARISH KUMAR(212221230104)</p>
    </footer>
</body>
</html>
```
#### Styles.css
```
body {
    margin: 0;
    font-family: Arial, sans-serif;
    background-color: #000;
    color: #fff;
}

header {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 20px;
    background-color:#d3cc10;
}

.logo {
    font-size: 24px;
    font-weight: bold;
}

nav ul {
    list-style: none;
    display: flex;
    gap: 20px;
}

nav ul li a {
    color: #fff;
    text-decoration: none;
}

.search-box {
    display: flex;
    align-items: center;
}

.search-box input {
    padding: 5px;
    border: none;
    border-radius: 3px;
}

.search-box button {
    padding: 5px 10px;
    border: none;
    border-radius: 3px;
    margin-left: 5px;
    background-color: #00f;
    color: #fff;
    cursor: pointer;
}

main {
    display: flex;
    justify-content: center;
    align-items: center;
    height: 80vh;
    background: linear-gradient(45deg, #2f6824, #5eb7b1);
    text-align: center;
}

.hero h1 {
    font-size: 36px;
    margin-bottom: 20px;
}

.buttons {
    display: flex;
    gap: 20px;
}

.buttons button {
    padding: 10px 20px;
    border: none;
    border-radius: 5px;
    cursor: pointer;
}

.login {
    background-color: #f00;
    color: #fff;
}

.signup {
    background-color: #0f0;
    color: #000;
}

footer {
    text-align: center;
    padding: 10px;
    background-color: #111;
    color: #fff;
}

```
#### Products.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Products - SOMIREDDYTECH</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <div class="logo">SOMIREDDYTECH</div>
        <nav>
            <ul>
                <li><a href="index.html">HOME</a></li>
                <li><a href="products.html">PRODUCTS</a></li>
                <li><a href="council.html">PEOPLE</a></li>
                <li><a href="contact.html">CONTACT</a></li>
            </ul>
            <div class="search-box">
                <input type="text" placeholder="Enter to Search">
                <button>Search</button>
            </div>
        </nav>
    </header>

    <main>
        <section class="products">
            <div class="product">
                <h2>C++</h2>
                <p>Efficiency Redefined: Harnessing the Power of C++ for Next-Level Development</p>
            </div>
            <div class="product">
                <h2>C</h2>
                <p>Crafting Performance: Where Precision Meets C Programming.</p>
            </div>
            <!-- Add more product sections as needed -->
        </section>
    </main>

    <footer>
        <p>DESIGNED AND DEVELOPED BY S HARISH KUMAR(212221230104)</p>
    </footer>
</body>
</html>
```
#### Style1.css
```
body {
    margin: 0;
    font-family: Arial, sans-serif;
    background-color: #000;
    color: #fff;
}

header {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 20px;
    background-color: #d3cc10;
}

.logo {
    font-size: 24px;
    font-weight: bold;
}

nav ul {
    list-style: none;
    display: flex;
    gap: 20px;
}

nav ul li a {
    color: #fff;
    text-decoration: none;
}

.search-box {
    display: flex;
    align-items: center;
}

.search-box input {
    padding: 5px;
    border: none;
    border-radius: 3px;
}

.search-box button {
    padding: 5px 10px;
    border: none;
    border-radius: 3px;
    margin-left: 5px;
    background-color: #00f;
    color: #fff;
    cursor: pointer;
}

main {
    display: flex;
    justify-content: center;
    align-items: center;
    height: 80vh;
    background: linear-gradient(45deg, #2f6824, #5eb7b1);
    text-align: center;
}

.hero h1 {
    font-size: 36px;
    margin-bottom: 20px;
}

.buttons {
    display: flex;
    gap: 20px;
}

.buttons button {
    padding: 10px 20px;
    border: none;
    border-radius: 5px;
    cursor: pointer;
}

.login {
    background-color: #f00;
    color: #fff;
}

.signup {
    background-color: #0f0;
    color: #000;
}

footer {
    text-align: center;
    padding: 10px;
    background-color: #111;
    color: #fff;
}

.products {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    gap: 20px;
    padding: 20px;
}

.product {
    background-color: #222;
    padding: 20px;
    border-radius: 10px;
    width: 200px;
    text-align: center;
}

.product h2 {
    color: #f00;
}

.product p {
    color: #aaa;
}
```

#### Council.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>People - SOMIREDDYTECH</title>
    <link rel="stylesheet" href="styl.css">
</head>
<body>
    <header>
        <div class="logo">SOMIREDDYTECH</div>
        <nav>
            <ul>
                <li><a href="index.html">HOME</a></li>
                <li><a href="products.html">PRODUCTS</a></li>
                <li><a href="council.html">PEOPLE</a></li>
                <li><a href="contact.html">CONTACT</a></li>
            </ul>
            <div class="search-box">
                <input type="text" placeholder="Enter to Search">
                <button>Search</button>
            </div>
        </nav>
    </header>

    <main>
        <section class="people">
            <div class="person">
                <img src="mine.jpg" alt="Roop Sagar">
                <h2>Manoj Tella</h2>
                <p>CEO</p>
            </div>
            <div class="person">
                <img src="mine1.jpeg" alt="Ratan Tata">
                <h2>Manu</h2>
                <p>CEO, Co-Founder</p>
            </div>
            <div class="person">
                <img src="mine.jpg" alt="Steve Jobs">
                <h2>Hari</h2>
                <p>CTO, Co-Founder</p>
            </div>
            <div class="person">
                <img src="mine.jpeg" alt="Sundar">
                <h2>SUNDAR</h2>
                <p>DIRECTOR</p>
            </div>
            <div class="person">
                <img src="mine2.png" alt="Walt Disney">
                <h2>Guna</h2>
                <p>Asst. Director</p>
            </div>
            <div class="person">
                <img src="mine3.png" alt="Elon Musk">
                <h2>Tella</h2>
                <p>Dy. Director</p>
            </div>
        </section>
    </main>

    <footer>
        <p>DESIGNED AND DEVELOPED BY S HARISH KUMAR(212221230104)</p>
    </footer>
</body>
</html>
```
#### Style2.css
```
body {
    margin: 0;
    font-family: Arial, sans-serif;
    background-color: #000;
    color: #fff;
}

header {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 20px;
    background-color:#d3cc10;
}

.logo {
    font-size: 24px;
    font-weight: bold;
}

nav ul {
    list-style: none;
    display: flex;
    gap: 20px;
}

nav ul li a {
    color: #fff;
    text-decoration: none;
}

.search-box {
    display: flex;
    align-items: center;
}

.search-box input {
    padding: 5px;
    border: none;
    border-radius: 3px;
}

.search-box button {
    padding: 5px 10px;
    border: none;
    border-radius: 3px;
    margin-left: 5px;
    background-color: #00f;
    color: #fff;
    cursor: pointer;
}

main {
    display: flex;
    justify-content: center;
    align-items: center;
    height: 80vh;
    background: linear-gradient(45deg, #2f6824, #5eb7b1);
    text-align: center;
}

.hero h1 {
    font-size: 36px;
    margin-bottom: 20px;
}

.buttons {
    display: flex;
    gap: 20px;
}

.buttons button {
    padding: 10px 20px;
    border: none;
    border-radius: 5px;
    cursor: pointer;
}

.login {
    background-color: rgb(54, 95, 146);
    color: #fff;
}

.signup {
    background-color: #0f0;
    color: #000;
}

footer {
    text-align: center;
    padding: 10px;
    background-color: #111;
    color: #fff;
}

.people {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    gap: 20px;
    padding: 20px;
}

.person {
    text-align: center;
    color: #fff;
}

.person img {
    border-radius: 50%;
    width: 150px;
    height: 150px;
}

.person h2 {
    margin: 10px 0 5px;
}

.person p {
    color: rgb(187, 209, 15);
}
```
#### Comtact.html
```
<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>Products - SOMIREDDYTECH</title>
        <link rel="stylesheet" href="style1.css">
    </head>
    <body>
        <header>
            <div class="logo">SOMIREDDYTECH</div>
            <nav>
                <ul>
                    <li><a href="index.html">HOME</a></li>
                    <li><a href="products.html">PRODUCTS</a></li>
                    <li><a href="council.html">PEOPLE</a></li>
                    <li><a href="contact.html">CONTACT</a></li>
                </ul>
                <div class="search-box">
                    <input type="text" placeholder="Enter to Search">
                    <button>Search</button>
                </div>
            </nav>
        </header>

    <main>
        <div class="contact-container">
            <div class="contact-form">
                <h2>Contact Us</h2>
                <form>
                    <label for="name">Your Name</label>
                    <input type="text" id="name" name="name" required>
                    <label for="email">Your Email</label>
                    <input type="email" id="email" name="email" required>
                    <button type="submit">Submit</button>
                </form>
            </div>
            <div class="contact-info">
                <h2>Contact Information</h2>
                <p><strong>Address:</strong> Ananthavaram,Bapatala,Andhra Pradesh,523301.</p>
                <p><strong>Email:</strong> harish@gmail.com</p>
                <p><strong>Phone:</strong> 1234567890</p>
            </div>
        </div>
    </main>

    <footer>
        <p>Designed and DEVELOPED BY S HARISH KUMAR(212221230104)</p>
    </footer>
</body>
</html>
```
#### Style3.css
```
body {
    margin: 0;
    font-family: Arial, sans-serif;
    background-color: #000;
    color: #fff;
}

header {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 20px;
    background-color:#d3cc10;
}

.logo {
    font-size: 24px;
    font-weight: bold;
}

nav ul {
    list-style: none;
    display: flex;
    gap: 20px;
}

nav ul li a {
    color: #fff;
    text-decoration: none;
}

.search-box {
    display: flex;
    align-items: center;
}

.search-box input {
    padding: 5px;
    border: none;
    border-radius: 3px;
}

.search-box button {
    padding: 5px 10px;
    border: none;
    border-radius: 3px;
    margin-left: 5px;
    background-color: #00f;
    color: #fff;
    cursor: pointer;
}

main {
    display: flex;
    justify-content: center;
    align-items: center;
    height: 80vh;
    background: linear-gradient(45deg, #2f6824, #5eb7b1);
    text-align: center;
}

.hero h1 {
    font-size: 36px;
    margin-bottom: 20px;
}

.buttons {
    display: flex;
    gap: 20px;
}

.buttons button {
    padding: 10px 20px;
    border: none;
    border-radius: 5px;
    cursor: pointer;
}

.login {
    background-color: #f00;
    color: #fff;
}

.signup {
    background-color: #0f0;
    color: #000;
}

footer {
    text-align: center;
    padding: 10px;
    background-color: #111;
    color: #fff;
}

.contact {
    padding: 20px;
    text-align: center;
    color: #fff;
}

.contact h1 {
    margin-bottom: 20px;
}

form {
    max-width: 600px;
    margin: 0 auto;
    text-align: left;
}

.form-group {
    margin-bottom: 15px;
}

label {
    display: block;
    margin-bottom: 5px;
}

input, textarea {
    width: 100%;
    padding: 10px;
    border: none;
    border-radius: 5px;
    box-sizing: border-box;
}

button[type="submit"] {
    display: block;
    width: 100%;
    padding: 10px;
    border: none;
    border-radius: 5px;
    background-color: #00f;
    color: #fff;
    font-size: 16px;
    cursor: pointer;
}

button[type="submit"]:hover {
    background-color: #0055cc;
}
```
### Output
![image](https://github.com/user-attachments/assets/b322e7b5-61ca-4dae-b9c7-0c824ba51250)

![image](https://github.com/user-attachments/assets/7b19477c-3cf1-488d-899f-6c23b78edbae)

![image](https://github.com/user-attachments/assets/59b32819-93d4-4a0b-a1b8-3117d7ac0926)

![image](https://github.com/user-attachments/assets/70c5246b-4762-4c3e-9bd7-561a0a842f7e)

### Result:
Thus,creating a website using CSS was executed successfully.
