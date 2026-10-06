# Contributing to A Nest Level Portfolio

This guide outlines how to get involved. By participating, you agree to abide by our [Code of Conduct](CODE_OF_CONDUCT.md) (feel free to create one if it doesn't exist yet!).

## 🚀 Getting Started

1. **Fork the Repo**:
   - Head to [the repo](https://github.com/portfolio) and click **Fork**.
   - Clone your fork: `git clone https://github.com/YOUR_USERNAME/danuzz-portfolio.git`.
   - Create a feature branch: `git checkout -b feature/amazing-idea`.

2. **Set Up Locally**:
   - Install deps: `npm install`.
   - Run dev server: `npm run dev`.
   - Test your changes at `http://localhost:5173`.

3. **Explore the Code**:
   - **HTML**: Core structure in `index.html`.
   - **CSS**: Custom styles + Tailwind in `src/main.css`.
   - **JS**: Animations & logic in `src/main.js`.
   - **Config**: Vite magic in `vite.config.js`.

## 📋 Contribution Types

We welcome all kinds of contributions! Here's what fits best:

| Type | Description | Label |
|------|-------------|-------|
| **🐛 Bug Fix** | Spot a glitch? (e.g., animation stutter on mobile) | `bug` |
| **✨ Feature** | New idea? (e.g., theme switcher or more work cards) | `enhancement` |
| **📖 Docs** | Improve README or add guides? | `documentation` |
| **🔧 Refactor** | Clean up code without changing behavior? | `refactor` |
| **🎨 Style** | Tweak designs or animations? | `design` |
| **🚀 Performance** | Optimize bundle size or scroll? | `performance` |

### Submitting Pull Requests (PRs)
1. **Make Changes**:
   - Commit atomically: `git commit -m "feat: add dark mode toggle"`.
   - Push: `git push origin feature/amazing-idea`.

2. **Open PR**:
   - Link to the issue (e.g., "Fixes #42").
   - Describe: What? Why? How tested?
   - Add screenshots/GIFs for visual changes.

3. **PR Guidelines**:
   - **Small & Focused**: One change per PR.
   - **Tested**: Run `npm run build` and `npm run preview`.
   - **No Breaking Changes**: Update without wrecking existing setups.
   - **Squash Commits**: We'll merge cleanly.

## 🏗 Development Workflow

### Code Style
- **JS**: ES modules, consistent with Prettier (run `npx prettier --write .`).
- **CSS**: Tailwind utilities first; custom only when needed.
- **HTML**: Semantic, accessible (e.g., alt texts, ARIA labels).
- **Commits**: Use conventional commits (e.g., `feat:`, `fix:`, `docs:`).

### Testing
- **Manual**: Browser dev tools for animations; Lighthouse for perf/accessibility.
- **Build Check**: `npm run build` should output a single, minified `index.html` (<1MB).
- **Edge Cases**: Test on mobile, dark mode, slow networks.

## ❤️ Credits

This project stands on the shoulders of giants:
- **GSAP & Lenis**: For fluid animations.
- **Tailwind & Vite**: Powering the build.
- **Remix Icon**: Clean SVGs.
- **You!** – Every star, fork, and PR fuels the fire.

---
