# MDAP-EX_01-Portfolio
## Date: 30/04/2025
## Name: GURU PRASATH R
## Reg.no:212223040053

## AIM
To create a Portfolio using HTML and CSS.

## ALGORITHM
### STEP 1
Create an HTML file (index.html)

### STEP 2
Create a CSS file (style.css)

### STEP 3
Include a navigation bar with links to different sections.

### STEP 4
Add structured sections for introduction, about, projects, and contact details.

### STEP 5
Define global styles for fonts, colors, and layout.

### STEP 6
Style the header, navigation bar, and sections.

### STEP 7
Use Flexbox or CSS Grid for layout design.

### STEP 8
Add hover effects and transitions for interactivity.

### STEP 9
Add Images and Media.

### STEP 10
Use optimized images for a professional look.

### STEP 11
Open the HTML file in a browser to check layout and functionality.

### STEP 12
Fix styling issues and refine content placement.

### STEP 13
Deploy the Portfolio.

### STEP 14
Upload to GitHub Pages for free hosting.

## PROGRAM
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Your Portfolio</title>
    <style>
        /* Global Styles */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: Arial, sans-serif;
        }

        body {
            background-color: #f4f4f4;
            color: #333;
            line-height: 1.6;
        }

        h1, h2, h3 {
            color: #333;
        }

        a {
            text-decoration: none;
            color: inherit;
        }

        /* Header Styles */
        header {
            background-color: #333;
            color: white;
            padding: 20px;
            text-align: center;
        }

        nav {
            display: flex;
            justify-content: space-between;
            align-items: center;
        }

        nav .logo h1 {
            font-size: 2rem;
        }

        .nav-links {
            list-style: none;
            display: flex;
        }

        .nav-links li {
            margin-left: 20px;
        }

        .nav-links a {
            color: white;
            font-size: 1.1rem;
            padding: 10px 20px;
            transition: background-color 0.3s;
        }

        .nav-links a:hover {
            background-color: #555;
        }

        /* About Section */
        #about {
            background-color: #fff;
            padding: 50px 20px;
            text-align: center;
        }

        #about img {
            border-radius: 50%;
            width: 200px;
            height: 200px;
            margin-top: 20px;
        }

        /* Projects Section */
        #projects {
            background-color: #f4f4f4;
            padding: 50px 20px;
            text-align: center;
        }

        .project-container {
            display: flex;
            justify-content: space-around;
            flex-wrap: wrap;
        }

        .project {
            background-color: #fff;
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            margin: 20px;
            width: 300px;
            text-align: center;
            transition: transform 0.3s;
        }

        .project:hover {
            transform: scale(1.05);
        }

        .project img {
            width: 100%;
            height: 200px;
            object-fit: cover;
            border-radius: 8px 8px 0 0;
        }

        .project-info {
            padding: 20px;
        }

        .project-info h3 {
            margin-bottom: 10px;
        }

        /* Contact Section */
        #contact {
            background-color: #fff;
            padding: 50px 20px;
            text-align: center;
        }

        form {
            display: flex;
            flex-direction: column;
            align-items: center;
        }

        form input, form textarea {
            width: 300px;
            padding: 10px;
            margin: 10px 0;
            border-radius: 5px;
            border: 1px solid #ddd;
            font-size: 1rem;
        }

        form button {
            padding: 10px 20px;
            background-color: #333;
            color: white;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            transition: background-color 0.3s;
        }

        form button:hover {
            background-color: #555;
        }

        /* Footer Styles */
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 10px;
            margin-top: 20px;
        }
    </style>
</head>
<body>
    <!-- Header Section -->
    <header>
        <nav>
            <div class="logo">
                <h1> </h1>
            </div>
            <ul class="nav-links">
                <li><a href="#about">About</a></li>
                <li><a href="#projects">Projects</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <!-- About Section -->
    <section id="about">
        <div class="about-content">
            <h2>About Me</h2>
            <p>Hi, I'm [Guru Prasath R], a Forex Trader and My own trading bot selling .</p>
            <img src="guru 6.jpg" alt="guru 6">
        </div>
    </section>

    <!-- Projects Section -->
    <section id="projects">
        <h2>My Projects</h2>
        <div class="project-container">
            <div class="project">
                <img src="trading bot.jpeg" alt="trading bot">
                <div class="project-info">
                    <h3>Project 1</h3>
                    <p>I m creating my own trading bot 24 hours running bot. </p>
                </div>
            </div>
            <div class="project">
                <img src="gold profit.jpg" alt="gold profit">
                <div class="project-info">
                    <h3>Project 2</h3>
                    <p>My trading profit second project 100$ invset and running 400$.</p>
                </div>
            </div>
            
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact">
        <h2>Contact Me</h2>
        <form action="#" method="POST">
            <input type="text" name="name" placeholder="Your Name" required>
            <input type="email" name="email" placeholder="Your Email" required>
            <textarea name="message" placeholder="Your Message" required></textarea>
            <button type="submit">Send Message</button>
        </form>
    </section>

    <!-- Footer -->
    <footer>
        <p>&copy; 2025 Your Name. All rights reserved.</p>
    </footer>
</body>
</html>


## OUTPUT
![Screenshot 2025-04-30 091049](https://github.com/user-attachments/assets/6cdcd3d6-0604-4eb1-bb69-746bbb1015df)

![Screenshot 2025-04-30 091123](https://github.com/user-attachments/assets/d83be01e-de2c-4b8c-b3b0-053c5470ef50)

![Screenshot 2025-04-30 091142](https://github.com/user-attachments/assets/a0b002f9-bc57-460d-8b5b-5f91c2b68d8a)




## RESULT
The program for creating Portfolio using HTML and CSS is executed successfully.
