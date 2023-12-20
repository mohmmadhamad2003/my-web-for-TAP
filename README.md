# my-web-for-TAP
<!DOCTYPE html>
<html>
  <head>
    <title>he guys</title>
    <link rel="stylesheet" href="styles.css" />
  </head>
  <body>
      <h1 class="title">he guys! </h1>
      <p id="currentTime"></p>
      <script src="script.js"></script>
  </body>
</html>
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>me Name is mohmmad hamad - Portfolio</title>
    <link rel="stylesheet" href="styles.css">
</head>

<body>
    <header>
        <div class="container">
            <h1>me Name is mohmmad hamad</h1>
            <p>Web Developer</p>
        </div>
    </header>

    <section id="about">
        <div class="container">
            <h2>About Me</h2>
            <p>
                "Welcome to my program. I am a passionate programmer with high ambitions.
                I currently design simple websites,
                but I aspire to delve deeper into programming; it's my dream.
                I am studying artificial intelligence engineering,
                hoping to gain experience in learning and working."
            </p>
        </div>
    </section>

    <section id="skills">
        <div class="container">
            <h2>Skills</h2>
            <ul>
                <li>HTML5</li>
                <li>CSS3</li>
                <li>JavaScript</li>
                <li>Responsive Design</li>
                <1i>c++</1i>
                
            </ul>
        </div>
    </section>

    <section id="portfolio">
        <div class="container">
            <h2>Portfolio</h2>
            <div class="portfolio-item">
                <img src="project1.jpg" alt="https://srtarabic.blogspot.com/2020/11/2021_18.html 1">
                <p>Project 1 Description</p>
            </div>
            <div class="portfolio-item">
                <img src="project2.jpg" alt="https://bitcoin1213.blogspot.com/2020/05/5-faucet.html 2">
                <p>Project 2 Description</p>
            </div>
            <!-- Add more portfolio items as needed -->
        </div>
    </section>

    <footer>
        <div class="container">
            <p>&copy; 2023 Your Name. All rights reserved.</p>
        </div>
    </footer>
</body>

</html>
body {
    font-family: 'Arial', sans-serif;
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

.container {
    max-width: 960px;
    margin: 0 auto;
    padding: 0 20px;
}

header {
    background-color: #3498db;
    color: #fff;
    text-align: center;
    padding: 40px 0;
}

header h1 {
    margin: 0;
}

section {
    padding: 60px 0;
}

section h2 {
    text-align: center;
}

section p {
    text-align: justify;
}

ul {
    list-style: none;
    padding: 0;
}

ul li {
    display: inline-block;
    margin: 0 10px;
}

footer {
    background-color: #2c3e50;
    color: #fff;
    text-align: center;
    padding: 20px 0;
}
