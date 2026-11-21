# Bunkmeter: College Attendance Planner

A smart college attendance planner and bunk calculator that calculates safe bunks and mandatory classes needed to maintain minimum attendance criteria.

## Features

- **Subject-wise attendance tracking**: Subject-wise attendance tracking: record attended classes and missed classes per course
- Customizable minimum required attendance threshold (e.g. 75% or 80%)
- **Smart Bunk Calculator**: Smart Bunk Calculator: calculates how many upcoming classes can be safely skipped without dropping below target
- **Catch-Up Calculator**: Catch-Up Calculator: computes how many consecutive classes must be attended if currently below threshold
- Quick one-tap logging buttons (+1 Attended, +1 Missed)
- Theme switcher and LocalStorage data persistence

## Tech Stack

- HTML5
- CSS3
- JavaScript (ES6+)
- LocalStorage API

## Screenshots

<!-- TODO: Add application screenshots here -->
![Bunkmeter: College Attendance Planner Screenshot](https://via.placeholder.com/800x450.png?text=Bunkmeter:+College+Attendance+Planner)

## Folder Structure

```
Bunkmeter/
├── attendance-planner.html
└── README.md
```

## Installation & Setup

This is a standalone, client-side web application. No complex build pipelines, database configurations, or package installations are required.

1. **Clone the repository:**
   ```bash
   git clone https://github.com/SSManikandaprabu/Bunkmeter.git
   cd Bunkmeter
   ```

2. **Run the application:**
   - **Direct Browser Launch**: Double-click `attendance-planner.html` to open it directly in any modern web browser (Chrome, Firefox, Safari, Edge).
   - **Or via Local HTTP Server**:
     ```bash
     python -m http.server 8000
     ```
     Then open [http://localhost:8000/attendance-planner.html](http://localhost:8000/attendance-planner.html) in your browser.

## Usage

1. Launch the application in your browser following the setup instructions above.
2. Interact with the application controls and input fields tailored for Bunkmeter: College Attendance Planner.
3. Preferences and data are stored locally in your browser's LocalStorage where applicable.

## Environment Variables

None required. Runs offline in browser.

## Live Demo Link

<!-- TODO: Add live demo link once deployed (e.g. GitHub Pages or Vercel) -->
_No live demo link currently configured. Refer to the TODO section below._

## Project Roadmap & TODOs

- [ ] Add screenshot of the attendance cards and bunk calculation summary

## Author

- **S.S. Manikanda Prabu** - [GitHub Profile](https://github.com/SSManikandaprabu)
