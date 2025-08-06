# MDAP-EX_01-Portfolio
## Date: 06.08.2025

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
### index.html :
```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta
      charset="UTF-8"
      name="viewport"
      content="width=device-width,initial-scale=1.0"
    />
    <title>Aswin Balakrishnan | Frontend Web Designer</title>
    <link rel="stylesheet" href="style.css" />
  </head>

  <body>
    <!-- NAVBAR SECTION -->
    <div class="navbar">
      <nav>
        <a href="index.html">HOME</a>
        <a href="#gallery">PROJECTS</a>
        <a href="#aboutme">ABOUT ME</a>
        <a href="#review">TESTIMONIALS</a>
      </nav>
    </div>

    <!-- HERO SECTION -->
    <section class="hero-section">
      <div class="hero-overlay"></div>
      <div class="hero-content">
        <h1>WELCOME TO<br /><span>My Portfolio</span></h1>
        <p>
          I’m <span>Aswin</span>, a frontend web designer passionate about clean
          code and elegant interfaces.
        </p>
        <button class="cta-btn">Let's Connect</button>
      </div>
    </section>

    <!-- QUOTE SECTION -->
    <section class="quote-section">
      <div class="quote-body">
        <h2 class="quote">
          “Design is not just what it looks like and feels like. Design is how
          it works.”
        </h2>
        <p class="meaning">
          Good design is invisible — it's about solving problems and creating
          seamless experiences.
        </p>
        <p class="author">~ Steve Jobs</p>
      </div>
    </section>

    <!-- ABOUT ME SECTION -->
    <section class="section3" id="aboutme">
      <div class="section3-div">
        <h4 class="section3-small-title">ABOUT ME</h4>
        <h1 class="section3-title">A Quick Introduction</h1>
        <p class="section3-p">
          Hi, I'm Aswin, a frontend web designer with a love for intuitive user
          experiences and semantic HTML/CSS. I design clean, responsive websites
          with a deep focus on accessibility and performance.
        </p>
        <p class="section3-p">
          My goal is to blend creativity with structure, bringing digital ideas
          to life through thoughtful design and scalable code.
        </p>
      </div>
      <div class="section3-img">
        <img src="./images/bg.jpg" alt="Portfolio Image" />
      </div>
    </section>

    <!-- VISION SECTION -->
    <section class="sidebysidesec">
      <div class="section2">
        <h2>Designing with Purpose</h2>
        <p>
          I believe in designing experiences that are simple, elegant, and
          human-centric. Whether it’s a website, a landing page, or a UI concept
          — every detail matters.
        </p>
      </div>
    </section>

    <!-- INSPIRATION SECTION -->
    <section class="section1">
      <div class="section1-div">
        <h4 class="section1-small-title">My Approach</h4>
        <h1 class="section1-title">design with clarity</h1>
        <p class="section1-paragraph">
          I take a structured approach to each project — from wireframes and
          component design to clean code and smooth deployment. My aesthetic is
          minimal, my tools are modern, and my mindset is user-first.
        </p>
      </div>
      <div class="section1-img">
        <img src="./images/bg.jpg" alt="Portfolio Work" />
      </div>
    </section>

    <!-- PROJECT PREVIEW -->
    <section class="gallery-preview" id="gallery">
      <h4 class="small-title">Project Highlights</h4>
      <h1 class="title">some of my favorite builds</h1>
      <div class="gallery-row row1">
        <div class="image-row">
          <img src="./images/bg.jpg" alt="Project 1" />
          <img src="./images/bg.jpg" alt="Project 2" />
          <img src="./images/bg.jpg" alt="Project 3" />
        </div>
      </div>
      <div class="gallery-row row2">
        <div class="image-row">
          <img src="./images/bg.jpg" alt="Project 4" />
          <img src="./images/bg.jpg" alt="Project 5" />
          <img src="./images/bg.jpg" alt="Project 6" />
        </div>
      </div>
      <div class="button">
        <a href="./gallery.html" class="btn">View All Projects</a>
      </div>
    </section>

    <!-- REVIEWS -->
    <section class="reviews" id="review">
      <h4 class="small-title">Feedback</h4>
      <h1 class="title">What People Are Saying</h1>

      <div class="review-grid">
        <div class="review-item">
          <p class="review-text">
            Aswin’s design sense is modern, clean, and impactful. Great
            communicator too.
          </p>
          <span class="review-author">– Kavya R., UI/UX Lead</span>
        </div>

        <div class="review-item">
          <p class="review-text">
            His websites are fast, responsive, and beautifully coded. Highly
            recommended!
          </p>
          <span class="review-author">– Ramesh T., Developer</span>
        </div>

        <div class="review-item">
          <p class="review-text">
            A rare mix of creativity and technical know-how. Aswin delivers!
          </p>
          <span class="review-author">– Sneha A., Project Manager</span>
        </div>
      </div>
    </section>

    <!-- FOOTER -->
    <footer class="footer">
      <div class="footer-content">
        <div class="footer-left">
          <div class="footer-logo-text">
            <p class="footer-text">
              A portfolio that reflects my love for clean interfaces and
              intentional design.
            </p>
          </div>
        </div>
        <div class="footer-columns">
          <div class="footer-column">
            <h4>Quick Links</h4>
            <a href="index.html">Home</a>
            <a href="faq.html">FAQs</a>
            <a href="#">Contact</a>
          </div>
        </div>
      </div>

      <hr class="centered-line" />

      <div class="footer-bottom">
        <p>
          © 2025 Aswin Balakrishnan<br />
          All rights reserved.
        </p>
        <div class="footer-links">
          <a href="#">Privacy Policy</a>
          <a href="#">Terms & Conditions</a>
        </div>
      </div>
    </footer>
  </body>
</html>
```

