Resume — SAJA PT

This project is a simple and elegant resume website created using HTML for structure and an external CSS file for styling.
It’s designed to display personal details, education, skills, and projects in a clean, professional format.

📄 Project Description

The project contains a single HTML file (index.html) that holds all the content of the resume.
It is organized into meaningful sections to keep it neat and easy to maintain.

The resume includes:

Header with profile photo and contact details

Professional Summary

Education Background

Technical Skills

Projects Portfolio

The design is lightweight and responsive, which means it can adapt to different screen sizes (desktop, tablet, or phone).

🔍 Code Breakdown

Below is a section-by-section explanation of how the HTML code works.

1. <!DOCTYPE html>

This tells the browser that the file is an HTML5 document.
It ensures the page is interpreted using modern HTML standards.

2. <html lang="en">

The opening <html> tag wraps all the content of the web page.

The lang="en" attribute specifies the language of the document as English.

3. <head> Section

The <head> contains metadata about the web page (not displayed on the page directly).

Key elements inside <head>:

<meta charset="UTF-8"> — Makes sure the page can display a wide range of characters (including emojis like 📍 or ✉️).

<title>Resume — SAJA PT</title> — Sets the title shown on the browser tab.

<meta name="viewport" content="width=device-width, initial-scale=1">
Ensures the page scales correctly on phones and tablets.

<link rel="stylesheet" href="css/style.css">
Links an external CSS file (style.css) stored in the css folder. This file is used to style the page (colors, fonts, layout, etc.).

4. <body> Section

Everything visible on the page is inside the <body> tag.

Main Layout
<div class="container">
  <main class="card">
    ...
  </main>
</div>


<div class="container"> acts as the overall wrapper that keeps everything centered and organized.

<main class="card"> is the main content area styled like a card (handled by CSS).

5. <header> — Profile Header and Contact Information

The header section holds the name, title, photo, and contact details.

<div class="profile-header">
  <div class="title">
    <h1>SAJA PT</h1>
    <p class="subtitle">Mvoc software Apllication development</p>
  </div>
  <div class="photo">
    <img src="assets/PIC.jpg" alt="Profile Picture">
  </div>
</div>


<h1> — Displays the name SAJA PT in large text.

<p class="subtitle"> — Shows the title Mvoc Software Application Development as a subtitle.

<img src="assets/PIC.jpg"> — Displays the profile picture stored in the assets folder.

Contact Section
<div class="contact">
  <div class="left-contact">
    <span>📍 Kochi, India</span>
    <span>✉️ <a href="mailto:sajaabbaspt@gmail.com">sajaabbaspt@gmail.com</a></span>
  </div>
  <div class="right-contact">
    <span>☎️ +91 8138800371</span>
    <span>🔗 <a href="https://github.com/Saja-abbas">GitHub: Saja-abbas</a></span>
  </div>
</div>


Divided into two parts: left-contact (location and email) and right-contact (phone and GitHub link).

mailto: makes the email clickable so it opens the default email app.

GitHub link opens in a new tab because of target="_blank".

6. Professional Summary Section
<section class="section">
  <h2>Professional Summary</h2>
  <p class="summary"> ... </p>
</section>


This section provides a brief introduction about education, skills, and professional interests.

7. Education Section
<section class="section">
  <h2>Education</h2>
  <div class="item">
    <h3>Mvoc Software Application Development</h3>
    <div>Cochin University of Science and Technology, Kochi, Kerala</div>
    <div class="time">July-10-2025</div>

    <h3>Bachelor of Computer Applications</h3>
    <div class="loc">Malabar College of Advanced Studies, Vengara, Malappuram, Kerala</div>
    <div class="time">Sept 2022 – Mar 2025</div>
  </div>
</section>


Lists the educational qualifications with institute names and timeline.

8. Skills Section
<section class="section">
  <h2>Skills</h2>
  <div>
    <span class="pill">Flutter</span>
    <span class="pill">MySQL</span>
    ...
  </div>
</section>


Displays technical and soft skills in pill-shaped tags for readability.
Examples: Flutter, MySQL, Python Django, Adaptability.

9. Projects Section
<section class="section">
  <h2>Projects</h2>

  <div class="item">
    <h3>MedLens <span class="tagline">“Scan, Analyze, and Stay Ahead of Illness”</span></h3>
    <div class="time">Jul 2024 – Jan 2025</div>
    <ul>
      <li>Developed a health app...</li>
      ...
    </ul>
  </div>
</section>


Highlights major projects with:

Project Title

Tagline

Timeline

Bullet-point features

Technologies used

Two projects are showcased:

MedLens — A health app using Machine Learning and Flutter.

Maternity Cue — A pregnancy tracking app using Flutter and Firebase.

📂 Folder Structure
resume-project/
│
├── index.html        # Main resume page
├── css/
│   └── style.css     # Stylesheet for design
└── assets/
    └── PIC.jpg       # Profile picture

🖥️ How It Works

When you open index.html in a browser, the HTML loads the content.

The CSS file applies styling (colors, fonts, layout).

The image is displayed from the assets folder.

Links for email and GitHub are clickable and interactive.

🚀 How to View

Clone the repository or download the files.

Open index.html in any web browser.

Make sure the css folder and assets folder stay in the same directory as index.html.

✨ Customization

You can easily modify:

Your name, title, contact info in the <header> section.

Add/remove skills using <span class="pill">.

Add new projects by copying the <div class="item"> block.

Change the profile picture in the assets folder.

📬 Author

Name: SAJA PT

Email: sajaabbaspt@gmail.com

GitHub: Saja-abbas

📜 License

Free to use and modify for personal or academic purposes.
