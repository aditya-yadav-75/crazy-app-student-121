# Wheel of Impossible Destiny

**Created by:** Aditya Yadav  
**Student Number:** #121  
**Live App:** https://YOUR-USERNAME.github.io/crazy-app-student-121/

Spin the neon wheel and let the universe pick one of eight ridiculous futures. This project is a single-file interactive web app made with HTML, CSS and JavaScript.

## How to Play

1. Open the live app link.
2. Click **SPIN THE UNIVERSE**.
3. Wait for the wheel to stop and read your result.
4. Check your spin count and chaos level.
5. Click **RESET** to start again.

## Features

- Eight randomized outcomes
- Neon cyberpunk interface
- Smooth spinning animation
- Sound effects created with the Web Audio API
- Spin counter and chaos meter
- Responsive layout for desktop and mobile
- Reset button
- Three `console.assert()` edge-case tests

## Secret Features

- The result is selected randomly each time.
- The sound is generated in the browser, so no audio files are required.
- The wheel has a hidden calculation that aligns the chosen result with the pointer.
- The code checks normal, zero and negative values using `console.assert()`.

## Technology Used

- HTML
- CSS
- JavaScript
- Web Audio API
- GitHub Pages

## Run Locally

Download or clone this repository and open `index.html` in a browser. No package installation or build command is required.

## Testing

Open the browser developer tools and select **Console**. The three `console.assert()` checks should run without assertion errors.

## AI Coding Lab: Debugging Exercise

For the lab demonstration, temporarily change `spinWheel` in the click listener to `spinWheeel`. Save and refresh the page, then inspect the Console. The page will report a `ReferenceError` because the misspelled function does not exist. Restore the name to `spinWheel` and refresh to fix the issue.

**One-sentence reflection:** I intentionally misspelled a function name, and the browser console helped me locate the undefined function so I could correct it.

## Analogy Comment

The source code includes this analogy above `spinWheel()`:

> The wheel is like a shopping trolley racing down a ramp — the extra full turns are its dramatic run-up, and the final angle parks it beside the chosen prize.

## Author

Aditya Yadav  
Student #121
