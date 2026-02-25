[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/8NpkA7e4)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=22857261&assignment_repo_type=AssignmentRepo)

# Assignment 1: Responsive Portfolio Website

**Course:** CSC4035 Web Programming and Technologies  
**Weight:** 5% of final grade  
**Due:** Week 6, Friday 11:59 PM  

---

## Overview

This project is a fully responsive professional portfolio website developed as part of CSC4035 Web Programming and Technologies. The portfolio showcases my technical skills, selected projects, and contact information while demonstrating strong application of modern HTML5 and CSS3 principles.

The design follows a **Dark Professional Tech Theme**, focusing on clean structure, high contrast readability, consistent spacing, and modern layout techniques using Flexbox and CSS Grid.

The website was built using a mobile-first approach and progressively enhanced with multiple breakpoints to ensure proper responsiveness across devices.

**Important:** No CSS frameworks (Bootstrap, Tailwind, etc.) were used. All CSS was written manually.

---

## Requirements

### Functional Requirements

This portfolio includes the required four sections:

| Section | Implemented Content |
|---------|--------------------|
| **Home/Hero** | Full name (Bornface Kangombe), professional tagline, call-to-action button |
| **About** | 150+ word professional bio, profile image, structured skills list |
| **Projects** | Three project cards including image, description, and action links |
| **Contact** | Accessible contact form with HTML5 validation attributes |

---

### Technical Requirements

| Requirement | Implementation |
|-------------|---------------|
| **HTML5** | Semantic structure using header, nav, main, section, article, footer |
| **CSS3** | External stylesheet only (css/styles.css) |
| **CSS Variables** | Custom properties used for colors, typography, and spacing |
| **Flexbox** | Used for navigation layout, alignment, and footer structure |
| **CSS Grid** | Used for project card layout and responsive grid structure |
| **Responsive** | Mobile-first approach with 3+ breakpoints |
| **Accessibility** | Alt attributes, form labels, proper heading hierarchy, readable contrast |

---

### Breakpoints Required

```css
/* Mobile-first base styles */

/* Tablet (768px and up) */
@media (min-width: 768px) { }

/* Desktop (1024px and up) */
@media (min-width: 1024px) { }

/* Large Desktop (1200px and up) - optional */
@media (min-width: 1200px) { }

## Project Structure

```
csc4035-assignment1-portfolio/
├── index.html          # Main HTML file
├── css/
│   └── styles.css      # Main stylesheet
├── images/             # Your images (profile, projects, etc.)
├── screenshots/        # Screenshots at different breakpoints
│   ├── mobile.png
│   ├── tablet.png
│   └── desktop.png
└── README.md           # This file (update with your info)
```

---

## Getting Started

1. **Clone this repository** to your local machine
2. **Open `index.html`** in your code editor
3. **Complete the TODO comments** in each file
4. **Test responsiveness** using browser developer tools
5. **Take screenshots** at mobile, tablet, and desktop sizes
6. **Commit and push** your changes regularly

---

## Grading Rubric (100 points)

| Criterion | Points | Description |
|-----------|--------|-------------|
| **HTML Structure & Semantics** | 20 | Valid HTML5, semantic elements, proper document structure |
| **CSS Styling & Design** | 20 | Professional design, cohesive color scheme, typography |
| **Flexbox & Grid Usage** | 20 | Both techniques used appropriately and effectively |
| **Responsive Design** | 20 | Mobile-first, 3+ breakpoints, no horizontal scrolling |
| **Content & Completeness** | 10 | All sections complete with quality content |
| **Code Quality** | 10 | Clean, organized, well-commented code |

### Automated Tests (40% of grade)

The following are checked automatically on each push:
- HTML validation (no errors)
- Required HTML elements present
- CSS file linked correctly
- Required sections exist
- Responsive meta tag present

---

## Submission Checklist

Before submitting, verify:

- [ ] All 4 sections are complete (Home, About, Projects, Contact)
- [ ] HTML validates with no errors
- [ ] CSS uses custom properties (variables)
- [ ] Flexbox is used for at least one component
- [ ] CSS Grid is used for at least one component
- [ ] Site is responsive at all breakpoints
- [ ] All images have alt text
- [ ] Form inputs have labels
- [ ] Screenshots added to `/screenshots` folder
- [ ] README updated with your information

---

## Your Information

**Name:** [Bornface Kangombe]
**Student ID:** [2022064526]
**Design Theme:** [Dark Professional Tech Theme]

### CSS Techniques Used
✔ CSS Custom Properties

✔ Flexbox

✔ CSS Grid

✔ Media Queries

✔ CSS Transitions
- [ ] Other: _______________

### Challenges & Solutions
[Describe any challenges you faced and how you solved them]
One of the main challenges was implementing a fully mobile-first layout while ensuring smooth scaling across tablet and desktop breakpoints. This was solved by carefully structuring the base mobile layout first, then progressively enhancing it using media queries.

Another challenge involved balancing contrast and readability within a dark theme. I resolved this by defining a consistent color system using CSS variables and testing contrast ratios to maintain accessibility.

Structuring the project cards using CSS Grid required experimentation to ensure proper responsiveness. I solved this by using grid-template-columns adjustments at each breakpoint.
### Credits
[All code in this project was written by me.
No CSS frameworks or external styling libraries were used.
All images are either personal or royalty-free placeholders]

---

## Academic Integrity

- All code must be your own work
- No CSS frameworks or libraries allowed
- Images must be royalty-free or your own (credit sources)
- Plagiarism detection tools will be used

**Violations result in zero marks and academic misconduct reporting.**

---

## Extension Opportunities (Bonus: up to +10%)

- Dark/light mode toggle with CSS (+3%)
- CSS animations/transitions (+3%)
- CSS-only hamburger menu (+2%)
- Print stylesheet (+2%)
