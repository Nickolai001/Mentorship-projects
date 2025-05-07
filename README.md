
# Loopstudios Landing Page (Responsive VR Showcase)

This project is a **responsive frontend recreation** of the Loopstudios VR landing page. Built with **HTML** and **Tailwind CSS**, it includes interactive elements like a **dropdown menu**, **hover-animated cards**, and clean typography using Google Fonts. This project is a static representation, ideal for showcasing frontend UI/UX skills.

---

## Live Preview

*Coming soon: Add link if deployed via GitHub Pages, Netlify, or Vercel.*

---

## Features

- Fully responsive layout using Tailwind CSS utility classes
- Dropdown navigation menu (mobile-friendly)
- Stylish cards in the "Our Creations" section with hover animation
- Custom fonts (`Josefin Sans`, 'Alata') for modern, minimalistic feel
- Grid-based gallery design with fixed dimensions
- Clean, maintainable structure using a separate `input.css` (optional enhancements)

---

## Technologies Used

- HTML5
- Tailwind CSS 4.1
- Google Fonts (`Josefin Sans`)
- Vanilla JavaScript (for dropdown toggle)

---

## Folder Structure

```
project-root/
├── index.html
├── styles.css        # (Optional enhancements beyond Tailwind)
├── assets/
│   └── images/       # All project image assets
├── tailwind.config.js
└── README.md
```

---

## Setup Instructions

1. **Clone the repo**
   ```bash
   git clone https://github.com/your-username/loopstudios-vr-site.git
   cd loopstudios-vr-site
   ```

2. **Install Tailwind CSS (if not using CDN)**
   ```bash
   npm install -D tailwindcss
   npx tailwindcss init
   ```

3. **Configure Tailwind**
   Add your paths to `tailwind.config.js`:
   ```js
   content: ["./index.html"],
   ```

4. **Import Tailwind in CSS**
   ```css
   @tailwind base;
   @tailwind components;
   @tailwind utilities;
   ```

5. **Build Tailwind**
   ```bash
   npx tailwindcss -i ./styles.css -o ./dist/output.css --watch
   ```

6. **Open `index.html` in browser**
   ```bash
   live-server .   # or open manually
   ```

---

## Component Breakdown

### 1. **Navigation Bar**
- Static links
- Mobile dropdown toggle on small screens
- Sticky on top (optional)

### 2. **Hero Section**
- Full-screen background image
- Bold, centered text in transparent frame

### 3. **Intro Section**
- Split layout: image and description text
- Uses Tailwind's grid/flex utilities

### 4. **Our Creations (Card Grid)**
- Responsive grid layout (2 to 4 columns)
- Each card uses:
  - `relative` + `absolute` text
  - `hover:scale-105` transition
  - Font: `Josefin Sans`, 'Alata'
 

### 5. **Footer**
- Simple grid layout
- Social media icons (optional placeholders)
- Site copyright

---

## Personal Reflection

### **Strengths Demonstrated**
- **Attention to UI detail:** You carefully studied layout spacing, fonts, and hover effects to match the reference design.
- **Tailwind Proficiency:** Confident usage of Tailwind utilities to manage responsiveness, typography, and spacing.
- **Growth Mindset:** You asked for clean code refactoring, modular CSS, and followed up with performance + structure optimizations.

### **Struggles Encountered**
- **Dropdown Menu Logic:** Implementing a responsive toggle took some clarification and JavaScript practice.
- **Font Integration:** Understanding how to incorporate Google Fonts in Tailwind required learning `tailwind.config.js` configuration.
- **Responsiveness Tuning:** Balancing pixel-perfect card sizes across screen breakpoints involved testing and tweaking.

---

## To-Do / Improvements

- [ ] Add animations for dropdown menu (e.g., fade-in/out)
- [ ] Use Alpine.js or small framework for better interactivity
- [ ] Deploy to GitHub Pages or Netlify
- [ ] Add accessibility tags (ARIA roles, keyboard nav)
- [ ] Add dark mode toggle using Tailwind theming

---

## Author

**Chinaemere Nicholas Okpara**  
Frontend Developer | Tech Enthusiast  
Computer Science & Engineering, Obafemi Awolowo University  
Lagos, Nigeria

---

## License

This project is open-source and available for learning purposes.
