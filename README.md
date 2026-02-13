# Ex01 Portfolio
## Date:

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
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>My Portfolio</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <nav>
        <h2 class="logo">Portfolio</h2>
        <ul>
            <li><a href="#home">Home</a></li>
            <li><a href="#about">About</a></li>
            <li><a href="#skills">Skills</a></li>
            <li><a href="#projects">Projects</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </nav>

    <section id="home" class="home">
        <h1>Hi, I'm <span>THARUN</span></h1>
        <p>Cyber Security Specialist</p>
    </section>

    <section id="about" class="about">
        <h2>About Me</h2>
        <p>
            Hello! I’m <strong>Tharun</strong>, a passionate and dedicated 
            Cyber Security enthusiast with a strong interest in protecting 
            systems and networks from cyber threats.
        </p>

        <p>
            I focus on learning ethical hacking, network security, 
            vulnerability assessment, and penetration testing. I enjoy 
            understanding how security systems work and finding ways to 
            strengthen them.
        </p>

        <p>
            My goal is to become a skilled Cyber Security professional and 
            help organizations safeguard their digital assets. I am always 
            eager to learn new security tools and stay updated with the 
            latest cybersecurity trends.
        </p>
    </section>

    <section id="skills" class="skills">
        <h2>My Skills</h2>
        <ul>
            <li><strong>Network Security</strong></li>
            <li><strong>Ethical Hacking</strong></li>
            <li><strong>Penetration Testing</strong></li>
            <li><strong>Python</strong></li>
            <li><strong>Linux</strong></li>
        </ul>
    </section>

    <section id="projects" class="projects">
        <h2>Projects</h2>
        <div class="project-box">Cyber Security Awareness Website</div>
        <div class="project-box">Network Vulnerability Scanner</div>
        <div class="project-box">Password Strength Checker</div>
    </section>

    <section id="contact" class="contact">
        <h2>Contact Me</h2>
        <p>Email: tharunanand2709062gmail.com</p>
        <p>GitHub:https://github.com/Tharun270906 </p>
        <p>Phone: 1234567890</p>
    </section>

</body>
</html>

```
```
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: 'Times New Roman', Times, serif;
}

body {
    background: #0a0f1c;   /* Dark navy background */
    color: #ffffff;
}

/* Navbar */
nav {
    background: #111827;
    color: #3b82f6;
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 15px 60px;
    border-bottom: 2px solid #3b82f6;
}

nav ul {
    list-style: none;
    display: flex;
}

nav ul li {
    margin-left: 25px;
}

nav ul li a {
    color: #ffffff;
    text-decoration: none;
    transition: 0.3s ease;
}

nav ul li a:hover {
    color: #3b82f6;  /* Blue hover */
}

/* Home Section */
.home {
    height: 100vh;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    background: linear-gradient(to right, #0a0f1c, #1e3a8a);
    text-align: center;
}

.home span {
    color: #3b82f6; /* Blue highlight */
}

.home h3 {
    margin-top: 10px;
    color: #cbd5e1;
}

.home p {
    margin-top: 15px;
    color: #94a3b8;
}

/* Sections */
section {
    padding: 70px 10%;
}

section h2 {
    margin-bottom: 30px;
    font-size: 30px;
    color: #3b82f6;
}

/* About */
.about p {
    max-width: 700px;
    margin: 15px auto;
    line-height: 1.6;
    color: #cbd5e1;
}

/* Skills */
.skill {

```


## OUTPUT
![alt text](<Screenshot 2026-02-13 111642.png>)

![alt text](<Screenshot 2026-02-13 111734.png>)
## RESULT
The program for creating Portfolio using HTML and CSS is executed successfully.
