# Personal Portfolio Website

A clean, responsive, and minimalist single-page portfolio website designed to showcase my current works and future projects. Hosted completely for free using GitHub Pages.

🌐 **Live Link:** [https://kzzar.github.io/personalsite/

## 🚀 Features
*   **Fully Responsive:** Optimized for desktop, tablet, and mobile screens.
*   **Performance Focused:** Built using vanilla HTML5 and CSS3 with zero external dependencies, frameworks, or tracking scripts for near-instant loading times.
*   **Modern Aesthetic:** Clean layouts featuring light/dark adaptive minimalist typography.
*   **Project Showcase:** Structural grid layout built to accommodate current case studies and hold placeholders for upcoming releases.

## 🛠️ Built With
*   HTML5
*   CSS3 (Custom CSS Properties / CSS Grid & Flexbox)

## 📁 File Structure
```text
personalsite/
├── index.html     # The main webpage script, structure, and styling
└── README.md      # Project documentation (this file)
```

## ⚙️ How to Update and Customize

### 1. Locally Editing Content
Open `index.html` in any text editor (like VS Code or Notepad) to swap out the text placeholders:
*   Update your name in the `<title>`, `<header>`, and `<footer>` tags.
*   Modify your bio in the `#hero` and `#about` sections.
*   Paste your links inside the `#contact` section buttons.

### 2. Adding Images
To add project images or thumbnails:
1. Create an `images` folder inside your repository.
2. Drop your image files (e.g., `project1.jpg`) into that folder.
3. Replace the text placeholders `<div class="card-img">...</div>` inside `index.html` with an actual image element:
   ```html
   <img src="images/project1.jpg" alt="Description of Project One" class="card-img">
   ```

### 3. Deploying Changes
Every time you `git commit` and `git push` modifications to the `main` branch, GitHub Pages will automatically run a build pipeline and update your live site within 1–2 minutes.
