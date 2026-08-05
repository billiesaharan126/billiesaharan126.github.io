# Po# Portfolio Site Instructions

## Purpose

This repository contains Jeremy Jackson's personal portfolio website.

The purpose of this website is to showcase:
- Writing ability
- Software development projects

The site should remain professional, minimalist, and easy for employers to navigate.

---

# Important Rules

## Do Not Rebuild the Website

The current structure is intentional.

Do not replace the entire site unless specifically requested.

Prefer:
- Editing existing files
- Adding new entries
- Making small improvements

---

# Main Pages

index.html
- Homepage
- About section
- Profile image

writing.html
- Displays writing projects

software.html
- Displays software projects

---

# Content Files

## Personal Information

File:

js/site-info.js

This controls:
- Name
- About section text
- Profile image path

Update this file when changing homepage information.

---

## Portfolio Information

File:

js/portfolio.js

This controls:
- Writing projects
- Software projects

Add new portfolio entries here instead of manually creating HTML cards.

---

# Adding Writing Projects

Place files inside:

writing/

Current organization:

writing/
- essays/
- articles/
- etc/

Each writing entry should include:

- Title
- Description
- PDF link

Example:

{
    title: "Example Title",
    description: "Short description of the work.",
    category: "Essays",
    link: "writing/essays/example.pdf"
}

---

# Adding Software Projects

Place files inside:

software/

Current organization:

software/
- games/
- apps/
- tools/

Each software entry should include:

- Project title
- Description
- Image preview
- Live demo link
- GitHub link

Example:

{
    title: "Project Name",
    description: "Short description of project.",
    image: "images/project.png",
    demo: "project-link",
    github: "github-link"
}

---

# Design Guidelines

Maintain:

- Beige color palette
- Minimalist aesthetic
- Professional appearance
- Desktop and mobile compatibility

Avoid:

- Excessive animations
- Bright colors
- Clutter
- Generic filler text

---

# Before Making Changes

Explain:

1. Which file will be changed
2. Why the change is needed
3. Whether other pages could be affected

Keep changes simple and understandable.

---

# Git Updates

After making changes:

git add .

git commit -m "Describe changes"

git push

---

# Notes

The website is designed so Jeremy can add content without needing to rebuild the site.

Prioritize maintainability and simple editing over unnecessary complexity.