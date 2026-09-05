# 🎨 Origami Hub

<div align="center">

**A creative front-end web platform dedicated to the art of paper folding.**

Step-by-step tutorials • Interactive guides • Skill-based learning • Beautiful gallery

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![Bootstrap](https://img.shields.io/badge/Bootstrap-7952B3?style=for-the-badge&logo=bootstrap&logoColor=white)](https://getbootstrap.com/)

</div>

---

## 📖 About The Project

**Origami Hub** is a multi-page, responsive website that makes the art of origami accessible and enjoyable for everyone — from curious kids to patient elders. It offers a rich library of paper-folding tutorials organized by **category** and **skill level**, complete with an interactive step-by-step viewer, filterable gallery, and community-facing pages (FAQ, feedback, contact).

This project was built as a front-end showcase demonstrating responsive design, interactive JavaScript components, and clean multi-page site architecture — no frameworks, no backend, just HTML, CSS, and vanilla JS.

---

## ✨ Features

- 🖼️ **10 Origami Categories** — Animals, Birds, Flowers, Faces, Dollar Bills, Holidays, Letters, Jewellery, Paper Toys, and Nature
- 🎚️ **Skill Levels** — Dedicated "Easy" (kids) and "Complex" (elders) pages with curated project sliders
- 🪜 **Interactive Step-by-Step Tutorials** — Click through fold stages with a live-updating image and description panel
- 🖼️ **Filterable Gallery** — Browse creations by category with instant JS filtering
- 📱 **Fully Responsive Navbar** — Mobile hamburger menu with animated dropdowns
- 💬 **Community Pages** — Contact form, Feedback, FAQ (Bootstrap accordion), and an Article page on origami's history
- ⚖️ **Legal Pages** — Privacy Policy & Terms and Conditions
- 🎞️ **Animated Homepage** — Bootstrap carousel hero + GSAP-powered horizontal scroll on the About page

---

## 🗂️ Project Structure

```
Origami-Hub/
│
├── index.html                 # Homepage — hero carousel + category grid
├── About.html                 # Story, mission & offerings (GSAP scroll animation)
├── Contact.html                # Contact form
├── Gallery.html                # Filterable image gallery
├── feedback.html               # Feedback page
├── F.A.Q.html                  # Frequently Asked Questions (accordion)
├── article.html                # History of origami — blog-style article
├── privacy policy.html         # Privacy Policy
├── terms and condition.html    # Terms & Conditions
│
├── Easy.html                   # Skill level: Beginner / Kids
├── hard.html                   # Skill level: Advanced / Elders
│
├── Animals.html / Animals steps.html
├── Birds.html / birds step.html
├── Flower.html / Flower steps.html
├── Face.html / face step.html
├── dollar.html / dollar step.html
├── Holiday.html / holiday steps.html
├── Letter.html / letter step.html
├── Jewellery.html / jewellery steps.html
├── paper toy.html / paper toy steps.html
├── Nature.html / nature step.html
│
├── main origami.css            # Shared stylesheet
├── main origami.js             # Shared navbar/dropdown logic
└── assect/                     # Images, icons & media assets
```

---

## 🛠️ Built With

| Technology | Purpose |
|---|---|
| **HTML5** | Semantic page structure |
| **CSS3** | Custom styling, layouts & responsiveness |
| **JavaScript (Vanilla)** | Interactive tutorials, gallery filters, mobile nav |
| **Bootstrap 5** | Grid system, carousel, accordion, icons |
| **Font Awesome** | Iconography |
| **GSAP + ScrollTrigger** | Horizontal scroll animations on the About page |

---

## 🚀 Getting Started

Since this is a static front-end project, no build tools or dependencies are required.

### Run Locally

```bash
# Clone the repository
git clone https://github.com/hibashakil12/Origami-Hub.git

# Navigate into the project folder
cd Origami-Hub

# Open index.html directly in your browser
# or serve it with a local server, e.g.:
npx serve .
```

> 💡 **Tip:** Using a local server (like `Live Server` in VS Code) is recommended so relative asset paths load correctly.

---

## 📸 Categories at a Glance

| 🐼 Animals | 🕊️ Birds | 🌸 Flowers | 😄 Faces | 💵 Dollar Bills |
|:---:|:---:|:---:|:---:|:---:|
| 🎄 Holidays | ✉️ Letters | 💎 Jewellery | ✈️ Paper Toys | 🍁 Nature |

---

## 🧭 Roadmap

- [ ] Standardize file naming (remove spaces from filenames for URL safety)
- [ ] Convert repeated header/footer markup into reusable components
- [ ] Add a working backend for the contact form
- [ ] Add dark mode toggle
- [ ] Improve accessibility (alt text, ARIA labels)

---

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

---

## 📄 License

**© 2026 Origami Hub. All Rights Reserved.**

This project, including its design, code, and content, is the sole intellectual property of **Hiba Shakil**. It is **not open source**.

No part of this project may be copied, reproduced, modified, distributed, or used — in whole or in part, for personal, educational, or commercial purposes — without **prior written permission** from the owner.

Any unauthorized use, reproduction, or distribution of this project found elsewhere without explicit written consent will be considered a violation of intellectual property rights, and **legal action will be taken** against the responsible party.

For permission requests or inquiries, please contact the owner [@hibashakil12](https://github.com/hibashakil12) directly.

---

## 📬 Contact

**Hiba Shakil**
GitHub: [@hibashakil12](https://github.com/hibashakil12)

<div align="center">

Made with 💜 and a lot of folded paper.

</div>
