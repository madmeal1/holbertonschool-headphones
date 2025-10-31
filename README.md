# Holberton School Headphones Web Page

This project is a fully functional, responsive web page for a fictional headphones brand, built from scratch using only HTML and CSS. No external libraries or frameworks are used. The design closely matches the provided Figma designer file, with careful attention to detail, accessibility, and responsiveness.

## Features

- **Pixel-perfect design**: Faithfully implements the Figma design, including layout, colors, and typography.
- **Responsive layout**: The page automatically adapts to mobile devices (screen width ≤ 480px) with a mobile-friendly version.
- **Accessibility**: Semantic HTML, proper alt text, keyboard navigation, and color contrast for an inclusive experience.
- **Interactive elements**:
  - Links change color to `#FF6565` on hover and active states.
  - Buttons have a hover/active opacity effect (`opacity: 0.9`).
- **Content width**: The main content is centered and constrained to a maximum width of 1000px for optimal readability.
- **Custom fonts**: Uses Source Sans Pro and Spin Cycle OT (see below for font installation).

## Getting Started

1. **Clone the repository**
   ```bash
   git clone https://github.com/madmeal1/holbertonschool-headphones.git
   cd holbertonschool-headphones
   ```
2. **Open `index.html` in your browser**
   - No build step or server is required.

## Fonts

If you are missing fonts, download them here:
- [Source Sans Pro](https://fonts.google.com/specimen/Source+Sans+Pro)
- [Spin Cycle OT](https://www.fonts.com/font/spin-cycle-ot)

Add the font files to your project and update the CSS `@font-face` rules if needed.

## Accessibility & Best Practices

- Uses semantic HTML elements (`<header>`, `<nav>`, `<main>`, `<footer>`, etc.).
- All images have descriptive `alt` attributes.
- Sufficient color contrast for text and interactive elements.
- Keyboard navigable: all links and buttons are accessible via keyboard.
- Responsive design ensures usability on all devices.

## Responsive Design

- The layout switches to a mobile-friendly version at 480px screen width or less.
- Navigation and content adapt for smaller screens.
- All content remains readable and accessible on mobile devices.

## Interactions

- **Links**: On hover/active, links change color to `#FF6565`.
- **Buttons**: On hover/active, buttons have `opacity: 0.9`.

## Project Structure

```
├── index.html        # Main HTML file
├── styles.css        # Main CSS file
├── assets/           # Images, fonts, and other assets
└── README.md         # Project documentation
```

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request.

## License

This project is for educational purposes at Holberton School.

---

**Enjoy your new headphones web page!**
