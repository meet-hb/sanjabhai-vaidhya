# 📸 Sanjay Vaidya — Official Portfolio Website

> A premium, fully responsive personal portfolio website for **Sanjay Vaidya** — celebrated Gujarati photographer, visual storyteller, and educator — featuring his four-decade journey capturing iconic personalities, landscapes, and the soul of Gujarati literary culture.
---

## 🌐 Live Pages
| Page | File | Description |
|------|------|-------------|
| **Home** | `index.html` | Main landing page with hero slider, about section, gallery highlights, testimonials (3D flipbook), and more |
| **About Me** | `about-me.html` | Photographer's biography, skills, and personal timeline |
| **Interview** | `Interview.html` | Full-length editorial interview with multi-language (EN / HI / GU) translation support |
| **Minimalistic Gallery** | `Minimalistic.html` | Advanced filterable photo gallery with 3D flipbook and sidebar controls |
| **Notes** | `Notes.html` | "My Self Notes" — personal sticky-note style journal section |
| **Travel** | `Travel.html` | Travel photography gallery |
| **Glamour** | `Glamour.html` | Glamour & portrait photography gallery |
| **Celebrity** | `Celebrity.html` | Celebrity photography gallery |
| **Teacher** | `Teacher.html` | Teacher portrait series |
| **Music** | `Music.html` | Indian classical music personalities photography |
| **Blog** | `blog.html` | Photography blog and articles |
| **Contact** | `contact.html` | Contact form and location details |

---
## 🗂️ Project Structure

```
sanjabhai-vaidhya/
│
├── index.html                  # Home page
├── about-me.html               # About the photographer
├── Interview.html              # Editorial interview (EN/HI/GU)
├── Minimalistic.html           # Filterable photo gallery
├── Notes.html                  # Personal notes / journal
├── Travel.html                 # Travel photography
├── Glamour.html                # Glamour photography
├── Celebrity.html              # Celebrity photography
├── Teacher.html                # Teacher portrait series
├── Music.html                  # Music personalities
├── blog.html                   # Blog page
├── contact.html                # Contact page
├── style.css                   # Main global stylesheet (~190 KB)
│
├── css/                        # Vendor / library CSS
│   ├── bootstrap.min.css
│   ├── responsive.css          # Comprehensive multi-breakpoint responsive rules
│   ├── animate.css
│   ├── font-awesome.min.css
│   ├── owl.carousel.css
│   ├── lightbox.min.css
│   ├── magnific-popup.css
│   ├── meanmenu.min.css
│   ├── jquery-ui.min.css
│   ├── TimeCircles.css
│   └── simplyCountdown.theme.default.css
│
├── js/                         # JavaScript files
│   ├── main.js                 # Core custom scripts
│   ├── interview-translations.js  # Full EN/HI/GU interview translations
│   ├── bootstrap.min.js
│   ├── owl.carousel.min.js
│   ├── jquery.mixitup.min.js   # Gallery filter
│   ├── isotope.pkgd.min.js     # Masonry / isotope grid
│   ├── lightbox.min.js
│   ├── jquery.magnific-popup.min.js
│   ├── jquery.meanmenu.js      # Mobile hamburger menu
│   ├── contact-form.js
│   ├── wow.min.js              # Scroll animations
│   ├── waypoints.min.js
│   ├── TimeCircles.js
│   ├── simplyCountdown.min.js
│   ├── waves.js
│   └── vendor/
│
├── images/                     # All image assets
│   ├── slider/                 # Hero slider images
│   ├── photo/                  # Portrait & book cover images
│   ├── portfolio/              # Portfolio/gallery images
│   ├── about-me/               # Photographer's profile images
│   ├── gellary/                # Gallery images
│   ├── blog/                   # Blog post images
│   ├── testimonial/            # Testimonial section images
│   ├── winners/                # Photo contest winners
│   ├── Notes/                  # Notes section images
│   └── ...
│
├── fonts/                      # Custom web fonts
│
└── inc/                        # Includes / components
    └── custom-slider/          # Nivo Slider plugin
        └── css/nivo-slider.css
```

---

## ✨ Key Features

### 🖼️ Photo Gallery (Minimalistic.html)
- **Dynamic category filter** — All / Travel / Glamour / Celebrity / Music / Teacher
- **2-column responsive grid** on mobile, multi-column on desktop
- **Sidebar controls** with search, sorting, and view toggle
- **Load More** pagination for performance

### 📖 3D Flipbook (index.html / Testimonial Section)
- Interactive CSS 3D page-flip animation
- Contains 7 pages of written testimonials from Padma Shri awardees and literary icons (Panna Naik, Tarak Mehta, Dr. Gunvant Shah, Dr. Suresh Dalal, Ashwini Bhatt, Tushar Shukla)
- Fully responsive with CSS `scale()` transforms on mobile

### 🎤 Editorial Interview (Interview.html)
- Premium editorial layout with sidebar author card
- Multi-language toggle: **English**, **Hindi (हिंदी)**, **Gujarati (ગુજરાતી)**
- Pull-quotes, themed sections, drop-cap intro paragraphs
- Scroll-triggered animations

