# hello-technest-website

A lightweight personal portfolio built with **HTML and CSS** — no frameworks, just clean and accessible web fundamentals.

---

## ✨ Overview

This project is a simple, responsive portfolio page designed to showcase personal information, links, and projects.

### Includes:
- Semantic HTML structure  
- Responsive layout  
- Dark mode support (`prefers-color-scheme`)  
- Accessible focus states  

---

## 📁 Project Structure
├── index.html # Main page structure and content
└── styles.css # Styling, layout, and responsiveness


---

## 🛠️ Customization

Update the following in `index.html`:

- **Name**  
  Replace `Magret` with your preferred display name

- **Links**
  - GitHub  
  - LinkedIn  
  - Email address  

- **Content**
  - Hero tagline  
  - Intro section  

---

## Diagram (Mermaid)
mermaid
flowchart TD
  browser[Browser] --> index[index.html]
  index --> css[styles.css]

  subgraph deployFlow [Deploy_to_Vercel]
    local[Local_folder] -->|npx vercel login| auth[Vercel_auth]
    auth -->|npx vercel --prod| vercel[Vercel_deployment]
    vercel --> url[Live_URL]
  end


## Live Site
```
https://hello-technest-website.vercel.app
```

## Notes
- Built as part of my learning journey at TechNest
- Created using Cursor as part of my development workflow
- Focused on mastering fundamentals before adding frameworks