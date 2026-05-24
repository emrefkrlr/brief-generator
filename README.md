# ⬡ AI Project Brief Generator

A free, open-source tool that turns your startup idea into a structured, AI-ready Markdown brief — in minutes.

No backend. No login. No cost. Just open `index.html` and start filling.

**→ [Try it live](https://your-username.github.io/brief-generator)**

---

## What it does

You fill in 10 structured sections about your project idea. When you're done, click **Generate Brief** to get a polished Markdown document you can paste directly into Claude, ChatGPT, Gemini, or any AI assistant.

The brief instructs the AI to:
- **Research before coding** — latest library versions, not 3-year-old examples
- **Verify free tier limits** — Heroku, Railway, Zoho change their plans often
- **Evaluate payment options** — Stripe vs Polar.sh vs Lemon Squeezy, VAT handling included
- **Deliver real outputs** — Docker Compose, `.env.example`, file tree, README, security checklist

---

## Screenshot

> _Add a screenshot here — `docs/screenshot.png`_

---

## Sections covered

| # | Section | What you fill in |
|---|---|---|
| 01 | Project Identity | Name, category, one-liner, revenue model |
| 02 | Problem & Solution | Target user, current workarounds, your differentiator |
| 03 | MVP Features | Must-have / nice-to-have / backlog |
| 04 | Tech Stack | Languages you know, framework preferences, local dev setup |
| 05 | Infrastructure | Hosting, DB, auth, email, storage — all verified for free tiers |
| 06 | User Flow | Step-by-step from landing to value moment |
| 07 | Revenue Model | Pricing tiers, paywall trigger, payment provider |
| 08 | References | Competitors, UI inspiration, gaps to exploit |
| 09 | Success Criteria | When is MVP done, first 30-day goal |
| 10 | Extra Context | Domain knowledge, risks, target geography |

---

## Getting started

```bash
# Clone the repo
git clone https://github.com/your-username/brief-generator.git

# Open in browser — no server needed
open index.html
```

Or just **[download index.html](index.html)** and open it directly. That's it.

---

## Deploy your own (GitHub Pages)

1. Fork this repo
2. Go to **Settings → Pages**
3. Set source: `main` branch, `/ (root)`
4. Your live URL: `https://your-username.github.io/brief-generator`

Free forever. No server. No config.

---

## Contributing

This project is built for the community — contributions of any size are welcome.

### Ways to contribute

| Type | Examples |
|---|---|
| 🐛 **Bug fix** | Layout broken on mobile, chip selection not working |
| ✨ **New feature** | Dark mode, save/load draft, new section |
| 🌍 **Translation** | UI in another language (form labels, placeholders) |
| 📋 **New section** | Team & hiring, compliance checklist, go-to-market |
| 🎨 **Design** | Better color scheme, typography, icons |
| 📝 **Docs** | Better README, usage examples, video walkthrough |
| 💡 **Ideas** | Open an issue — no code required |

### How to contribute

```bash
# 1. Fork the repo on GitHub

# 2. Clone your fork
git clone https://github.com/YOUR-USERNAME/brief-generator.git
cd brief-generator

# 3. Create a branch
git checkout -b feature/your-feature-name

# 4. Make your changes
# Everything lives in a single file: index.html
# No build step, no npm install, no dependencies.

# 5. Test in browser
open index.html

# 6. Commit and push
git add .
git commit -m "feat: add dark mode toggle"
git push origin feature/your-feature-name

# 7. Open a Pull Request on GitHub
```

### Contribution guidelines

- **Single-file architecture** — keep everything in `index.html`. No build tools, no bundlers.
- **No external dependencies** — Google Fonts is the only external resource. Keep it that way.
- **Test in Chrome and Firefox** before submitting.
- **Keep it accessible** — use semantic HTML, meaningful placeholder text.
- **One PR per feature** — keep changes focused and easy to review.

### Good first issues

If you're new to contributing, look for issues tagged `good first issue`. Some ideas to get started:

- [ ] Add a "Reset form" button
- [ ] Save draft to `localStorage` so progress isn't lost on refresh
- [ ] Add a dark mode toggle
- [ ] Make the sidebar collapsible on medium screens
- [ ] Add more payment provider options (e.g. Lemonsqueezy, Ko-fi)
- [ ] Add an "Export as PDF" button
- [ ] Add a section for "Team & co-founders"

---

## Project structure

```
brief-generator/
├── index.html        ← The entire app (HTML + CSS + JS)
├── README.md         ← This file
└── docs/
    └── screenshot.png  ← Add yours here
```

No package.json. No node_modules. No build pipeline.

---

## Design decisions

**Why a single HTML file?**
Zero friction to fork, host, share, or modify. Anyone can open it without installing anything. GitHub Pages serves it instantly.

**Why Solarized palette?**
Readable in both bright office light and dark rooms. Warm tones reduce eye strain during long sessions.

**Why Space Mono + Outfit?**
Space Mono signals "technical / developer tool" — the monospace makes code-like fields feel natural. Outfit is clean and modern for body text without being generic.

**Why no framework (React, Vue)?**
Keeps the barrier to contribution as low as possible. A designer who knows CSS can contribute without learning a JS framework.

---

## License

MIT — do whatever you want with it. Attribution appreciated but not required.

---

## Acknowledgements

Built with the idea that getting started on a side project shouldn't require 3 hours of planning documents. Fill this in, paste into your AI of choice, and ship.

---

_If this helped you launch something — open an issue and tell us about it. We'd love to hear._
