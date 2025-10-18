# 🎬 Video Sharing Website — HTML & CSS

> A simple, elegant **video-sharing website** built using **HTML5** and **inline CSS**.  
> It demonstrates the use of semantic HTML structure, responsive layouts, and embedded media — perfect for beginners exploring front-end web design.

---

## 🧱 Project Overview

This project represents a **static video-sharing website**, built to simulate the core layout of platforms like **YouTube**.  
It features a **header**, **navigation bar**, **sidebar**, **main content area for videos**, and a **footer** — all styled directly within a `<style>` block.

---

## 🧩 Code Structure and Functionality

### 1️⃣ Document Structure

- Declares `<!DOCTYPE html>` to ensure **HTML5 compliance**.  
- Uses semantic elements — `<header>`, `<nav>`, `<main>`, and `<footer>` — to improve readability and accessibility.  
- The layout is organized into distinct, meaningful sections.

---

### 2️⃣ Header Section

- Displays the **site title:** `"My Video Sharing Site"`  
- Styled with:
  - Background: 🔴 `#ff0000`
  - Text color: ⚪ `white`
  - Alignment: centered for visibility and emphasis

```html
<header>
  <h1>My Video Sharing Site</h1>
</header>
```

---

### 3️⃣ Navigation Bar

- Contains links to: **Home**, **Trending**, **Subscriptions**, and **Library**.  
- Implemented using **Flexbox** for even spacing:
  ```css
  display: flex;
  justify-content: space-between;
  ```
- Styled with a dark theme (`#333`) and white text.

```html
<nav>
  <a href="#">Home</a>
  <a href="#">Trending</a>
  <a href="#">Subscriptions</a>
  <a href="#">Library</a>
</nav>
```

---

### 4️⃣ Sidebar

- Appears on the **left side** (25% width).  
- Lists categories like:
  - 🎵 Music  
  - ⚽ Sports  
  - 🎮 Gaming  
  - 📰 News  
- Styled with a light gray background (`#f4f4f4`) and vertical list layout.

```html
<aside>
  <ul>
    <li>Music</li>
    <li>Sports</li>
    <li>Gaming</li>
    <li>News</li>
  </ul>
</aside>
```

---

### 5️⃣ Main Content Area

- Occupies the **remaining 75%** of the width (beside the sidebar).  
- Displays **embedded YouTube videos** using `<iframe>` tags.  
- Each video is wrapped in a `<div class="video">` block.

```html
<main>
  <div class="video">
    <h2>Video Title 1</h2>
    <iframe src="https://www.youtube.com/embed/sample1" allowfullscreen></iframe>
  </div>

  <div class="video">
    <h2>Video Title 2</h2>
    <iframe src="https://www.youtube.com/embed/sample2" allowfullscreen></iframe>
  </div>
</main>
```

✅ **Responsiveness:**  
Each video uses `width: 100%; height: 315px;` for full container scaling.

---

### 6️⃣ Footer

- Stays fixed at the bottom with full-width coverage.  
- Contains:
  ```html
  <footer>© 2023 My Video Sharing Site</footer>
  ```
- Styled with dark background (`#333`) and white text for contrast.

---

## 🎨 CSS Styling Summary

Defined inside the `<style>` tag:

| Element | Key Properties |
|----------|----------------|
| `body` | Background: `#f9f9f9`, Font: sans-serif |
| `header` | Background: `#ff0000`, Text: white, Centered |
| `nav` | Flex layout, Background: dark gray, White links |
| `aside` | Float: left, Width: 25%, Background: `#f4f4f4` |
| `main` | Float: left, Width: 75% |
| `.video iframe` | Width: 100%, Height: 315px |
| `footer` | Fixed bottom, Full width, Background: dark gray |

---

## ⚙️ How the Code Works

1️⃣ **Layout Rendering**
- The browser displays the header first, then navigation links.  
- The body splits into:
  - Left sidebar for categories  
  - Right section for videos  
- Footer remains visible at the bottom.

2️⃣ **Responsive Behavior**
- Flexbox in navigation ensures link spacing on any screen size.  
- `<iframe>` videos auto-scale horizontally for consistent layout.

3️⃣ **Video Embedding**
- Uses YouTube’s `embed` URLs.  
- Attribute `allowfullscreen` enables fullscreen mode.

4️⃣ **Static Nature**
- No backend functionality — purely client-side.  
- Links are placeholders (`href="#"`).  
- Can be extended using **JavaScript** or **server-side** logic.

---

## 🚀 Potential Improvements

| Area | Enhancement |
|-------|--------------|
| **Responsiveness** | Replace floats with **Flexbox** or **CSS Grid** |
| **Interactivity** | Add **JavaScript** for dynamic content loading |
| **Backend** | Implement **user login**, **video uploads**, or **comments** |
| **Accessibility** | Add `alt` attributes and ARIA labels |
| **Styling** | Include hover animations, shadows, and transitions |

---

## 🧠 Learning Outcomes

Through this project, you’ll learn:
- Structuring web pages with **semantic HTML**
- Applying **inline CSS styling** for layout control
- Embedding multimedia content using `<iframe>`
- Managing layout using **float**, **Flexbox**, and **fixed positioning**
- Planning improvements for responsiveness and interactivity

---

## 👨‍💻 Author

**Sarbajit Kumar De**  
🎓 Front-End Developer in Training  
📧 `sarbajit.dev@outlook.com`  
🌐 [github.com/SarbajitDe](https://github.com/SarbajitDe)

---


---

> _“A simple start to web development — combining structure, style, and creativity in one HTML page.”_ 🌐✨
