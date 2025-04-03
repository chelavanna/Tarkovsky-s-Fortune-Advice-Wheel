# TARKOVSKY'S FORTUNE ADVICE WHEEL
#### Video Demo: 
#### Description:

## Overview
Tarkovsky's Fortune Wheel is a web-based application inspired by the poetic and philosophical works of Andrei Tarkovsky. Users spin a wheel and receive cryptic fortunes reminiscent of Tarkovsky's films.

## How It Works
* Users land on the main page, where they see the title and a Tarkovsky-themed spinning wheel.
* Pressing "Spin" triggers the animation, and after a few seconds, a fortune is revealed.
* The user is taken to a new page displaying their message.
* A "Back to Wheel" button allows them to return and spin again.

## Technologies Used
* Python (Flask): Backend framework to serve the web application.
* HTML & CSS: Used for structure and styling.
* JavaScript: Handles the wheel spin animation and page transitions.

## File Breakdown
* app.py → Main Flask backend.
* templates/ → HTML files (index.html for the wheel, advice.html for results).
* static/ → CSS, JavaScript, and images.
  - style.css → Styles for layout, animations, and transitions.
  - script.js → Handles spinning animation and navigation.
  - tarkovsky.png → Image used for the spinning wheel.

## Challenges & Learnings
1. Wheel Spinning Logic: Making the spin animation smooth and reset properly.
2. Page Transitions: Moving from the wheel page to the advice page in an aesthetically pleasing way.
3. Design Choices: Ensuring the cryptic messages feel authentic to Tarkovsky’s artistic vision.

## Installation & Usage
1. Clone the repository:
   ```sh
   git clone https://github.com/chelavanna/Tarkovsky-s-Fortune-Advice-Wheel
