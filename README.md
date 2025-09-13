````markdown
# 💧 Water Sort Mock‑Up

An interactive front-end prototype of a "Water Sort" puzzle game, developed using HTML, CSS, and JavaScript. This mock-up simulates the drag-and-drop gameplay where colored water layers are sorted into matching containers.

---

## 🧠 What is Water Sort?

"Water Sort" is a relaxing puzzle game where the goal is to sort colored liquids in test tubes until each tube contains only one color. This mock-up demonstrates the game’s basic mechanics and interface without using external libraries or a backend.

---

## 🗂️ Project Structure

| File            | Purpose                                      |
|------------------|----------------------------------------------|
| `index.html`     | The main HTML file containing the game board. |
| `styles.css`     | Styling for layout, tubes, and colors.       |
| `script.js`      | Game logic: handles user input and color movement. |
| `/assets`        | (Optional) For images or screenshots if added. |

---

## 🚀 Getting Started

You don’t need any backend or build tools to run this. It’s pure front-end.

### 1. Clone the Repo

```bash
git clone https://github.com/0wethu/water-sort-mock-up.git
cd water-sort-mock-up
````

### 2. Open in Browser

You can open `index.html` directly:

* Double-click the file
  **OR**
* Use Live Server (recommended for dev):

```bash
# If using VSCode
# Install "Live Server" extension
# Right-click on index.html → "Open with Live Server"
```

---

## 🕹️ How to Play

1. Click a **tube** to select it (source).
2. Click another tube to **pour** the top color into it (destination).
3. You can only pour if:

   * The destination has space
   * The top color matches
4. Try to make each tube contain **only one color**.

---

## 📸 Screenshots

> Replace these placeholders with your actual images

### 🖼️ Game Start

![Start of Game](./assets/screenshot-start.png)

### 🧪 Mid-Game Interaction

![During Play](./assets/screenshot-play.png)

### ✅ Completed Puzzle

![Puzzle Solved](./assets/screenshot-complete.png)

> 💡 To add your own screenshots:
>
> * Take a screenshot (e.g. `Shift + Cmd + 4` on Mac)
> * Save it in a folder named `assets/` inside the repo
> * Reference it like `![Alt text](./assets/your-image.png)`

---

## 💡 Example Code (JS Snippet)

```javascript
function pour(fromTube, toTube) {
  const color = fromTube.pop();
  if (canPour(color, toTube)) {
    toTube.push(color);
  }
}
```

---

## 🧰 Future Enhancements

* Add animations or transitions
* Add win detection
* Add “undo” and “reset” buttons
* Support touch controls for mobile
* Add level system with difficulty scaling

---

## 🤝 Contributing

1. Fork the repository
2. Create a new branch (`feature/undo-button`, `fix/mobile-bug`, etc.)
3. Make your changes
4. Submit a pull request with a clear description

---

## 📄 License

This project is licensed under the **Innotech Advisors License**.

---

© 2025 Innotech Advisors. All rights reserved.

Redistribution and use in source and binary forms, with or without modification, are permitted **for educational and non‑commercial purposes only**, provided that:

* This project retains the above copyright
* Attribution is given to the original author
* Commercial use or redistribution is **not allowed** without prior written permission from Innotech Advisors

For commercial licensing inquiries, contact: **[legal@innotechadvisors.com](mailto:legal@innotechadvisors.com)**

---

## 📬 Contact

**Author:** [@0wethu](https://github.com/0wethu)
**Org:** Innotech Advisors
**Live Demo:** *Coming Soon*

---

```

