[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/TUGW0SrP)
# Welcome to the HTML5 Basics Assignment repository! 

This assignment is designed to help you build foundational knowledge of HTML5, understand its structure, and practice creating web page content using semantic elements.

## Learning Objectives

By completing this assignment, you will:

  Understand the structure and purpose of HTML5 in web development.
  Learn to create basic web page content using core HTML5 elements.
  Explore semantic HTML elements and their benefits for readability and SEO.
  Gain a basic understanding of accessibility and SEO best practices in HTML.
  
## Assignment Content
  1. HTML5 Basics
Learn the structure of an HTML document (e.g., <!DOCTYPE html>, <html>, <head>, <body>).
Explore core elements such as headings, paragraphs, lists, links, and images.
  2. Semantic HTML
Introduction to semantic tags like <header>, <footer>, <nav>, <section>, and <article>.
Learn how semantic elements improve content readability and support SEO.
  3. Accessibility and SEO Basics
Understand the importance of accessible HTML and SEO-friendly practices.
Use attributes like alt, title, and semantic structures to improve usability.

## Activities

Creating a Simple Webpage: Design a basic webpage that includes text, images, and links.
Use common HTML tags like h1, p, a, img, and ul or ol.
Structure a webpage with semantic tags such as header, footer, nav, section, and article.
Ensure the content is well-organized for readability and SEO.

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="A simple webpage showcasing HTML structure with text, images, and links.">
    <title>My Simple Webpage</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>

    <!-- Header Section -->
    <header>
        <h1>Welcome to My Simple Webpage</h1>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <!-- Main Content Section -->
    <main>
        <section id="home">
            <h2>Home Section</h2>
            <p>This is the home section of my simple webpage. You can navigate through different sections using the links in the header.</p>
            <img src="https://via.placeholder.com/400" alt="Placeholder Image" />
        </section>

        <section id="about">
            <h2>About Me</h2>
            <article>
                <h3>Who Am I?</h3>
                <p>I am a web developer passionate about creating user-friendly websites. I enjoy learning new technologies and improving my skills every day.</p>
                <a href="https://github.com/your-profile" target="_blank">Visit my GitHub Profile</a>
            </article>
        </section>

        <section id="contact">
            <h2>Contact Information</h2>
            <p>If you'd like to get in touch, feel free to send me a message or visit my social media profiles.</p>
            <ul>
                <li><a href="https://twitter.com/yourprofile" target="_blank">Twitter</a></li>
                <li><a href="https://linkedin.com/in/yourprofile" target="_blank">LinkedIn</a></li>
                <li><a href="mailto:your-email@example.com">Email</a></li>
            </ul>
        </section>
    </main>

    <!-- Footer Section -->
    <footer>
        <p>&copy; 2024 My Simple Webpage. All Rights Reserved.</p>
    </footer>

</body>
</html>

