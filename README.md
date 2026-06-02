# Grand Surya Hotel Official Website

> Front-End Web Developer Internship · Grand Surya Hotel, Kediri

Official hotel website designed and developed from scratch as part of an internship at Grand Surya Hotel, Kediri. Built with a focus on responsive design, cross-browser compatibility, and a user-friendly interface that reflects the hotel's brand identity.

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![SCSS](https://img.shields.io/badge/SCSS-CC6699?style=flat&logo=sass&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![PHP](https://img.shields.io/badge/PHP-777BB4?style=flat&logo=php&logoColor=white)

---

## Overview

This project is the official website for **Grand Surya Hotel**, a hotel property in Kediri, East Java. The website was built entirely from scratch following direct collaboration with hotel stakeholders to translate their business requirements into a functional and visually appealing web presence.

---

## Pages

| Page | File | Description |
|---|---|---|
| Home | `index.html` | Landing page with hero section and hotel highlights |
| Rooms | `rooms.html` | Room types and accommodation details |
| Restaurant | `restaurant.html` | Dining options and menu showcase |
| Activities | `activities.html` | Hotel activities and entertainment |
| Services | `services.html` | Hotel facilities and services |
| Offers | `offers.html` | Promotions and special packages |
| Contact | `contact.html` | Contact form and hotel location |

---

## Features

- Responsive layout optimized for desktop, tablet, and mobile
- Cross-browser compatible interface
- SCSS-based styling with modular structure compiled to CSS
- Contact form with PHP backend processing (`contact_process.php`)
- Consistent visual identity aligned with hotel branding

---

## Repository Structure

```
grand-surya-hotel/
│
├── index.html              ← Home page
├── main.html               ← Main layout
├── rooms.html              ← Rooms & accommodation
├── restaurant.html         ← Restaurant & dining
├── activities.html         ← Activities & recreation
├── services.html           ← Hotel services & facilities
├── offers.html             ← Promotions & packages
├── contact.html            ← Contact page
├── contact_process.php     ← Contact form handler (PHP)
├── elements.html           ← UI component library
│
├── assets/
│   ├── scss/
│   │   └── main.scss       ← Main SCSS source file
│   ├── css/
│   │   └── style.css       ← Compiled CSS output
│   └── js/                 ← JavaScript files
│
├── package.json            ← SCSS compiler config (node-sass)
└── README.md
```

---

## Tech Stack

| Technology | Usage |
|---|---|
| HTML5 | Page structure and semantic markup |
| CSS3 | Styling and layout |
| SCSS | Modular stylesheet preprocessing |
| JavaScript | UI interactivity and dynamic behavior |
| PHP | Contact form backend processing |
| node-sass | SCSS to CSS compilation |

---

## Getting Started

### View the website
Open `index.html` directly in any modern browser no server required for most pages.

### SCSS Compilation (for development)
```bash
# Install dependencies
npm install

# Compile SCSS and watch for changes
npm run compile:sass
```

This compiles `assets/scss/main.scss` → `assets/css/style.css` and watches for changes automatically.

### Contact Form
The contact form (`contact.html`) requires a PHP-capable server to function:
```bash
# Using PHP built-in server
php -S localhost:8000
```

---

## Context

This website was developed during a **Front-End Web Development Internship** at Grand Surya Hotel, Kediri (June – August 2025). The development process involved:

- Gathering requirements through direct collaboration with hotel operations and management staff
- Designing and building the complete website from scratch
- Ensuring responsive and cross-browser-compatible output
- Delivering a final product aligned with the hotel's visual identity and business needs

---

## Author

**Agnes Priscilla Sekartaji Hadikusuma**  
S1 Teknik Informatika · Institut Teknologi Sepuluh Nopember (ITS) Surabaya

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat&logo=linkedin&logoColor=white)](https://linkedin.com/in/agnespriscilla33)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white)](https://github.com/agnespriscilla)
[![Email](https://img.shields.io/badge/Email-D14836?style=flat&logo=gmail&logoColor=white)](mailto:agnes.priscilla33@gmail.com)
