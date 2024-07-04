# html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>INFOTECH</title>
    <link rel="stylesheet" href="style.css">
    <link sel="stylesheet" href="products.css"
</head>
<body>
    <header>
        <div class="logo">
            <h1>INFOTECH</h1>
        </div>
        <nav>
            <ul>
                <li><a href="#">Home</a></li>
                <li><a href="#">Products</a></li>
                <li><a href="#">People</a></li>
                <li><a href="#">Contact</a></li>
            </ul>
            <div class="search-bar">
                <link rel="stylesheet" href="products.css">
                <input type="text" placeholder="Enter to Search">
                <button>Search</button>
            </div>
        </nav>
    </header>

    <main>
        <div class="hero">qq
            <h2>"Driving progress through precision engineering and boundless creativity."</h2>
            <div class="buttons">
                <button class="login">Log In</button>
                <button class="signup">Sign Up</button>
            </div>
        </div>
    </main>

    <footer>
        <p>DESIGNED AND DEVELOPED BY DHARSHINI SENTHILKUMAR (212221220009)</p>
    </footer>
</body>
</html>
```
# CSS
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
    background-color: #111;
}

.logo h1 {
    color: #00ffff;
}

nav ul {
    display: flex;
    list-style-type: none;
    margin: 0;
    padding: 0;
}

nav ul li {
    margin-right: 20px;
}

nav ul li a {
    text-decoration: none;
    color: #fff;
}

.search-bar {
    display: flex;
    align-items: center;
}

.search-bar input {
    padding: 5px;
    border: none;
    border-radius: 3px;
    margin-right: 5px;
}

.search-bar button {
    padding: 5px 10px;
    border: none;
    border-radius: 3px;
    background-color: #00ffff;
    color: #000;
    cursor: pointer;
}

.hero {
    text-align: center;
    padding: 100px 20px;
    background: url('background.jpg') no-repeat center center;
    background-size: cover;
}

.hero h2 {
    margin: 0 0 20px 0;
    font-size: 24px;
    color: #fff;
}

.buttons {
    display: flex;
    justify-content: center;
    gap: 10px;
}

button {
    padding: 10px 20px;
    border: none;
    border-radius: 5px;
    font-size: 16px;
    cursor: pointer;
}

button.login {
    background-color: #ff0000;
    color: #fff;
}

button.signup {
    background-color: #00ff00;
    color: #fff;
}

footer {
    text-align: center;
    padding: 10px;
    background-color: #f00;
    color: #fff;
    position: fixed;
    bottom: 0;
    width: 100%;
}
```
# html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Products - INFOTECH</title>
    <link rel="stylesheet" href="products.css">
</head>
<body>
    <header>
        <div class="logo">
            <h1>INFOTECH</h1>
        </div>
        <nav>
            <ul>
                <li><a href="#">Home</a></li>
                <li><a href="#" class="active">Products</a></li>
                <li><a href="#">People</a></li>
                <li><a href="#">Contact</a></li>
            </ul>
            <div class="search-bar">
                <input type="text" placeholder="Enter to Search">
                <button class="search-button">Search</button>
            </div>
        </nav>
    </header>

    <main>
        <div class="products">
            <div class="product">
                <h3>C++</h3>
                <p>Efficiency Redefined: Harnessing the Power of C++ for Next-Level Development</p>
            </div>
            <div class="product">
                <h3>C</h3>
                <p>Crafting Performance: Where Precision Meets C Programming.</p>
            </div>
            <div class="product">
                <h3>JavaScript</h3>
                <p>Scripting Success: Unleashing the Power of JavaScript.</p>
            </div>
            <div class="product">
                <h3>PHP</h3>
                <p>PHP is a server-side scripting language that is embedded in HTML.</p>
            </div>
            <div class="product">
                <h3>Python</h3>
                <p>Unlocking Innovation: Python Paving the Way to Progress.</p>
            </div>
            <div class="product">
                <h3>SQL</h3>
                <p>SQL is a standard language for accessing and manipulating databases.</p>
            </div>
            <div class="product">
                <h3>Shell</h3>
                <p>Shell can be accessed by users using a command-line interface.</p>
            </div>
            <div class="product">
                <h3>Ruby</h3>
                <p>Ruby: Where Simplicity Meets Power in Programming.</p>
            </div>
            <div class="product">
                <h3>TypeScript</h3>
                <p>Empower Your Code: Embrace the Future with TypeScript.</p>
            </div>
            <div class="product">
                <h3>F#</h3>
                <p>F# is an Open source programming language with a lot of features.</p>
            </div>
        </div>
    </main>

    <footer>
        <p>DESIGNED AND DEVELOPED BY DHARSHINI SENTHILKUMAR (212221220009)</p>
    </footer>
</body>
</html>
```
# css
```
/* General Styles */
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
    background-color: #111;
}

.logo h1 {
    color: #00ffff;
}

