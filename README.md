# 🏋️ IRON PULSE | Premium Fitness Landing Page

A single-page, static landing page for a fictional luxury fitness center. Built with semantic HTML and custom CSS as a portfolio project.

---

## 📖 About the Project

**IRON PULSE** is a fictional, brand-style landing page designed to showcase frontend development skills through a premium fitness-themed layout. The site presents programs, membership plans, trainers, and gym highlights — all within a polished, responsive single-page experience.

> **Note:** This is not a real gym or business. It is a personal portfolio and learning project.

---

## 🎯 Project Purpose

- Demonstrate proficiency in **semantic HTML5** structure and **modern CSS3** layout techniques
- Build a visually rich, portfolio-ready frontend project without frameworks or JavaScript
- Practice responsive design and component-style styling using a consistent design system
- Create an engaging, content-driven landing page suitable for a frontend development internship application

---

## ✨ Key Features

| Feature              | Description                                                                 |
| --------------------- | ---------------------------------------------------------------------------- |
| **Sticky navigation** | Sticky, blurred header with links to eight main sections                    |
| **Hero section**      | Full-height banner with background image, overlay, headline, and dual CTAs  |
| **About section**     | Two-column layout with trainer image, mission, and vision copy              |
| **Programs**          | Six program cards (Strength, Weight Loss, CrossFit, PT, Cardio, Nutrition)  |
| **Why Choose Us**     | Six feature cards highlighting equipment, trainers, plans, and support      |
| **Membership plans**  | Three pricing tiers (Basic, Premium, Elite) with a highlighted middle plan  |
| **Gallery**           | Eight-image responsive grid with hover zoom effect                          |
| **Trainers**          | Four trainer profile cards with roles, bios, and social icons               |
| **Testimonials**      | Three member success stories with photos and star ratings                  |
| **Stats bar**         | Four stat cards (members, trainers, years, awards)                         |
| **BMI calculator**    | Static, design-only BMI form (no JavaScript logic)                         |
| **Contact section**   | Static HTML contact form plus a contact-info card and map placeholder      |
| **Footer**            | Quick links, newsletter UI, and social icons                               |

---

## 🎨 Design Highlights

