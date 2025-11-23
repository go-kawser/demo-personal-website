# Personal Portfolio | Md Abu Kayser - Full-Stack Engineer

## Demo Frontend

Professional, responsive personal portfolio template for a Full Stack Developer and UI/UX Designer. Built with Tailwind CSS, DaisyUI and lightweight custom CSS for fast performance and easy customization.

## Table of Contents

- Overview
- Live Demo
- Features
- Tech Stack
- Project Structure
- Getting Started
- Customization Guide
- Deployment
- Contributing
- Contact

## Overview

This repository contains a polished landing/portfolio website showcasing projects, services, client testimonials, and contact information for Md Abu Kayser - a Full Stack Developer and UI/UX Designer. The layout emphasizes performance, accessibility, and a modern aesthetic with theme switching and responsive components.

The project is intended both as a personal portfolio and as a starter template you can fork and customize to present your own work to clients.

## Live Demo github pages

- **GitHub Pages:** https://md-abu-kayser.github.io/demo-personal-website/

## Features

- Clean, responsive hero and multi-section layout (About, Services, Portfolio, Testimonials, Blog, Contact)
- Theme selection (DaisyUI themes) and accessible color contrasts
- Portfolio grid with category filters and animated hover states
- Skills section with animated progress bars
- Reusable components using Tailwind + DaisyUI utility classes
- Optimized for performance: minimal custom CSS and CDN-hosted UI libraries

## Tech Stack

- HTML5
- CSS3 (custom styles + Tailwind CSS via CDN)
- DaisyUI (component library for Tailwind)
- Font Awesome (icons)
- Google Fonts (Poppins)

### Project Structure

**Root files:**

```
index.html            # Single-page portfolio site
README.md             # Project documentation (this file)
css/                  # Custom styles
styles.css            # Project-specific CSS
images/               # Placeholder images and avatar
```

### Key sections in `index.html`:

- Header / Navigation - responsive navbar with theme picker and Hire button
- Hero - prominent headline, call-to-actions and animated typewriter
- About - personal summary, contact metadata, and skills
- Services - cards describing offered services
- Portfolio - projects gallery (image cards)
- Testimonials - client feedback carousel
- Contact - contact call-to-action and links

### Getting Started

**Prerequisites: a modern browser. To run locally:**

1. Clone the repository:

- git clone https://github.com/md-abu-kayser/demo-personal-website.git

### Customization Guide

- Replace the name, email and personal details in the About section of `index.html`.
- Swap out images in the `images/` folder and update image paths.
- Edit `css/styles.css` to tweak colors, animations, and spacing. The project uses CSS variables for easy color theming (see `:root`).
- Tailwind / DaisyUI themes can be changed via the theme picker in the navbar. To permanently set a theme, modify the `data-theme` attribute on the `<html>` element in `index.html`.

### Accessibility notes

- Semantic HTML is used for headings and sections.
- Buttons and links include clear text CTAs.
- Ensure images include concise `alt` text when adding or replacing images.

### Deployment

**Recommended quick deploy options:**

- GitHub Pages - push to `main` and enable Pages from the repository settings (select root). The site will be served at `https://md-abu-kayser.github.io/demo-personal-website/`.
- Netlify / Vercel - drag & drop the project folder or connect your GitHub repo for CI/CD.

### Contributing

This repo is primarily a personal portfolio template. If you'd like to suggest improvements, feel free to open an issue or submit a pull request. Keep changes focused and provide screenshots for visual edits.

**Suggested contribution workflow:**

1. Fork the repository
2. Create a feature branch (`git checkout -b feat/awesome-improvement`)
3. Commit changes and push
4. Open a Pull Request describing your changes

### License

- This project is licensed under the terms of the **[MIT License](./LICENSE)**.
- You may replace or update the license as needed for client or proprietary projects.

---

### Contact and Maintainer

- **_Name:_** Md Abu Kayser - Full-Stack Engineer
- **_Project:_** _demo-personal-website_
- **_Maintainer:_** [md-abu-kayser](https://github.com/md-abu-kayser)
- **_GitHub:_** [github.com/abu.kayser-official](https://github.com/md-abu-kayser)
- **_Email:_** [abu.kayser.official@gmail.com](mailto:abu.kayser.official@gmail.com)

If you’d like this README tailored for a specific purpose - such as **hiring managers**, **open-source contributors**, or **client deliverables** - feel free to request a custom tone or format.

---

**Thank you for reviewing this project!**  
It’s designed to be **clean, well-structured**, and **pleasant to explore** - perfect for interviews, portfolio showcases, or professional demos.

**Made with love - a clean, responsive portfolio template for showcasing modern web skills.**

---
