# Ex01 Portfolio
# Name:Mopuri Ankitha
# Register Number:212223040117
## Date:30-08-2025

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
Portfolio.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Portfolio</title>
    <link rel="stylesheet" href="portfolio.css">
</head>
<body>
   
    <h1>My Portfolio</h1>
   
    
    <nav>
        <a href="portfolio.html">Home</a>
        <a href="projects.html">Projects</a>
        <a href="skills.html">Skills</a>
        <a href="contact.html">Contact</a>
    </nav>
    <hr>
    
    
<p class="intro">
I am Ankitha, a passionate third-year Computer Science student at Saveetha Engineering College.  
I enjoy exploring technology and creating projects that solve real-world problems.  
Currently, I’m learning web development and building my skills step by step to become a full-stack developer.  
</p>

    <img src="my photo.png">
    <p class="intro">Currently, I’m focusing on web development and strengthening my coding skills. I aspire to build applications that are not only functional but also user-friendly and innovative.</p>
 </body>
</html>
```
projects.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Projects</title>
    <link rel="stylesheet" href="portfolio.css">
</head>
<body>
    <h1 class="heading">My Projects</h1>
    <nav>
        <a href="portfolio.html">Home</a>
        <a href="projects.html">Projects</a>
        <a href="skills.html">Skills</a>
        <a href="contact.html">Contact</a>
    </nav>
    <hr>
    <p class="intro">
    Here are some of the projects I’ve worked on to strengthen my skills and apply my learning.  
    Each project reflects my interest in exploring new technologies.
</p>


    <div class="main">
        <div class="container1">
            <h3>Portfolio Website</h3>
            <p>A personal portfolio built using HTML and CSS showcasing my skills, projects, and contact information.</p>
        </div>

        <div class="container2">
            <h3>BMI Calculator</h3>
            <p>Developed a Simple BMI calculator using Python with Input Validation</p>
        </div>

        <div class="container3">
            <h3>Age Calculator</h3>
            <p>Developed a Console Based Age Calculator Using Python </p>
        </div>
    </div>
</body>
</html>

```
skills.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Skills</title>
    <link rel="stylesheet" href="portfolio.css">
</head>
<body>
    <h1 class="heading">
        My Skills
    </h1>
    <nav>
        <a href="portfolio.html">Home</a>
        <a href="projects.html">Projects</a>
        <a href="skills.html">Skills</a>
        <a href="contact.html">Contact</a>
    </nav>
    <hr>
    <p class="intro">
Here are some of the technical, soft, and software skills I have developed over time.  
These skills help me in building projects, collaborating effectively, and staying productive.
</p>

    <div class="main">
    <div class="container1">
        <h3>Technical Skills</h3>
        <ul>
            <li>HTML</li>
            <li>CSS</li>
            <li>Javascript</li>
            <li>C Programming</li>
            <li>Python</li>
            <li>Java</li>
        </ul>
    </div>
    <div class="container2">
        <h3>Soft Skills</h3>
        <ul>
            <li>Communication</li>
            <li>Time Management</li>
            <li>Team Work</li>
            <li>Problem Solving</li>
        </ul>
    </div>
    <div class="container3">
        <h3>Software Skills/Tools</h3>
        <ul>
            <li>Canva</li>
            <li>Microsoft Word</li>
            <li>Microsoft Powerpoint</li>
        </ul>

    </div>
    </div>

</body>
</html>
```
contact.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contact</title>
    <link rel="stylesheet" href="portfolio.css">
</head>
<body>
    <h1 class="heading">Contact Me</h1>
    <nav>
        <a href="portfolio.html">Home</a>
        <a href="projects.html">Projects</a>
        <a href="skills.html">Skills</a>
        <a href="contact.html">Contact</a>
    </nav>
    <hr>
    <p class="intro">
Feel free to reach out! Whether it’s a project idea, collaboration, or just to say hello,  
I’d love to connect with you.
</p>


    <div class="contact-box">
        <p><b>Email:</b> ankithaxxxxx@gmail.com</p>
        <p><b>LinkedIn:</b> <a href="https://www.linkedin.com/in/xxxxxxx/" target="_blank">Click here</a></p>
        <p><b>GitHub:</b> <a href="https://github.com//" target="_blank">Click here</a></p>
        <p><b>Mobile:</b> +91-XXXXXXXXXX</p>
    </div>
</body>
</html>

```
portfolio.css
```
body{
    background-color: wheat;
}
h1{
    text-align: center;
}
nav{
    display: flex;
    justify-content: flex-end;
    gap:20px;
    margin: 10px;
}
hr{
    border: 2px solid black;
}
h2{
    text-align: center;
    color:brown;
}
p{
    text-align: center;
    color:darkolivegreen
}
img {
    display: block;
    margin-left: auto;
    margin-right: auto;
    width: 200px;   
    border-radius: 500px;  
}

.main {
    display: grid;
    grid-template-columns: repeat(3, 1fr); 
    gap: 50px;
    max-width: 1000px;
    margin: 50px auto;
}

.container1, .container2, .container3 {
    border: 2px solid black;
    padding: 15px;
    border-radius: 10px;
    background-color: #f9f5e9;
    box-shadow: 2px 2px 8px rgba(0,0,0,0.1);
}

.contact-box {
    border: 2px solid black;
    padding: 20px;
    width: 400px;
    margin: 50px auto;
    text-align: center;
    border-radius: 10px;
    background-color: #f9f5e9;
    box-shadow: 2px 2px 8px rgba(0,0,0,0.1);
}
.intro{
    font-size: larger;
}
.heading{
    margin-top: 30px;
}

```
## OUTPUT
<img width="1918" height="918" alt="image" src="https://github.com/user-attachments/assets/5bdb1fc5-171d-46cc-8b35-eb82ef99472e" />

<img width="1919" height="906" alt="image" src="https://github.com/user-attachments/assets/bf859eab-71b2-4bd8-afd1-ebdae12352f7" />

<img width="1910" height="882" alt="image" src="https://github.com/user-attachments/assets/3e96dc66-cd31-4c95-8906-1f38b823b4c9" />

<img width="1918" height="891" alt="image" src="https://github.com/user-attachments/assets/d12cb904-9283-475e-ae72-09ba8582d70d" />

## RESULT
The program for creating Portfolio using HTML and CSS is executed successfully.