nav ul {
    display: flex;
    list-style-type: none;
    margin: 0;
    padding: 0;
}

nav ul li {
    margin-right: 20px;
}

nav ul li a {
    text-decoration: none;
    color: #fff;
}

nav ul li a.active {
    color: #ff0000;
}

.search-bar {
    display: flex;
    align-items: center;
}

.search-bar input {
    padding: 5px;
    border: none;
    border-radius: 3px;
    margin-right: 5px;
}

.search-bar button, .search-button {
    padding: 5px 10px;
    border: none;
    border-radius: 3px;
    background-color: #ff0000;
    color: #fff;
    cursor: pointer;
}

/* Hero Section */
.hero {
    text-align: center;
    padding: 100px 20px;
    background: url('background.jpg') no-repeat center center;
    background-size: cover;
}

.hero h2 {
    margin: 0 0 20px 0;
    font-size: 24px;
    color: #fff;
}

.buttons {
    display: flex;
    justify-content: center;
    gap: 10px;
}

button {
    padding: 10px 20px;
    border: none;
    border-radius: 5px;
    font-size: 16px;
    cursor: pointer;
}

button.login {
    background-color: #ff0000;
    color: #fff;
}

button.signup {
    background-color: #00ff00;
    color: #fff;
}

/* Products Page */
.products {
    display: flex;
    flex-wrap: wrap;
    justify-content: space-around;
    padding: 20px;
}

.product {
    width: 200px;
    padding: 20px;
    margin: 20px;
    background-color: #222;
    border-radius: 10px;
    text-align: center;
    transition: transform 0.3s;
}

.product h3 {
    color: #ff0000;
    margin-bottom: 10px;
}

.product p {
    color: #fff;
}

.product:hover {
    transform: scale(1.05);
}

/* Footer */
footer {
    text-align: center;
    padding: 10px;
    background-color: #f00;
    color: #fff;
    position: fixed;
    bottom: 0;
    width: 100%;
}
```
#html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>People - INFOTECH</title>
    <link rel="stylesheet" href="people.css">
</head>
<body>
    <header>
        <div class="logo">
            <h1>INFOTECH</h1>
        </div>
        <nav>
            <ul>
                <li><a href="#">Home</a></li>
                <li><a href="#">Products</a></li>
                <li><a href="#" class="active">People</a></li>
                <li><a href="#">Contact</a></li>
            </ul>
            <div class="search-bar">
                <input type="text" placeholder="Enter to Search">
                <button class="search-button">Search</button>
            </div>
        </nav>
    </header>

    <main>
        <div class="people">
            <div class="person">
                <img src="c:\Users\Lenovo\Downloads\ratan tata.jfif" alt="Ratan Tata">
                <h3>Ratan Tata</h3>
                <p>CEO, Co-Founder</p>
            </div>
            <div class="person">
                <img src="c:\Users\Lenovo\Downloads\mark mama.jfif" alt="Mark zukerberg">
                <h3>Mark zukerberg</h3>
                <p>CTO, Co-Founder</p>
            </div>
            <div class="person">
                <img src="c:\Users\Lenovo\Downloads\sundar.jfif" alt="Sundar">
                <h3>Sundar</h3>
                <p>Director</p>
            </div>
            <div class="person">
                <img src="c:\Users\Lenovo\Downloads\elon musk.jfif" alt="Elon Musk">
                <h3>Elon Musk</h3>
                <p>Dy. Director</p>
            </div>
        </div>
    </main>

    <footer>
        <p>DESIGNED AND DEVELOPED BY DHARSHINI SENTHILKUMAR (212221220009)</p>
    </footer>
</body>
</html>
```
# css
```
/* General Styles */
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
    background-color: #111;
}

.logo h1 {
    color: #00ffff;
}

nav ul {
    display: flex;
    list-style-type: none;
    margin: 0;
    padding: 0;
}

nav ul li {
    margin-right: 20px;
}

nav ul li a {
    text-decoration: none;
    color: #fff;
}

nav ul li a.active {
    color: #ff0000;
}

.search-bar {
    display: flex;
    align-items: center;
}

.search-bar input {
    padding: 5px;
    border: none;
    border-radius: 3px;
    margin-right: 5px;
}

.search-bar button, .search-button {
    padding: 5px 10px;
    border: none;
    border-radius: 3px;
    background-color: #ff0000;
    color: #fff;
    cursor: pointer;
}

/* Hero Section */
.hero {
    text-align: center;
    padding: 100px 20px;
    background: url('background.jpg') no-repeat center center;
    background-size: cover;
}

.hero h2 {
    margin: 0 0 20px 0;
    font-size: 24px;
    color: #fff;
}

.hero .buttons {
    display: flex;
    justify-content: center;
}

.hero .buttons button {
    padding: 10px 20px;
    border: none;
    border-radius: 5px;
    margin: 0 10px;
    cursor: pointer;
}

.hero .buttons .login {
    background-color: #ff0000;
    color: #fff;
}

.hero .buttons .signup {
    background-color: #00ff00;
    color: #000;
}

/* Product Section */
.products {
    display: flex;
    flex-wrap: wrap;
    justify-content: space-around;
    padding: 50px 20px;
}

.product {
    flex: 1 1 30%;
    background-color: #222;
    margin: 10px;
    padding: 20px;
    border-radius: 10px;
    text-align: center;
}

.product h3 {
    color: #ff0000;
}

.product p {
    color: #fff;
}

/* People Section */
.people {
    display: flex;
    justify-content: space-around;
    padding: 50px 20px;
}

.person {
    text-align: center;
    max-width: 150px;
}

.person img {
    border-radius: 50%;
    width: 100px;
    height: 100px;
}

.person h3, .person p {
    color: #fff;
    margin: 10px 0;
}

footer {
    text-align: center;
    padding: 20px;
    background-color: #111;
    color: #ff0000;
}
```
# html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contact Us - INFOTECH</title>
    <link rel="stylesheet" href="contact.css">
