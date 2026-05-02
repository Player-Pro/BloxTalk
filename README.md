# 🧱 BloxTalk — The Roblox Community Forum

> An independent, fan-made community forum for Roblox players, developers, and fans worldwide.

![BloxTalk Banner](https://img.shields.io/badge/BloxTalk-Community%20Forum-E8412A?style=for-the-badge&logo=roblox&logoColor=white)
![Status](https://img.shields.io/badge/status-in%20development-FFD046?style=for-the-badge)
![License](https://img.shields.io/badge/license-MIT-00B89C?style=for-the-badge)

---

## 📖 Table of Contents

- [About](#about)
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Getting Started](#getting-started)
- [Project Structure](#project-structure)
- [Forum Categories](#forum-categories)
- [Contributing](#contributing)
- [Roadmap](#roadmap)
- [License](#license)
- [Disclaimer](#disclaimer)

---

## About

BloxTalk is an open-source community forum built specifically for the Roblox community. Unlike Discord servers, BloxTalk provides a persistent, searchable, and structured space to discuss games, share developer resources, trade items, and connect with other players.

This repo contains the **landing page** and **frontend** for the BloxTalk website. The backend/API is maintained in a separate repository (link coming soon).

---

## Features

- 🎮 **Forum categories** covering games, dev help, trading, news, clans, and off-topic chat
- 🏅 **Rank & reputation system** — earn badges from Noob to Legend
- 🔔 **Smart notifications** — follow threads, categories, or users
- 🛡️ **Moderated & safe** — human mods + community reporting
- 🔎 **Powerful search** — filter by category, date, upvotes, or author
- 📌 **Pinned resource wikis** per category maintained by top contributors
- 📱 **Mobile-first responsive design**

---

## Tech Stack

| Layer | Technology |
|---|---|
| Frontend | HTML5, CSS3, Vanilla JS |
| Fonts | Google Fonts (Baloo 2, DM Sans) |
| Hosting (planned) | Vercel / Netlify |
| Backend (planned) | Node.js + Express |
| Database (planned) | PostgreSQL |
| Auth (planned) | JWT + OAuth |

> This project is currently **frontend only**. Backend contributions are welcome — see [Contributing](#contributing).

---

## Getting Started

### Prerequisites

- A modern web browser (Chrome, Firefox, Safari, Edge)
- [Git](https://git-scm.com/) installed
- Optional: [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) VS Code extension for local dev

### Installation

1. **Clone the repo**
   ```bash
   git clone https://github.com/your-username/bloxtalk.git
   cd bloxtalk
   ```

2. **Open the landing page**
   ```bash
   # Option A — just open the file directly
   open bloxtalk-landing.html

   # Option B — use Live Server in VS Code
   # Right-click bloxtalk-landing.html → "Open with Live Server"
   ```

3. **That's it!** No build step or dependencies required for the current frontend-only version.

---

## Project Structure

```
bloxtalk/
├── bloxtalk-landing.html   # Main landing page (self-contained)
├── README.md               # You're reading this
├── LICENSE                 # MIT License
└── assets/                 # (coming soon)
    ├── images/
    └── icons/
```

> As the project grows, this will be split into a proper `src/` structure with components, styles, and scripts separated.

---

## Forum Categories

| Category | Description |
|---|---|
| 🎮 Game Discussion | Reviews, rankings, and game recommendations |
| 🛠️ Dev Hub | Scripting, building, Lua help, Studio tutorials |
| 💰 Trading Post | Limiteds trading, price checks, scam alerts |
| 📰 News & Updates | Platform news, patch notes, community reactions |
| 🏆 Clans & Groups | Recruiting, group rankings, clan wars |
| 💬 Off-Topic Lounge | Memes, intros, polls, and everything else |

---

## Contributing

Contributions are welcome! Whether it's fixing a typo, improving the design, or building out the backend — all help is appreciated.

### How to contribute

1. Fork the repository
2. Create a new branch
   ```bash
   git checkout -b feature/your-feature-name
   ```
3. Make your changes and commit
   ```bash
   git commit -m "feat: add your feature description"
   ```
4. Push to your fork
   ```bash
   git push origin feature/your-feature-name
   ```
5. Open a **Pull Request** against the `main` branch

### Commit message convention

We use [Conventional Commits](https://www.conventionalcommits.org/):

| Prefix | Use for |
|---|---|
| `feat:` | New features |
| `fix:` | Bug fixes |
| `style:` | CSS / design changes |
| `docs:` | README or documentation updates |
| `chore:` | Maintenance tasks |

### Issues

Found a bug or have a feature idea? [Open an issue](https://github.com/your-username/bloxtalk/issues) and use the appropriate label (`bug`, `enhancement`, `question`).

---

## Roadmap

- [x] Landing page design
- [x] Category section
- [x] Trending threads section
- [x] Features & CTA sections
- [ ] Responsive mobile nav menu
- [ ] User registration & login
- [ ] Thread creation & replies
- [ ] Upvote / downvote system
- [ ] User profiles & badges
- [ ] Search functionality
- [ ] Dark / light mode toggle
- [ ] Backend API (Node.js)
- [ ] Database integration
- [ ] Admin moderation panel
- [ ] Email notifications

---

## License

This project is licensed under the **MIT License** — see the [LICENSE](LICENSE) file for details.

---

## Disclaimer

> BloxTalk is an **independent fan project** and is **not affiliated with, endorsed by, or sponsored by Roblox Corporation**. "Roblox" is a trademark of Roblox Corporation. This project exists purely as a community-driven initiative.

---

<p align="center">Made with ❤️ by the Roblox community, for the Roblox community.</p>
