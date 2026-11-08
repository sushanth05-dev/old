# Sushanth M. — Personal Developer Portfolio

> **Role:** Aspiring AI Engineer | B.Tech CSE (AI/ML) Student  
> **Status:** First-Semester Engineering Student

This repository contains the complete personal portfolio website for **Sushanth M.**, designed with an honest, ambitious, and academic developer aesthetic.

---

## 🚀 Quick Start / How to Run

### Option 1: Instant Browser Preview (Zero Installation)
Simply double-click or open **`index.html`** in any modern web browser (Edge, Chrome, Safari, Firefox).  
- No Node.js required
- No `npm install` needed
- Complete styling via Tailwind CSS & Inter typography
- All interactive features (filtering, navigation, mobile drawer) work out of the box

### Option 2: React + TypeScript + Tailwind Build (Vite)
If you have [Node.js](https://nodejs.org/) installed:

```bash
# 1. Install dependencies
npm install

# 2. Swap entry file if needed (or run Vite directly)
cp index.vite.html index.html

# 3. Start development server
npm run dev

# 4. Create production build
npm run build
```

---

## 📂 Project Architecture

```
portfolio/
├── index.html                 # Complete standalone, zero-setup production portfolio
├── index.vite.html            # Vite React entrypoint
├── package.json               # React 18, TypeScript, Lucide, Tailwind dependencies
├── vite.config.ts             # Vite build configuration
├── tsconfig.json              # TypeScript compiler configuration
├── tailwind.config.js         # Tailwind color palette & font configuration
├── postcss.config.js          # PostCSS configuration
│
└── src/
    ├── main.tsx               # React DOM root entry
    ├── App.tsx                # Main layout orchestrator
    ├── index.css              # Global Tailwind base styles
    │
    ├── components/
    │   ├── Navbar.tsx         # Sticky navigation with mobile hamburger drawer
    │   ├── Hero.tsx           # Headline, status pill & verified social links
    │   ├── About.tsx          # Bio & "Currently Learning" progression
    │   ├── Skills.tsx         # Categorized skill badges (non-percentage labels)
    │   ├── Projects.tsx       # Filterable showcase of all 8 projects
    │   ├── Hackathons.tsx     # "Learning Through Building" 4 pillars
    │   ├── LearningJourney.tsx# "My Learning Journey" visual roadmap
    │   ├── Contact.tsx        # Direct GitHub & LinkedIn profiles
    │   └── Footer.tsx         # Copyright & credo
    │
    └── data/
        ├── constants.ts       # Navigation items, roadmap steps, social links
        ├── projects.ts        # Typed project data & category tags
        └── skills.ts          # Categorized skills & learning levels
```

---

## 🛠️ Tech Stack & Philosophy
- **Core Stack:** React, TypeScript, Tailwind CSS, Lucide Icons, Vite
- **Honest & Credible:** Accurately represents a first-semester B.Tech CSE student without exaggerated titles or fabricated achievements.
- **Accessible & Responsive:** Mobile-first layout with semantic HTML5 elements and keyboard navigation.

---

## 🌐 Verified Links
- **GitHub:** [https://github.com/sushanth05-dev](https://github.com/sushanth05-dev)
- **LinkedIn:** [https://www.linkedin.com/in/sushanth-m-a3870a432/](https://www.linkedin.com/in/sushanth-m-a3870a432/)
