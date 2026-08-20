# 🌟 Personal Goals & About Me Web Pages

> A clean, two-page personal website showcasing developer background details, structured learning milestones, daily routines, vacation wishlist galleries, and interactive contact forms.

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)

---

## 📄 Site Architecture & Pages

### 1. 👤 About Me Page (`about.html`)
- **Developer Biography:** Profile overview highlighting web development passion and goals.
- **Contact & Network Links:** Fast access to direct email (`mailto:`), phone calling (`tel:`), and search tools.
- **Cross Navigation:** Linked directly to the main goals and planner page.

### 2. 🎯 Goals & Vacation Planner (`index.html`)
- **Daily Study Schedule:** Structured timetable tracking coding hours, breaks, and study routines using HTML `<time>` tags and tables.
- **Learning Roadmap:** Step-by-step milestones utilizing semantic `<ol>`, `<abbr>`, and interactive `<details>` tags.
- **Vacation Gallery & Wishlist:** Visual showcase of travel destinations (swimming pools, Riviera Cancún) along with places to avoid using description lists (`<dl>`).
- **Interactive Contact Form:** Input validation for user information (Name, Password, Telephone regex pattern check) submitting to `httpbin.org`.

---

## ✨ Features & HTML Best Practices

- **Semantic HTML5:** Built with `<header>`, `<nav>`, `<main>`, `<article>`, `<section>`, `<aside>`, `<figure>`, and `<footer>`.
- **Accessible & Responsive:** Mobile-viewport configured, lazy-loaded imagery (`loading="lazy"`), and proper `alt` descriptions.
- **Interactive Elements:** Collapsible collapsible blocks using `<details>` and `<summary>`.

---

## 📂 Repository Structure

```text
.
├── index.html       # Primary page: Goals, schedule, vacation gallery & contact form
├── about.html       # Biography, background overview, and direct contact details
├── main.css         # Stylesheet for both pages
└── img/             # Profile pictures, icons, and vacation imagery
