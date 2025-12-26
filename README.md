# Simple Stopwatch

A basic stopwatch web application built with HTML, CSS, and JavaScript. It supports start, stop, and reset functionalities and displays the elapsed time in `HH:MM:SS` format.

---

## Features

- Displays elapsed time with hours, minutes, and seconds.
- Start button to begin timing.
- Stop button to pause timing.
- Reset button to clear the time and start over.
- Simple and clean UI (custom styling can be added).

---

## Installation

1. Clone or download this repository.

```bash
git clone https://github.com/yourusername/simple-stopwatch.git
```

2. Open the `index.html` file in your web browser.

---

## Usage

- Click **Start** to begin the stopwatch.
- Click **Stop** to pause the stopwatch.
- Click **Reset** to reset the timer to zero.

---

## File Structure

```
/ (root)
├── index.html      # The main HTML file containing stopwatch markup
├── style.css       # CSS styles for the stopwatch UI (optional)
└── script.js       # JavaScript logic for the stopwatch functionality
```

---

## How it Works

- The stopwatch counts seconds, minutes, and hours using `setInterval`.
- The display updates every second in `HH:MM:SS` format.
- Buttons control the timer start, stop, and reset actions.
- Prevents multiple intervals by checking if the timer is already running.

---

## Requirements

- Modern web browser (Chrome, Firefox, Edge, Safari).
- No additional dependencies.

---

## License

This project is for educational purposes

---

## Acknowledgements

This is a simple project to demonstrate JavaScript timing functions and DOM manipulation.
