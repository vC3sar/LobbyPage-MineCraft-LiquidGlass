# 🖤 Lobby Page

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JS-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)

A visually appealing landing page with **liquid glass effects**, dynamic content, and a Discord button. Perfect for upcoming projects, game servers, or communities.

![pagewww](https://i.ibb.co/RTj7sc33/chrome-s-FDngfv-C8d.png)

---

## 🌟 Features

- **Liquid glass design:** Frosted glass effect for container, logo, and buttons.
- **Dynamic loader:** Animated dots sequence (`Cargando... . .. ...`).
- **Configurable content:** Controlled entirely via `config.js`:
  - Background image/color
  - Logo
  - Title
  - Description
  - Discord button text & link
  - Loader text
- **Discord button:** Includes hover shine effect for elegance.
- **Responsive design:** Works on desktop and mobile.

---

## 🚀 Installation

1. Clone or download the repository:

```bash
git clone https://github.com/yourusername/lobby-page.git
```

## Make sure your folder contains:

- index.html
- style.css
- config.js
- favicon.jpg (or change in index.html)
- background.jpg (or your preferred background)

## ⚙️ Configuration (config.js)

All page content is dynamic. Edit config.js to customize:

```
const CONFIG = {
    background: "url('./background.jpg') no-repeat center center fixed",
    logo: "logo.png",
    title: "WELCOME TO MY SERVER",
    description: "JOIN OUR COMMUNITY AND ENJOY THE GAME!",
    buttonText: "JOIN DISCORD",
    discordLink: "https://discord.gg/example",
    loaderText: "CARGANDO..."
};
```

## 🎨 Customization

- Background: Modify CONFIG.background or add effects in style.css.

- Logo: Replace CONFIG.logo with your image.

- Loader speed: Adjust interval in index.html (default 1000ms).

- Liquid glass effects: Modify backdrop-filter, box-shadow, or CSS animation for shine.

- Button hover effect: Tweak .btn:hover for more glow or scale.

## 🌐 Live Preview

- Open index.html in any modern browser to see the loader, logo, title, description, and Discord button animate dynamically.

## 📱 Browser Support

- Modern browsers with CSS backdrop-filter support (Chrome, Edge, Safari, Firefox with flags).

- Fully responsive for mobile and desktop screens.

## 🔗 Discord Button

### The Discord button is fully configurable:

- Text: CONFIG.buttonText

- Link: CONFIG.discordLink

- Hover: Shine animation included

## 📝 License

This project is free to use and modify BUT NOT MONETIZE.
Feel free to adapt and customize for your personal or community projects.

⚡ Credits

Design inspired by liquid glass aesthetic
# LobbyPage-MineCraft-LiquidGlass
