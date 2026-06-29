# SHISH MOHAMMAD // Cybersecurity Portfolio

This is a premium, high-performance, dark-themed cybersecurity portfolio designed to showcase digital defense capabilities, threat mitigating skills, professional experience, and terminal-grade projects.

It has been connected into a unified, responsive multi-page web application that is fully static and ready to be deployed directly to **GitHub Pages** with zero build configuration!

---

## 📂 Folder Structure

All the files in this folder are connected and self-contained:
*   `index.html` - The landing page of your portfolio, displaying key metrics, highlighted case studies, and tool previews.
*   `projects.html` - Your dedicated projects registry containing detailed system reports and repository links for 6 tactical operations.
*   `skills.html` - Your skills inventory, technical stack matrix, certifications tracker, and interactive terminal career log.
*   `contact.html` - An encrypted-style terminal contact form with social nodes and interactive geographical grid details.
*   `README.md` - Deployment and customization guidelines (this file).

---

## 🚀 Easy Deployment to GitHub Pages

Deploying your portfolio to GitHub Pages is completely free and takes less than a minute:

1.  **Create a GitHub Repository**:
    *   Log in to GitHub and create a new repository (e.g., name it `portfolio` or `yourusername.github.io`).
2.  **Upload These Files**:
    *   Upload all the files inside this `Ready to upload` folder directly to the root of your new repository.
3.  **Enable GitHub Pages**:
    *   Go to your repository **Settings** tab.
    *   Scroll down to the **Pages** menu on the left sidebar.
    *   Under **Build and deployment** > **Branch**, select `main` (or `master`) and `/ (root)`.
    *   Click **Save**.
4.  **Live Site**:
    *   GitHub will generate your live URL (usually `https://yourusername.github.io/portfolio/`). It will be active in 1-2 minutes!

---

## 🛠️ Customization Guide

You can easily adjust the portfolio to reflect your own branding and credentials by modifying the `.html` files:

### 1. Update Profile Photo
In `index.html`, search for `Shish Mohammad Profile` and replace the `src` attribute of the `<img>` tag with your own image URL, or upload your own image (e.g., `avatar.jpg`) to the repository and reference it relative:
```html
<img src="avatar.jpg" alt="Your Name Profile" class="...">
```

### 2. Connect Your Social Links
Search for the following placeholder URLs inside `index.html`, `projects.html`, `skills.html`, and `contact.html` and replace them with your actual profile links:
*   `https://github.com` (replace with your GitHub profile)
*   `https://linkedin.com` (replace with your LinkedIn profile)
*   `https://twitter.com` (replace with your Twitter/X handle)
*   `mailto:root@shish.io` (replace with your email address)

### 3. Add Your CV
Place your resume PDF named `cv.pdf` in the root of the folder and update the `DOWNLOAD_CV.PDF` button link:
```html
<a href="cv.pdf" download class="...">DOWNLOAD_CV.PDF</a>
```

### 4. Personalize Content
All text content, metric values, timelines, and projects can be modified inside the respective HTML files. The design uses standard HTML5 and Tailwind CSS classes, making customization extremely direct.