### style.css:
```css
@import url('https://fonts.googleapis.com/css2?family=Poppins:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&family=Roboto:ital,wght@0,100..900;1,100..900&display=swap');

/* === Root Variables === */
:root {
  /* Colors */
  --primary: #ffbe03;
  --white: #ffffff;
  --button-hover: #e0a800;
  --black-txt: #000000;
  --hero-overlay: rgba(20, 20, 30, 0.4);
  --soft-bg: #dcdff7;
  --soft-grey: #5f5f5f;

  /* Attributes */
  --rounded: 1.4rem;
  --shadow: 0 0.25rem 1.5rem rgba(0, 0, 0, 0.1);
  --max-section-width: 90%;
  --section-padding: 3rem 2rem;
}

/* === General Reset and Defaults === */
*{
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  /*outline: 1px solid red;*/
}

body {
  background: var(--white);
  max-width: 100%;
  overflow-x: hidden;
}

html {
  max-width: 100%;
  margin-top: 7rem;
  overflow-x: hidden;
  scroll-behavior: smooth;
}

/* Headings and Paragraphs */
h1,
h2,
h3,
h4,
h5,
h6 {
  font-family: "Poppins", sans-serif;
}

p {
  font-family: "Roboto", sans-serif;
}

/* Italicized Span */
span {
  font-style: italic;
  color: var(--primary);
}


/* Links */
a {
  text-decoration: none;
  font-family: "Roboto", sans-serif;
}

a:hover {
  text-decoration: underline;
}

/* === Sections, Titles and More === */
section {
  width: var(--max-section-width);
  padding: var(--section-padding);
  margin: 0 auto 6rem auto !important;
  overflow-x: hidden;
  overflow-y: hidden;
  max-width: 90%;
}

.small-title {
  font-size: 1.5rem;
  text-align: center;
  text-transform: uppercase;
  padding-bottom: 1rem;
  color: var(--soft-grey) !important;
}

.title {
  text-transform: uppercase;
  text-align: center;
  font-size: 3rem;
  padding-bottom: 1.5rem;
  font-weight: 800;
}

/* Quote Section */
.quote-section {
  margin: 0 auto;
  height: auto;
  max-height: 100vh;
}

.quote,
.author,
.meaning {
  text-align: center;
}

.quote {
  line-height: 1.5;
  padding-bottom: 2rem;
}

.meaning {
  text-align: center;
  padding-bottom: 2rem;
  font-weight: 400;
  font-size: 1.2rem !important;
  line-height: 2;
  color: var(--soft-grey);
}

.author {
  font-style: italic;
  font-weight: normal;
  font-size: 1rem;
  color: var(--soft-grey);
}

/* --- Section 01 --- */
.section1 {
  background-color: var(--soft-bg);
  border-radius: var(--rounded);
  overflow: hidden;
}

.section1-div {
  padding: var(--section-padding);
  height: auto;
  max-height: 100vh;
}

.section1-small-title {
  font-size: 1.5rem;
  text-align: center;
  text-transform: uppercase;
  padding-bottom: 1rem;
  margin-bottom: 0.5rem;
  color: var(--soft-grey) !important;
}

.section1-title {
  text-transform: uppercase;
  text-align: center;
  font-size: 3rem;
  padding-bottom: 1rem;
  font-weight: 800;
  margin-bottom: 0.5rem;
}

.section1-paragraph {
  text-align: center;
  font-size: 1rem;
  line-height: 1.5rem;
  padding-bottom: 1rem;
  max-width: 900px;
  margin: 0 auto;
}

.section1-img {
  aspect-ratio: 4 / 3;
  width: 50%;
  min-height: 50vh;
  margin: 0 auto 3rem auto;
  display: flex;
  overflow: hidden;
  justify-content: center;
  border-radius: var(--rounded);
}

.section1-img img {
  width: 100%;
  height: 100%;
  object-fit: cover;
}

/* --- Section 02 --- */
.section2 {
  display: flex;
  justify-content: space-between;
  gap: 2rem;
}

.section2 h2 {
  text-align: left;
  line-height: 2.5rem;
  font-size: 2rem;
  font-weight: 700;
  width: 30%;
  color: var(--black-txt);
}

.section2 p {
  text-align: left;
  line-height: 2rem;
  font-size: 1rem;
  width: 60%;
  color: var(--soft-grey);
}

/* --- Section 03 --- */
.section3 {
  display: flex;
  justify-content: space-between;
  background-color: var(--soft-bg);
  border-radius: var(--rounded);
  overflow: hidden;
  padding: var(--section-padding);
  gap: 3rem;
  align-items: center;
}

.section3-div {
  padding: 0;
  flex: 1;
}

.section3-small-title {
  font-size: 1.5rem;
  text-align: left;
  text-transform: uppercase;
  padding-bottom: 1rem;
  color: var(--soft-grey) !important;
}

.section3-title {
  text-transform: uppercase;
  text-align: left;
  font-size: 3rem;
  padding-bottom: 1.5rem;
  font-weight: 800;
  color: var(--black-txt);
}

.section3-p {
  padding-bottom: 1rem;
  text-align: left;
  font-size: 1rem;
  line-height: 1.5rem;
  max-width: 50ch;
  color: var(--soft-grey);
}

.section3-img {
  aspect-ratio: 4 / 3;
  width: 50%;
  height: 50vh;
  margin: 0 auto;
  display: flex;
  justify-content: center;
  overflow: hidden;
  border-radius: var(--rounded);
}

.section3-img img {
  width: 100%;
  height: 100%;
  object-fit: cover;
}

/* === Navbar === */
.navbar {
  position: fixed;
  top: 1rem;
  left: 0;
  right: 0;
  width: 98%;
  z-index: 100;
  font-family: "Roboto", sans-serif;
  background: var(--white);
  border-radius: var(--rounded);
  box-shadow: var(--shadow);
  padding: 1.3rem 3rem 1.3rem 2.2rem;
  display: flex;
  justify-content: center;
  margin: 0 auto;
}

.navbar nav a {
  color: var(--soft-grey);
  text-decoration: none;
  margin-left: 2.4rem;
  font-size: 1rem;
  transition: color 0.2s;
}

.navbar nav a:hover {
  font-weight: 800;
  border-bottom: 2px solid var(--primary);
}

/* === Hero Section === */

.hero-section {
  position: relative;
  min-height: 80vh;
  display: flex;
  align-items: flex-end;
  background: url(../images/bg.jpg);
  color: var(--white);
  background-size: cover;
  background-position: center;
  border-radius: var(--rounded);
  overflow: hidden;
}

.hero-overlay {
  position: absolute;
  inset: 0;
  background: var(--hero-overlay);
  border-radius: inherit;
  z-index: 1;
}

.hero-content {
  position: relative;
  z-index: 2;
  padding: 2.5rem;
  max-width: 50rem;
  padding-bottom: 10rem;
}

.hero-content h1 {
  font-size: 3rem;
  font-weight: bold;
  line-height: 1.15;
  margin-bottom: 1rem;
  letter-spacing: 1.15px;
}

.hero-content h1 span {
  font-style: normal;
}

.hero-content p {
  font-size: 1.08rem;
  opacity: 0.85;
  line-height: 2;
  margin-bottom: 1.5rem;
  letter-spacing: 1.15px;
}

/* CTA and button styles */
.cta-btn,
.btn {
  padding: 0.8rem 1.7rem;
  background: var(--primary);
  font-family: "Roboto", sans-serif;
  color: var(--black-txt);
  font-weight: 600;
  border: none;
  border-radius: 0.5rem;
  text-decoration: none;
  font-size: 1.1rem;
  cursor: pointer;
  transition: background 0.21s;
}

.cta-btn:hover,
.btn:hover {
  background: var(--button-hover);
}

/* === Gallery Section === */

/* Gallery Preview Row */

.gallery-row {
  display: flex;
  justify-content: center;
  margin: 2rem 0;
}

.row1 {
  padding-right: 10%;
}

.row2 {
  padding-left: 10%;
}

.image-row {
  display: flex;
  flex-wrap: wrap;
  gap: 1.5rem;
  justify-content: center;
}

.image-row img {
  aspect-ratio: 1 / 1;
  width: 12rem;
  border-radius: var(--rounded);
  box-shadow: var(--shadow);
  object-fit: cover;
}

/* Gallery Button */
.button {
  display: flex;
  justify-content: center;
  padding-top: 1rem;
  padding-bottom: 1rem;
}


/* === Reviews Section === */
.reviews {
  padding: var(--section-padding);
  margin-bottom: 6rem;
}

.review-grid {
  display: flex;
  flex-wrap: wrap;
  gap: 2rem;
  padding-top: 2rem;
  justify-content: center;
  position: relative;
}

.review-item {
  background: var(--white);
  border-radius: 1.2rem;
  box-shadow: var(--shadow);
  padding: 2rem;
  max-width: 22rem;
  position: relative;
  animation: floatUp 1s ease-out both;
}

/* Optional vertical offset for a nice staggered layout */
.review-item:nth-child(1),
.review-item:nth-child(3) {
  transform: translateY(20px);
}

.review-item:nth-child(2){
  transform: translateY(-10px);
}

.review-text {
  font-size: 1.1rem;
  line-height: 1.2;
  margin-bottom: 1rem;
  color: var(--soft-grey);
  quotes: "“" "”" "‘" "’";
}

.review-text::before {
  content: open-quote;
  font-size: 2rem;
  vertical-align: -0.4rem;
  color: var(--primary);
}

.review-text::after {
  content: close-quote;
  font-size: 2rem;
  vertical-align: -0.4rem;
  color: var(--primary);
}

.review-author {
  font-size: 0.9rem;
  opacity: 0.6;
  font-style: italic;
  color: var(--black-txt);
}


/* === Footer Section === */
.footer {
  background-color: var(--white);
  padding: 1.5rem 3.5rem;
  border-radius: var(--rounded);
  width: 95%;
  box-shadow: var(--shadow);
  margin: 0 auto;
  font-family: "Roboto", sans-serif;
  margin-bottom: 3rem;
}

.footer-content {
  display: flex;
  flex-direction: row;
  justify-content: space-between;
  align-items: center;
  gap: 5rem;
  margin: 2rem 0;
}

.footer-left {
  display: flex;
  flex-direction: column;
  justify-content: space-between;
  gap: 1rem;
}

.footer-logo-text {
  display: flex;
  flex-direction: column;
  align-items: flex-start;
  gap: 1rem;
}

.footer-text {
  font-size: 0.95rem;
  color: var(--soft-grey);
  max-width: 350px;
  line-height: 1.5;
}

.footer-column {
  display: flex;
  flex-direction: column;
  justify-content: space-between;
  gap: 0.8rem;
}

.footer-column h4 {
  font-size: 1.5rem;
  font-weight: bold;
  margin-bottom: 1rem;
  color: var(--black-txt);
}

.footer-column a {
  text-decoration: none;
  color: var(--primary);
  font-size: 1.1rem;
}

.footer-column a:hover {
  text-decoration: underline;
}

.centered-line {
  width: 100%;
  height: 0.1rem;
  background-color: var(--soft-grey);
  border: none;
  margin: 2rem auto;
}

.footer-bottom {
  display: flex;
  flex-direction: row;
  justify-content: space-between;
  width: 100%;
  align-items: center;
  line-height: 1.5;
  font-size: 0.9rem;
  color: var(--soft-grey);
}

.footer-links {
  display: flex;
  justify-content: flex-end;
  gap: 1rem;
  align-items: center;
}

.footer-links a {
  text-decoration: none;
  color: var(--black-txt);
  font-weight: 600;
  transition: color 0.2s ease;
}

.footer-links a:hover {
  text-decoration: underline;
  color: var(--primary);
}

/* === Accessibility & Interaction Enhancements === */
.navbar nav a:focus,
.cta-btn:focus,
.btn:focus{
  outline: 3px solid var(--primary);
  outline-offset: 2px;
}

/* Clickable areas - added padding for better touch targets */
.navbar nav a,
.cta-btn,
.btn {
  padding: 0.5rem 1rem;
}
```


