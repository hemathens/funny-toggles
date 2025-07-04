<!-- Badges: build your brand at the top -->
[![GitHub stars](https://img.shields.io/github/stars/hemathens/funny-toggles?style=social)](https://github.com/hemathens/funny-toggles/stargazers)
[![Kaggle Profile](https://img.shields.io/badge/Kaggle-hem%20ajit%20patel-20BEFF?logo=kaggle)](https://www.kaggle.com/hemajitpatel)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Hem%20Ajit%20Patel-0A66C2?logo=linkedin)](https://www.linkedin.com/in/hem-patel19)
[![GitHub](https://img.shields.io/badge/GitHub-hemathens-181717?logo=github)](https://github.com/hemathens)

# Funny Toggles Showcase

A playful, interactive collection of 15 uniquely animated CSS/JavaScript toggles, each with its own character and theme. Explore a world of quirky, flabbergasting toggle animations—from black hole warps and to basketball and flips—all in one scrolling ribbon!

![Fun Toggle Ribbon](./screenshot.gif)

---

## 🔥 Live Demo

Deployed on Vercel: [https://funny-toggles.vercel.app](https://funny-toggles.vercel.app)

---

## 🚀 Features

* **15 Distinct Toggles**: Each toggle has a bespoke animation (e.g., Black Hole Warp, Caterpillar→Butterfly, Neon Sign Flicker).
* **Responsive Scrolling Ribbon**: A horizontal, scrollable strip showcasing all toggles, with smooth scroll-snap behavior.
* **Lazy-Loaded Animations**: Heavy animations only run when in view, boosting performance.
* **Keyboard & Touch Support**: Drag-to-scroll, arrow-key navigation, and accessible focus states.
* **Themed Backgrounds**: Subtle animated backgrounds adapt to each toggle’s theme.
* **Easy Customization**: Tweak colors, speeds, and easing via CSS variables.

---

## 🛠 Installation

1. **Clone the repo**

   ```bash
   git clone https://github.com/hemathens/funny-toggles.git
   cd funny-toggles
   ```
2. **Install dependencies** (if any build tools are used):

   ```bash
   npm install
   ```
3. **Run locally**

   ```bash
   # For a simple static site
   npx serve .
   # Or, if using a bundler/framework:
   npm run dev
   ```
4. **Open** your browser to `http://localhost:3000` (or the port your server indicates).

---

## 📂 Project Structure

```
funny-toggles/
├── index.html           # Main HTML file with toggle ribbon
├── css/
│   ├── style.css        # All toggle & layout styling
│   └── animations.css   # Keyframe definitions and variables
├── assets/              # SVGs, sprites, and demo gif
└── README.md            # This file
```

---

## ⚙️ Usage

* **Scroll** the ribbon horizontally to browse toggles.
* **Click** or **keypress** each toggle to see its animation.
* **Customize** via CSS variables in `style.css`:

  ```css
  :root {
    --toggle-speed: 1s;
    --accent-color: #ff4081;
  }
  ```

---

## 📦 Deployment

### Vercel

1. Install Vercel CLI:

   ```bash
   npm i -g vercel
   ```
2. Deploy:

   ```bash
   vercel --prod
   ```

### GitHub Pages

1. In `package.json`, add:

   ```json
   "homepage": "https://hemathens.github.io/funny-toggles"
   ```
2. Push to `main`, then enable Pages in repo **Settings → Pages → Source: main branch / (root)**.

---

## 🤝 Contributing

Contributions are welcome! To add a new toggle or improve existing ones:

1. Fork this repo.
2. Create a new branch: `git checkout -b feature/my-new-toggle`.
3. Commit your changes: `git commit -m "Add My New Toggle"`.
4. Push to your branch: `git push origin feature/my-new-toggle`.
5. Open a Pull Request.

Please follow the established code style and include clear documentation for any new animations.

---

## 📄 License

[MIT License](LICENSE)

---

> Crafted with ❤️ by Hem Ajit Patel to delight and inspire. Enjoy toggling!
