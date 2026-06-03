# NASA APOD Space Gallery 🌌

An interactive, beautifully designed single-page web app for exploring NASA's **Astronomy Picture of the Day (APOD)**. Browse this week's cosmic discoveries, travel back in time to any APOD since 1995, and save your favourite space images — all without any build tools or frameworks.

Built for the **NASA × Hack Club Stardance Challenge 2026** — open source.

---

## 🚀 Live Demo

**[👉 Click here to view the live site](https://YOUR-USERNAME.github.io/nasa-apod-gallery/)**

> Replace the link above with your actual GitHub Pages URL after deploying.

---

## ✨ Features

- **Today's APOD hero card** — large image, title, explanation, copyright, and date fetched live from NASA
- **7-day gallery grid** — responsive 3-col / 2-col / 1-col layout showing the past week of APODs
- **Full-screen modal** — click any image for an expanded view with the full explanation text
- **Date picker** — look up any APOD all the way back to June 16, 1995
- **Favourites** — heart any image to save it locally; a dedicated favourites section appears at the bottom
- **YouTube video support** — APODs that are videos show a thumbnail and open the video inline
- **Dark / Light mode** — toggle between Cosmic Dark and Eclipse Light themes, saved to browser storage
- **Skeleton loading** — animated placeholder cards while data is fetching
- **Error handling** — friendly retry button if the API is unavailable
- **Offline fallback gallery** — 20 real NASA images (shuffled randomly each session) shown when the API is rate-limited

---

## 🔑 Getting Your Free NASA API Key

The app ships with NASA's public `DEMO_KEY` which allows 30 requests/hour. For your own unlimited key (1,000 requests/hour):

1. Go to [api.nasa.gov](https://api.nasa.gov/)
2. Fill in your name and email — takes 30 seconds
3. Your key is emailed to you instantly
4. Open `index.html`, find `const NASA_API_KEY = "DEMO_KEY";` near the top of the `<script>` tag, and replace `"DEMO_KEY"` with your key
5. Save and redeploy — done

---

## 💻 Running Locally

No build step, no npm install, no terminal needed.

**Option 1 — Just open it:**
Download the repo and double-click `index.html` in your file manager. Opens directly in any browser.

**Option 2 — VS Code Live Server (recommended):**
1. Install the [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) extension in VS Code
2. Right-click `index.html` → **Open with Live Server**
3. The page auto-reloads whenever you edit the file

---

## 🛠 Tech Stack

| Layer | Choice |
|---|---|
| Markup | HTML5 (semantic) |
| Styles | CSS3 — custom properties, keyframes, grid, flexbox |
| Logic | Vanilla JavaScript ES6+ — async/await, localStorage |
| Data | NASA APOD API (api.nasa.gov) |
| Hosting | GitHub Pages |

Zero external frameworks. Zero build tools. One `index.html` file.

---

## 📁 Project Structure

```
nasa-apod-gallery/
├── index.html        ← the entire app (HTML + CSS + JS)
├── README.md
├── .gitignore
└── .env.example      ← documents the NASA_API_KEY (never commit your real key)
```

---

## 🤝 Open Source

MIT License — fork it, improve it, star it. Clear skies! 🌠
