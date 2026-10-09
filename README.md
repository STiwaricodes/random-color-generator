# Random Color Palette Generator

A simple and interactive web project built using HTML, CSS, and JavaScript. It generates random color palettes and allows users to copy HEX color codes to the clipboard.

## Features

- Generate a palette containing five random colors.
- Display the HEX code for each color.
- Copy HEX color codes to the clipboard.
- Show a visual confirmation when copying a color.
- Responsive color palette layout.
- Smooth hover effects and a clean user interface.

## Technologies Used

- **HTML5** — Structure of the application.
- **CSS3** — Styling, grid layout, and animations.
- **JavaScript** — Random color generation and clipboard functionality.
- **Google Fonts (Poppins)** — Typography.
- **Font Awesome** — Icons for copying color codes.

## How It Works

1. Click the **Generate Palette** button to generate random colors.
2. Each color is generated using a random six-character hexadecimal code.
3. The generated HEX code is displayed below its color.
4. Click a color or its copy icon to copy the HEX code.
5. A visual confirmation appears when a color is copied.

## Project Structure

```text
random-color-generator/
├── index.html
├── style.css
├── script.js
└── README.md
```

## How to Run Locally

1. Clone or download the repository.
2. Keep `index.html`, `style.css`, and `script.js` in the same folder.
3. Open `index.html` in your web browser.
4. Click **Generate Palette** to explore random colors.

No package installation or build tools are required.

## Current Limitations

- Generated palettes are not saved after refreshing the page.
- There is no option to lock a color while generating a new palette.
- Clipboard functionality may require a secure context, such as HTTPS or localhost, depending on the browser.

## Future Improvements

- Save favorite color palettes.
- Add a lock option for individual colors.
- Export palettes as CSS variables.
- Add a one-click option to copy the entire palette.
- Add different palette-generation modes.

## License

This project is created for learning and practice purposes. Add a formal license if you plan to distribute it publicly.