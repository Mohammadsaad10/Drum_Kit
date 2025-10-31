# 🥁 Drum Kit

A fun, interactive **Drum Kit** web app that lets users play drum sounds either by clicking buttons or pressing corresponding keyboard keys. Built with **HTML**, **CSS**, and **JavaScript** for quick response and engaging sound feedback.

---

## 📋 Table of Contents

- [Introduction](#-introduction)
- [Demo](#-demo)
- [Features](#-features)
- [Technologies Used](#technologies-used)
- [Project Structure](#-project-structure)
- [Installation](#installation)
- [Usage](#-usage)
- [Customization](#-customization)
- [Troubleshooting](#-troubleshooting)
- [Deployment](#-deployment)
- [Credits](#-credits)
- [License](#-license)

---

## 🎶 Introduction

The Drum Kit project is a simple front-end application that allows users to simulate a drum set. Each key press or button click triggers a unique drum sound (crash, snare, toms, or kick), accompanied by a short visual animation.

This project demonstrates:

- DOM manipulation in JavaScript
- Event handling for mouse clicks and keyboard input
- Audio playback in browsers
- CSS styling and animations

---

## 🌐 Demo

🎯 **[Live Demo](https://mohammadsaad10.github.io/Drum_Kit/)**

---

## 🧩 Features

- Play 7 different drum sounds (`w`, `a`, `s`, `d`, `j`, `k`, `l`)
- Responsive key and button interaction
- Smooth visual animation feedback
- Simple, intuitive layout
- Lightweight — no external libraries needed except Google Fonts

---

## Technologies Used

| Technology              | Purpose                                                 |
| ----------------------- | ------------------------------------------------------- |
| **HTML5**               | Defines the structure of the webpage                    |
| **CSS3**                | Provides the styling and button animations              |
| **JavaScript (ES6)**    | Handles event listeners, sound playback, and animations |
| **Google Fonts (Arvo)** | Font styling                                            |

---

## 📁 Project Structure

```
drum-kit/
├── index.html       # Main HTML file
├── styles.css       # Styling for layout and drum buttons
├── index.js         # JavaScript for sound and button logic
├── sounds/          # Folder containing .mp3 sound files
└── images/          # Folder with button background images
```

---

## Installation

1. **Clone or download** this repository:

   ```bash
   git clone https://github.com/Mohammadsaad10/Drum_Kit.git
   cd Drum-Kit
   ```

2. Make sure the following directories exist:

   ```
   /sounds
   /images
   ```

   and that they contain the appropriate `.mp3` and `.png` files as referenced in the code.

3. Open `index.html` in your preferred web browser.

---

## 🚀 Usage

- **Click** on any drum button with your mouse, or
- **Press** the corresponding keyboard keys:

| Key | Sound     |
| --- | --------- |
| w   | Crash     |
| a   | Kick Bass |
| s   | Snare     |
| d   | Tom 1     |
| j   | Tom 2     |
| k   | Tom 3     |
| l   | Tom 4     |

Each interaction plays the drum sound and triggers a short animation.

---

## 🎨 Customization

- To change **sounds**, replace the `.mp3` files inside `/sounds` and update the file names in `index.js`.
- To change **button images**, replace the `.png` files inside `/images` and adjust the CSS background-image paths in `styles.css`.
- You can modify the **color theme** in the CSS file by adjusting background and text color values.

---

## 🧩 Troubleshooting

| Issue                           | Solution                                                                                   |
| ------------------------------- | ------------------------------------------------------------------------------------------ |
| No sound plays                  | Check that your browser allows autoplay and that the `.mp3` files are in the correct path. |
| Buttons don’t animate           | Ensure `styles.css` is correctly linked in `index.html`.                                   |
| Keyboard doesn’t trigger sounds | Verify your keyboard event listener (`keydown`) is active in `index.js`.                   |

---

## 👨‍💻 Credits

Created with ❤️ by **Mohammadsaad**.  
Inspired by front-end learning projects from Appbrewery's web dev bootcamp focusing on event-driven interactivity.

---

## 📜 License

This project is open-source under the **MIT License** — feel free to use, modify, and share!
