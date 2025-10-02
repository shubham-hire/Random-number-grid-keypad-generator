# Random Number Grid Keypad Generator

A simple web prototype that generates a random-number grid keypad (for login / PIN entry / security UX experiments).

---

## Table of Contents

- [Motivation](#motivation)
- [Features](#features)
- [Demo / Screenshots](#demo--screenshots)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
  - [Usage](#usage)
- [Project Structure](#project-structure)
- [How it Works](#how-it-works)
- [Future Improvements](#future-improvements)
- [License](#license)
- [Contributing](#contributing)
- [Contact](#contact)

---

## Motivation

Normal numeric keypads can be predictable: users memorize positions, and attackers exploit shoulder surfing or pattern attacks.
This project explores randomized numeric grids (“scrambled keypads”) to improve security in PIN entry systems.
It can be embedded in login flows or used for usability/security research.

---

## Features

- Generates a randomized grid of digits (0–9) on each page load
- Responsive and works in browsers (desktop + mobile)
- Two layout variants (`main.html` / `main2.html`)
- Simple CSS styling (easy to extend or theme)
- Can be integrated into login pages for PIN input

---

## Demo / Screenshots

👉 *(Add a screenshot or GIF demo here — strongly recommended for credibility!)*

Example randomized grid:


7 | 1 | 5

2 | 9 | 3

6 | 0 | 8


---
## Getting Started

### Prerequisites
- A modern web browser  
- (Optional) Any local server if you don’t want to open HTML files directly  

### Installation

Clone the repository:

```bash
git clone https://github.com/shubham-hire/Random-number-grid-keypad-generator.git
cd Random-number-grid-keypad-generator
---
.
├── main.html
├── main2.html
├── Random Number Keypad Login.html
├── style.css
├── style2.css
├── loginlandscape2.jpg
├── AURA.jpg
├── CAT2 - PROBLEM STATEMENT.pdf
└── Random Number Keypad Login_files/
    ├── fiveserver.js
    ├── style.css