## OUTPUT
### The below images are some screenshots of the web design.
<img width="1919" height="673" alt="Screenshot 2025-08-06 195442" src="https://github.com/user-attachments/assets/ade5afcd-e21d-47b8-b3a5-d76857671a3b" />
<img width="1919" height="855" alt="Screenshot 2025-08-06 195436" src="https://github.com/user-attachments/assets/8da66250-2dde-49d6-8aef-6b73f4a7502b" />
<img width="1917" height="1028" alt="Screenshot 2025-08-06 195426" src="https://github.com/user-attachments/assets/9097ce29-a6d9-4e2a-8ba9-782601df64d2" />
<img width="1919" height="1030" alt="Screenshot 2025-08-06 195416" src="https://github.com/user-attachments/assets/f199bdac-9a8c-4d04-a8da-f92fee50f113" />
<img width="1919" height="1029" alt="Screenshot 2025-08-06 195408" src="https://github.com/user-attachments/assets/68fd2d2b-a261-4cbc-a18e-0a5b44498c93" />
<img width="1918" height="1022" alt="Screenshot 2025-08-06 195356" src="https://github.com/user-attachments/assets/aeae8f2d-92ca-4422-9ea2-efa30202ca61" />
<img width="1919" height="1029" alt="Screenshot 2025-08-06 195343" src="https://github.com/user-attachments/assets/d0f87d77-b83c-4a40-b617-c93d0c41b04a" />
<img width="1919" height="1030" alt="Screenshot 2025-08-06 195328" src="https://github.com/user-attachments/assets/9ab4f69f-4c83-432c-8412-170760eb1743" />



## RESULT
The program for creating Portfolio using HTML and CSS is executed successfully.


### Name : ASWIN B
### Register Number : 212224110007
