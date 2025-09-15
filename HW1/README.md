# Path@Penn – Stage 4 Prototype

## Overview
This repository contains my Stage 4 deliverable for the course project.  
The goal was to implement a **static, phone-sized HTML/CSS prototype** of my redesigned Path@Penn registration flow.  
The implementation faithfully matches my Stage 3 design mockups while being lightweight and responsive.

## Files
- **index.html** – Opening screen (Quick Enroll widget with four dropdowns + Register / Explore / View Cart buttons).  
- **register.html** – Search page with title prompt and search bar.  
- **course.html** – Static example course detail page for **CIS 1200** with session listings and Join buttons.  
- **style.css** – Shared stylesheet with CSS variables, layout, and component styles.  
- **logo.png** – Penn logo used in the ribbon header.

## Features
- Responsive header ribbon with logo and stacked title.  
- **Quick Enroll widget**: Level, Department, Course, Recitation dropdowns in one row.  
- Always-visible **conflict status** for CIS 1200 Rec 201.  
- **Modal dialog** on Register click:
  - Shows **success** for valid selections.
  - Shows **conflict** if CIS 1200 + Rec 201 is chosen.  
- Demo navigation:
  - “Register for a class” → `register.html`.  
  - Search → `course.html`.  
  - Course page shows CIS 1200 sessions, availability counts, inline conflict label, and Join buttons with modal feedback.

## How to Run
1. Clone this repo.  
2. Open `index.html` directly in your browser **or** use VS Code with the **Live Server** extension:  
   ```bash
   # in VS Code terminal
   npx live-server

## Attributions

- Portions of the HTML and CSS were generated using ChatGPT (GPT-5).  
  Specifically, I asked it to scaffold a mobile-friendly layout with a header, dropdown menus, and a register button.  
- I reviewed, tested, and modified all AI-generated code to ensure correctness and accessibility.