</head>
<body>
    <div class="container">
        <header>
            <h1>INFOTECH</h1>
            <nav>
                <a href="#">Home</a>
                <a href="#">Products</a>
                <a href="#">People</a>
                <a class="active" href="#">Contact</a>
            </nav>
            <div class="search">
                <input type="text" placeholder="Enter to Search">
                <button>Search</button>
            </div>
        </header>
        
        <main>
            <section class="contact-us">
                <div class="form-container">
                    <h2>Contact Us</h2>
                    <form>
                        <input type="text" placeholder="Your Name" required>
                        <input type="email" placeholder="Your Email" required>
                        <button type="submit">Submit</button>
                    </form>
                </div>
                <div class="contact-info">
                    <h2>Contact Information</h2>
                    <p><strong>Address:</strong> 3RD Floor, Tower 12, FCA Building, No.18, ROOP DEVELOP CITY Phase-I, SECUNDERABAD HR IN 188854</p>
                    <p><strong>Email:</strong> rooptech.official@gmail.com</p>
                    <p><strong>Phone:</strong> 1234567890</p>
                </div>
            </section>
        </main>
        
        <footer>
            <p>DESIGNED AND DEVELOPED BY DHARSHINI SENTHILKUMAR (212221220009)</p>
        </footer>
    </div>
</body>
</html>
```
# css
```
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: Arial, sans-serif;
    background-color: #000;
    color: #fff;
}

.container {
    max-width: 1200px;
    margin: 0 auto;
    padding: 20px;
}

header {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 10px 0;
    border-bottom: 2px solid #fff;
}

header h1 {
    color: #FF0000;
}

nav a {
    color: #fff;
    text-decoration: none;
    margin: 0 10px;
}

nav a.active, nav a:hover {
    color: #FF0000;
}

.search {
    display: flex;
    align-items: center;
}

.search input {
    padding: 5px;
    border: none;
    border-radius: 5px;
}

.search button {
    padding: 5px 10px;
    margin-left: 5px;
    border: none;
    background-color: #FF0000;
    color: #fff;
    border-radius: 5px;
    cursor: pointer;
}

main {
    display: flex;
    justify-content: space-between;
    margin-top: 20px;
}

.contact-us {
    display: flex;
    justify-content: space-between;
    width: 100%;
}

.form-container, .contact-info {
    background-color: #333;
    padding: 20px;
    border-radius: 10px;
    width: 45%;
}

.form-container h2, .contact-info h2 {
    margin-bottom: 20px;
    color: #FF0000;
}

.form-container form {
    display: flex;
    flex-direction: column;
}

.form-container form input {
    padding: 10px;
    margin-bottom: 10px;
    border: none;
    border-radius: 5px;
}

.form-container form button {
    padding: 10px;
    border: none;
    background-color: #FF0000;
    color: #fff;
    border-radius: 5px;
    cursor: pointer;
}

footer {
    text-align: center;
    margin-top: 20px;
    padding: 10px;
    border-top: 2px solid #fff;
    color: #FF0000;
}
```

# output:
![Screenshot (50)](https://github.com/DHARSHINISENTHILKUMAR/html/assets/113699377/26aeb6b4-0944-4bd6-b52b-f33bcb7c3e3e)
![Screenshot (51)](https://github.com/DHARSHINISENTHILKUMAR/html/assets/113699377/b89de5f9-4e92-4946-ade3-9960255faa5e)
![Screenshot (52)](https://github.com/DHARSHINISENTHILKUMAR/html/assets/113699377/7995bfc1-2c91-47b0-8508-d8041531f2ea)
![Screenshot (53)](https://github.com/DHARSHINISENTHILKUMAR/html/assets/113699377/6bb1d6d1-5c39-46f3-8213-cd5acb194126)

