# Wenzhou in Two Days

A two-day travel guide for first-time visitors to Wenzhou. This is my final project for the **Web Technologies 2026** course at Hainan Bielefeld University of Applied Sciences.

## Live Demo

🔗 [https://YOUR-USERNAME.github.io/wenzhou-guide/](https://YOUR-USERNAME.github.io/wenzhou-guide/)

*(Replace `YOUR-USERNAME` with your actual GitHub username before submitting.)*

## Project Overview

Wenzhou is more than factories. It has the peaks of Yandang Mountain, bamboo rafts on the Nanxi River, the twin pagodas of Jiangxin Island, and the street food of Wuma Street. In two days, you can see the mountains, the river, the sea, and the city.

This website is designed for tourists who are visiting Wenzhou for the first time and only have two days.

## Features

- **Four pages**: Home, Must-See Spots, Food Map, and Practical Tips.
- **Responsive Design**: Mobile-first layout using CSS Grid. Works on phones and desktops.
- **Interactive Elements**: 
  - Mobile hamburger menu (JavaScript)
  - Food category filter with fade-in animation (JavaScript)
  - Collapsible spot details using `<details>`/`<summary>` (Native HTML)
  - Scroll reveal animations (Intersection Observer)
  - Dynamic greeting based on time of day
- **Social Sharing**: Open Graph meta tags for link previews.
- **Icons**: Custom favicon and Apple touch icon.

## Tech Stack

- **HTML5**: Semantic structure (`header`, `nav`, `main`, `article`, `footer`).
- **CSS3**: Grid, Flexbox, media queries, custom properties.
- **JavaScript (Vanilla)**: DOM manipulation, Intersection Observer, event handling. No external libraries or frameworks.
- **Git & GitHub Pages**: Version control and deployment.

## File Structure

```text
wenzhou-guide/
├── index.html              # Home page
├── spots.html              # Must-See Spots page
├── food.html               # Food Map page
├── tips.html               # Practical Tips page
├── project.html            # Course project description
├── css/
│   └── style.css           # Global stylesheet
├── js/
│   ├── nav.js              # Injects navigation and footer
│   └── dynamic.js          # Hamburger menu, filtering, animations
├── images/
│   ├── og-image.jpg        # Open Graph image (1200x630)
│   ├── favicon-32.png      # Browser favicon (32x32)
│   ├── apple-touch-icon.png# Apple touch icon (180x180)
│   └── (scenic photos)
└── README.md
