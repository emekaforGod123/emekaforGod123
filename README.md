HTML:

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Emil Computer Service Limited</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <section id="home">
            <h1>Welcome to Emil Computer Service Limited</h1>
            <p>We offer top-notch computer services in Omudioha Emohua Local Government Area, Rivers State.</p>
            <button>Learn More</button>
        </section>
        <section id="about">
            <h1>About Me</h1>
            <p>My Name is Emejuru Chukwuemeka, I'm a Computer Programmer, Designer, Internet Service Provider.</p>
        </section>
        <section id="contact">
            <h1>Contact Me</h1>
            <form>
                <label for="name">Name:</label>
                <input type="text" id="name" name="name"><br><br>
                <label for="email">Email:</label>
                <input type="email" id="email" name="email"><br><br>
                <label for="message">Message:</label>
                <textarea id="message" name="message"></textarea><br><br>
                <input type="submit" value="Send Message">
            </form>
            <p>Phone Number: +2348086941019</p>
            <p>Email: chukwuemejuru99@gmail.com</p>
        </section>
    </main>
    <footer>
        <p>&copy; 2023 Emil Computer Service Limited</p>
    </footer>
</body>
</html>
```

CSS (in style.css file):

```
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
}

header {
    background-color: #FF0000;
    color: #FFFFFF;
    padding: 1em;
    text-align: center;
}

nav ul {
    list-style: none;
    margin: 0;
    padding: 0;
    display: flex;
    justify-content: space-between;
}

nav li {
    margin-right: 20px;
}

nav a {
    color: #FFFFFF;
    text-decoration: none;
}

main {
    display: flex;
    flex-direction: column;
    align-items: center;
    padding: 2em;
}

section {
    background-color: #FFFFFF;
    padding: 1em;
    margin-bottom: 20px;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
}

h1 {
    color: #FF0000;
}

button {
    background-color: #FF0000;
    color: #FFFFFF;
    border: none;
    padding: 10px 20px;
    font-size: 16px;
    cursor: pointer;
}

button:hover {
    background-color: #FF3333;
}

footer {
    background-color: #FF0000;
    color: #FFFFFF;
    padding: 1em;
    text-align: center;
    clear: both;
}
```

