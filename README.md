# CSS-Margin-And-Padding-Features
CSS, Margin, And Padding Features
HTML:
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Personal Website</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Ray Kipkorir</h1>
    </header>
    
    <section class="introduction">
        <h2>Introduction</h2>
        <p>Hello, I'm Ray Kipkorir. I'm a web developer with a passion for creating responsive and user-friendly websites.</p>
    </section>

    <section class="skills">
        <h2>Skills</h2>
        <ul>
            <li>HTML</li>
            <li>CSS</li>
            <li>JavaScript</li>
            <li>Responsive Design</li>
            <li>UI/UX Design</li>
        </ul>
    </section>

    <footer>
        <h2>Contact</h2>
        <ul>
            <li>Email: rayloxx3@gmail.com</li>
            <li><a href="https://linkedin.com/in/rayloxx">LinkedIn</a></li>
            <li><a href="https://twitter.com/1Ray_Kipkorir">Twitter</a></li>
        </ul>
    </footer>
</body>
</html>

CSS
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
}

header {
    background-color: #333;
    padding: 20px;
    color: white;
    text-align: center;
}

.introduction {
    background-color: #f2f2f2;
    padding: 20px;
    margin: 20px 0;
}

.skills {
    background-color: #ddd;
    padding: 20px;
    margin: 20px 0;
}

.skills ul {
    list-style: none;
    padding: 0;
}

.skills li {
    border: 1px solid #999;
    padding: 10px;
    margin-bottom: 10px;
}

footer {
    background-color: #333;
    color: white;
    padding: 20px;
    text-align: center;
}

footer ul {
    list-style: none;
    padding: 0;
}

footer ul li {
    margin-bottom: 10px;
}

footer a {
    color: white;
    text-decoration: none;
}

