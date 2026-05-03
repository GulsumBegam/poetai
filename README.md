# 🖋️ Poet — AI Poem Generator

> *Describe a feeling, a scene, or an idea — and Poet will craft a unique poem just for you.*

A beautifully crafted, fully client-side AI poem generator chatbot. Built with vanilla HTML, CSS, and JavaScript — no backend or API keys required.

---

## ✨ Features

- **6 Poem Styles** — Free Verse, Rhyming, Haiku, Limerick, Ode, and Sonnet
- **Smart Theme Detection** — Automatically detects themes (Nature, Love, Sorrow, Hope, Time, Journey) from your descriptions
- **Keyword Personalization** — Extracts meaningful words from your prompt and weaves them directly into the poetry
- **Conversational UI** — Chat directly with the "Poet" AI personality
- **Copy & Regenerate** — Easily copy poems to your clipboard or regenerate for a fresh variation
- **Poem History** — A built-in sidebar keeps track of your recently generated poems
- **Ambient Design** — Atmospheric dark theme with floating golden particles for an immersive writing experience
- **100% Client-Side** — No servers, no API keys, no waiting. Runs entirely in your browser

---

## 🛠️ Tech Stack

- HTML5 & CSS3 (Custom Properties, Grid, Flexbox, Animations)
- Vanilla JavaScript (ES6)
- Font Awesome 6 (Icons)
- Google Fonts (Playfair Display & Lora)

---


## 🧠 How It Works

Instead of relying on external APIs, Poet uses a custom **Template-Based Generation Engine** built in JavaScript:

1. **Theme Detection** — Parses user input and scores it against a dictionary of theme-related keywords
2. **Couplet Banks** — Pulls from hand-written, rhyming couplet pairs categorized by theme
3. **Structure Assembly** — Assembles couplets into the correct poetic structure based on chosen style
4. **Keyword Injection** — Extracts nouns/adjectives from your prompt and injects them into dynamic placeholders
5. **Anti-Repetition Tracking** — Remembers recently used couplets to ensure fresh outputs every time

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

[![Live Demo](https://img.shields.io/badge/Live-Demo-purple?style=for-the-badge)](https://gulsumbegam.github.io/poetai/)

<p align="center">Made with ❤️ and a love for poetry</p>