- **Bold dark theme** — Near-black background (`#0B0B0B`) with a red primary accent (`#E63946`) and a gold/yellow secondary accent (`#FFD166`)
- **Typography pairing** — [Bebas Neue](https://fonts.google.com/specimen/Bebas+Neue) for headings/logo and [Poppins](https://fonts.google.com/specimen/Poppins) for body text via Google Fonts
- **CSS custom properties** — Centralized design tokens for colors, radius, and container width (`:root` variables)
- **CSS Grid & Flexbox** — Responsive layouts for program cards, pricing, gallery, trainers, and footer
- **Hover interactions** — Card lift on program cards, image zoom in the gallery, and animated nav underline
- **Sticky, blurred header** — `backdrop-filter: blur()` on the navbar for a glass effect
- **Font Awesome icons** — Used throughout programs, features, contact info, and socials via CDN
- **Responsive breakpoints** — Layout adjustments at `max-width: 1000px`, `700px`, and `420px`

---

## 🛠️ Technologies Used

| Technology       | Role                                                 |
| ---------------- | ----------------------------------------------------- |
| **HTML5**        | Semantic markup, forms                                |
| **CSS3**         | Layout, custom properties, transitions, media queries |
| **Google Fonts** | Bebas Neue & Poppins web typography                    |
| **Font Awesome** | Icon set (CDN-linked)                                  |

**Not used:** JavaScript, React, Vue, Bootstrap, Tailwind, build tools, or backend services.

---

## 📁 Project Structure

```
Decode_lab_proj_1/
├── index.html          # Single-page site (11 sections)
├── css/
│   └── style.css       # Complete stylesheet
├── images/
│   ├── GymInterior.jpg     # Hero background
│   ├── TrainerCoaching.jpg # About section image
│   ├── Gallery1.jpg .. Gallery8.webp  # Gallery grid (8 images)
│   ├── Trainer1.jpg .. Trainer4.jpg   # Trainer cards (4 images)
│   ├── Member1.webp .. Member3.jpg    # Testimonial photos (3 images)
│   └── Galler1.svg         # Placeholder asset
├── IMAGES.md            # Image sourcing notes and keyword suggestions
├── screenshots/
│   ├── hero.png
│   ├── about.png
│   ├── programs.png
│   ├── membership.png
│   ├── gallery.png
│   ├── trainers.png
│   ├── contact.png
│   └── footer.png
└── README.md
```

---

## 🗂️ Main Website Sections

The page contains **11** `<section>` elements, all reachable from the sticky navbar.

| Section        | ID              | In Nav? | Content                                                        |
| -------------- | --------------- | ------- | ---------------------------------------------------------------- |
| Hero           | `#home`         | Yes     | Headline, sub-copy, "Join Now" and "Explore Programs" CTAs       |
| About          | `#about`        | Yes     | Mission & vision copy alongside a trainer-coaching image         |
| Programs       | `#programs`     | Yes     | 6 program cards (Strength, Weight Loss, CrossFit, PT, Cardio, Nutrition) |
| Why Choose Us  | —               | No      | 6 feature highlights (equipment, trainers, plans, support, etc.) |
| Membership     | `#membership`   | Yes     | 3 pricing tiers — Basic, Premium (highlighted), Elite             |
| Gallery        | `#gallery`      | Yes     | 8-image gym gallery grid                                          |
| Trainers       | `#trainers`     | Yes     | 4 trainer profile cards with bios and socials                     |
| Testimonials   | `#testimonials` | Yes     | 3 member success stories with star ratings                        |
| Stats          | —               | No      | 4 stat highlights (members, trainers, experience, awards)         |
| BMI Calculator | —               | No      | Design-only BMI input form (no calculation logic)                 |
| Contact        | `#contact`      | Yes     | Contact form, contact info, and map placeholder                   |
| Footer         | —               | —       | Logo, quick links, newsletter form, social icons, copyright       |

**Navigation links:** Home, About, Programs, Membership, Trainers, Gallery, Testimonials, Contact

**Footer quick links:** Programs, Membership, Trainers

---

## 🚀 How to Run Locally

No installation or build step is required. Open the project in any modern browser.

**Option 1 — Direct open**

Open `index.html` directly in your browser from the project folder.

**Option 2 — Local server (recommended)**

Using Python:

```bash
cd Decode_lab_proj_1
python -m http.server 8000
```

Then visit: `http://localhost:8000`

Using VS Code / Cursor Live Server extension:

1. Open the project folder
2. Right-click `index.html` → **Open with Live Server**

---

## 📸 Screenshots

| Hero                                    | About                                     |
| ---------------------------------------- | ------------------------------------------ |
| <img width="1880" height="903" alt="image" src="https://github.com/user-attachments/assets/1d4aa36a-a883-4b72-9d85-dcfa64caf32d" /> |<img width="1871" height="900" alt="image" src="https://github.com/user-attachments/assets/ea432c31-8c65-4489-a2de-9cc2e56626eb" />
 |

| Programs                                        | Membership                                        |
| ------------------------------------------------ | -------------------------------------------------- |
| <img width="1873" height="901" alt="image" src="https://github.com/user-attachments/assets/394e93ff-326e-4250-ae92-1e3dc5d42322" />|<img width="1878" height="897" alt="image" src="https://github.com/user-attachments/assets/98b692d5-af03-4686-97e4-ac29dd51ec0b" />|

| Gallery                                       | Trainers                                        |
| ----------------------------------------------- | ------------------------------------------------- |
| <img width="1831" height="865" alt="image" src="https://github.com/user-attachments/assets/910e016e-37e8-4af2-9ebe-297b20e54070" />|<img width="1823" height="862" alt="image" src="https://github.com/user-attachments/assets/ab9c1b95-4aed-4720-b295-785915493c9a" /> |

| Testimonials                                    | BMI Calculator                                       |
| ----------------------------------------------- | ------------------------------------------------- |
|<img width="1862" height="895" alt="image" src="https://github.com/user-attachments/assets/a505a66f-b62a-41d3-9040-192d08adfd8d" />|<img width="1861" height="883" alt="image" src="https://github.com/user-attachments/assets/ec1dec81-88b6-44de-bc31-4b68774f2b86" /> |

| Contact                                        | Footer                                      |
| ------------------------------------------------ | --------------------------------------------- |
| <img width="1867" height="857" alt="image" src="https://github.com/user-attachments/assets/2b7555c4-4069-414a-8af9-eb8b7a381333" /> | <img width="1866" height="898" alt="image" src="https://github.com/user-attachments/assets/2ca59cb0-5b21-4864-b928-2624e8b88345" /> |


---

## 💡 What I Learned

- Structuring a long single-page site with semantic HTML5 (`header`, `nav`, `section`, `article`, `footer`)
- Building a small CSS design system with custom properties for colors, radius, and spacing
- Creating layouts with **CSS Grid** and **Flexbox** (program cards, pricing, gallery, trainers, footer)
- Using a **sticky header with backdrop blur** for a premium feel without JavaScript
- Designing hover-driven UI feedback (card lift, image zoom, nav underline) with pure CSS
- Organizing responsive styles with **max-width media queries** and progressive layout collapse

---

## 🔮 Future Improvements

- [ ] Add real photography and replace placeholder images (see `IMAGES.md`)
- [ ] Add form submission handling for the contact and newsletter forms (e.g., Formspree or a custom backend)
- [ ] Add working BMI calculation logic with JavaScript
- [ ] Add navigation link and section for "Why Choose Us"
- [ ] Implement scroll-spy active state for nav links
- [ ] Add a lightbox for gallery images
- [ ] Replace the map placeholder with an embedded Google Map
- [ ] Optimize images for faster loading (WebP, `loading="lazy"`)
- [ ] Deploy to GitHub Pages / Netlify / Vercel and add a live demo link

---

## ⚠️ Disclaimer

This project is an **unofficial educational and portfolio website**. IRON PULSE is a fictional brand created for demonstration purposes only and is not a real gym or business.

The contact form, newsletter signup, and social media links are **UI placeholders** and do not connect to any live backend or service.

## Image Credits

Images are placeholders sourced for portfolio presentation — see `IMAGES.md` for suggested royalty-free replacements and keywords.

---

## 👤 Author

**Syed Qazi Burhan**  
Software Engineer 

- GitHub: [github.com/Qazi-Burhan](https://github.com/Qazi-Burhan)
- LinkedIn: [www.linkedin.com/in/syed-qazi-burhan-ul-haq-36aa90333]

---

Built with HTML & CSS · © 2026 IRON PULSE
