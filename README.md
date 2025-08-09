# My-Protofolio-
My own protofolio website 
# My Portfolio

A clean, mobile-friendly personal portfolio template built with plain HTML & CSS — ready to edit on your phone and deploy on Vercel.

> Quick: edit `index.html` and `style.css` in Acode (or any mobile code editor), push to GitHub, then import the repo on Vercel to go live.

---

## What’s inside
- `index.html` — main page (placeholders ready for your name, about, projects, contact, etc.)
- `style.css`  — styles & mobile-friendly layout
- `README.md`  — (this file)
- `.gitignore` — optional (recommended to add if you include build files later)

---

## How to customize (mobile-friendly)
1. Install **Acode** (or any file editor) on your phone.  
2. Open the `index.html` file and replace placeholder comments like `<!-- Your Name -->` with your details.  
3. Edit colors, fonts or spacing in `style.css` if you want a different look.  
4. Save files.

---

## How to push to GitHub (using GitHub mobile app)
1. Open **GitHub** app → tap **+** → **New repository** → name it (e.g., `portfolio`) → create.  
2. Open the repo → tap **Add file** → **Create new file** → paste the contents of `index.html` → commit.  
3. Repeat for `style.css` and `README.md`.  
> Tip: You can also upload files directly from Acode (Export → Upload to GitHub) if the editor supports it.

---

## Deploy on Vercel (mobile)
1. Open your phone browser and go to **vercel.com** (or use Vercel app).  
2. Sign in with **GitHub**.  
3. Click **New Project** → import your `portfolio` repo → **Deploy**.  
4. After deploy, Vercel gives you a live URL like `https://your-repo-name.vercel.app`. Share it!

---

## Optional — Use Git (if you prefer terminal on phone)
If you have Termux / a terminal that supports Git:
```bash
git clone https://github.com/<your-username>/<your-repo>.git
# edit files locally with your editor
git add .
git commit -m "Initial portfolio"
git push origin main

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title><!-- Your Name --> - Portfolio</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>

  <!-- HEADER -->
  <header>
    <div class="container">
      <h1><!-- Your Name --></h1>
      <p><!-- Your Tagline --></p>
    </div>
  </header>

  <!-- NAVIGATION -->
  <nav>
    <a href="#about">About</a>
    <a href="#education">Education</a>
    <a href="#experience">Experience</a>
    <a href="#projects">Projects</a>
    <a href="#skills">Skills</a>
    <a href="#contact">Contact</a>
  </nav>

  <!-- ABOUT -->
  <section id="about" class="container">
    <h2>About Me</h2>
    <p><!-- Short intro about yourself --></p>
  </section>

  <!-- EDUCATION -->
  <section id="education" class="container">
    <h2>Education</h2>
    <ul>
      <li><!-- Your education details --></li>
    </ul>
  </section>

  <!-- EXPERIENCE -->
  <section id="experience" class="container">
    <h2>Experience</h2>
    <ul>
      <li><!-- Internship/Job details --></li>
    </ul>
  </section>

  <!-- PROJECTS -->
  <section id="projects" class="container">
    <h2>Projects</h2>
    <ul>
      <li><!-- Project 1 --></li>
      <li><!-- Project 2 --></li>
    </ul>
  </section>

  <!-- SKILLS -->
  <section id="skills" class="container">
    <h2>Skills</h2>
    <ul>
      <li><!-- Skill 1 --></li>
      <li><!-- Skill 2 --></li>
    </ul>
  </section>

  <!-- CONTACT -->
  <section id="contact" class="container">
    <h2>Contact</h2>
    <p>Email: <!-- Your Email --></p>
    <p>GitHub: <a href="#"><!-- GitHub Link --></a></p>
    <p>LinkedIn: <a href="#"><!-- LinkedIn Link --></a></p>
  </section>

  <!-- FOOTER -->
  <footer>
    <p>&copy; <span id="year"></span> <!-- Your Name -->. All rights reserved.</p>
  </footer>

  <script>
    document.getElementById("year").textContent = new Date().getFullYear();
  </script>

</body>
</html>

body {
  font-family: Arial, sans-serif;
  margin: 0;
  background-color: #f4f4f4;
  color: #333;
}

.container {
  width: 90%;
  max-width: 1000px;
  margin: auto;
}

header {
  background: linear-gradient(to right, #6a11cb, #2575fc);
  color: white;
  padding: 40px 0;
  text-align: center;
}

nav {
  background: #222;
  display: flex;
  justify-content: center;
  flex-wrap: wrap;
}

nav a {
  color: white;
  padding: 15px 20px;
  text-decoration: none;
  display: block;
}

nav a:hover {
  background: #2575fc;
}

section {
  background: white;
  margin: 20px 0;
  padding: 20px;
  border-radius: 8px;
}

h2 {
  color: #2575fc;
}

footer {
  background: #222;
  color: white;
  text-align: center;
  padding: 15px;
  margin-top: 20px;
}