### 📝 My Self Notes (Notes.html)
- Polaroid/sticky-note card UI
- Glassmorphism effects with scotch-tape aesthetic
- Written in the voice of the photographer

### 📱 Fully Responsive Design
- **4 breakpoints**: Desktop (1200px+), Tablet (992px–1199px), Mobile (576px–991px), Small Mobile (≤575px)
- Mobile hamburger menu via **MeanMenu** plugin
- Sticky header navigation across all pages

---

## 🛠️ Tech Stack

| Layer | Technology |
|-------|-----------|
| **Structure** | HTML5 (Semantic markup) |
| **Styling** | Vanilla CSS3, Bootstrap 4/5 grid |
| **Animations** | Animate.css, WOW.js, CSS keyframes |
| **Gallery Filter** | jQuery MixItUp, Isotope |
| **Slider** | Nivo Slider (custom), Owl Carousel |
| **Lightbox** | Lightbox.js, Magnific Popup |
| **Menu** | jQuery MeanMenu (mobile), custom desktop nav |
| **Flipbook** | Pure CSS 3D `perspective` + `rotateY` transforms |
| **Icons** | Font Awesome 4.x |
| **Fonts** | Google Fonts — Poppins, Caveat, Outfit, Lora |
| **Countdown** | TimeCircles.js, Simply Countdown |
| **Scroll FX** | Waypoints.js, jQuery Appear |

---

## 🚀 Getting Started

### Static Version (Frontend Only)
No build tools required. Simply open any `.html` file in a browser:
```bash
# Clone or download the project
cd sanjabhai-vaidhya

# Open in browser (Windows)
start index.html

# Or use VS Code Live Server for best results
```

### Laravel Admin Panel (Backend)
A separate Laravel-based admin panel (`sanjay-vaidya-admin`) manages dynamic content like testimonials and gallery data.

```bash
# Navigate to admin panel
cd d:\xampp\htdocs\sanjay-vaidya-admin

# Start Laravel development server
php artisan serve

# Admin panel runs on: http://127.0.0.1:8000
```

> **Prerequisites for Laravel backend:** PHP 8.x, Composer, MySQL (XAMPP recommended on Windows)

---

## 📐 Responsive Breakpoints

| Breakpoint | Width | Behavior |
|------------|-------|----------|
| Large Desktop | ≥ 1200px | Full layout, sticky header, multi-column gallery |
| Desktop | 992px – 1199px | Slightly reduced padding, same layout |
| Tablet | 768px – 991px | Stacked sidebar, 2-column gallery, hamburger menu |
| Mobile | 576px – 767px | Single/2-column layout, horizontal filter pills |
| Small Mobile | ≤ 575px | Single-column, compact spacing, hidden desktop nav |
| iPhone Retina | ≤ 320px | Ultra-compact layout overrides |

---

## 👤 About the Photographer

**Sanjay Vaidya** is a Glamour, Portrait, and Landscape photographer based in **Ahmedabad, India**, active since **1985**. He is best known for:

- Photo-books featuring iconic Gujarati literary figures (Suresh Dalal, Tarak Mehta, Gunvant Shah, Chandrakant Bakshi)
- Portrait sessions with Indian classical music maestros (Pandit Bhimsen Joshi, Ustad Zakir Hussain, Pandit Shivkumar Sharma)
- Photography of spiritual leaders, Bollywood celebrities, and social icons
- Teaching photography at colleges and conducting outdoor workshops across India
- His celebrated **"E-Series"** and **3D Photo Archive** projects

---

## 📁 Navigation Structure

```
Home
├── Behind The Shutter  →  about-me.html
├── Through The Lens (dropdown)
│   ├── Travel.html
│   ├── Glamour.html
│   ├── Teacher.html
│   ├── Celebrity.html
│   ├── Music.html
│   └── Gujarati Literature (coming soon)
├── Lens On Paper (dropdown)
│   └── (same categories as above — book format)
├── Interviews  →  Interview.html
└── Contact Us  →  contact.html

Special Pages (via header buttons):
├── My Self Notes  →  Notes.html
└── ...Minimalistic!  →  Minimalistic.html
```

---

## 🔧 Development Notes

- Page-specific CSS overrides are written **inline within each `.html` file's `<style>` block** rather than in a centralized stylesheet.
- The `Minimalistic.html` gallery uses a `GALLERY_DATA` JavaScript array to dynamically render cards — CSS changes must target the `.gallery-card` class structure.
- `responsive.css` contains legacy rules across 6+ breakpoints; `--float` (CSS custom property prefix) is used intentionally in some rules to disable `float: inherit !important` on mobile without fully removing the declaration.
- The `interview-translations.js` file (~220 KB) contains the complete translated text for all 14 interview questions in three languages.

---

## 📄 License

This project is a **personal portfolio** for Sanjay Vaidya. All photographs, written content, and design elements are the intellectual property of the respective owners. Not for redistribution.

---

*Built with ❤️ — A visual tribute to 40 years behind the lens.*
