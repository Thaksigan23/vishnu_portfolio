# Vishnutharan Bavachelvan — Portfolio

Personal portfolio website for **Vishnutharan Bavachelvan**, an IT undergraduate and aspiring software developer based in Jaffna District, Sri Lanka.

## Live Demo

> Deploy the site to Vercel, Netlify, or GitHub Pages to add your live URL here.

## Features

- **Hero** — typing role animation, profile photo, floating badges, and tech marquee
- **About** — bio, animated stats, education card, and interactive terminal visual
- **Journey** — school and university timeline
- **Skills** — filterable bento grid with circular progress rings
- **Projects** — responsive project showcase grid
- **Contact** — direct links and a contact form (FormSubmit.co)
- **Theme toggle** — dark/light mode with localStorage persistence
- **Animations** — scroll reveals, parallax, cursor glow, and magnetic buttons

## Tech Stack

- [Vite](https://vitejs.dev/) — build tool and dev server
- [TypeScript](https://www.typescriptlang.org/) — type-safe JavaScript
- [Tailwind CSS v4](https://tailwindcss.com/) — utility-first styling
- Vanilla TS (no React) — HTML rendered from `src/main.ts`

## Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) 18 or later
- npm

### Installation

```bash
git clone https://github.com/Thaksigan23/vishnu_portfolio.git
cd vishnu_portfolio
npm install
```

### Development

```bash
npm run dev
```

Open [http://localhost:5173](http://localhost:5173) in your browser.

### Build

```bash
npm run build
```

Output is written to the `dist/` folder.

### Preview production build

```bash
npm run preview
```

## Project Structure

```
vishnu_portfolio/
├── public/              # Static assets (profile photo, images)
├── src/
│   ├── data.ts          # Profile, skills, projects, and content
│   ├── main.ts          # Page layout and sections
│   ├── style.css        # Global styles and animations
│   ├── animations.ts    # Scroll and interaction effects
│   ├── ui.ts            # Theme toggle, back-to-top
│   └── ...              # Section-specific modules
├── index.html
├── vite.config.ts
└── package.json
```

## Customization

Most content lives in `src/data.ts`. Update profile details, skills, projects, and journey entries there. Replace placeholder links (email, WhatsApp, GitHub, Instagram) with real values before deploying.

The contact form uses [FormSubmit.co](https://formsubmit.co/). On first submit, activate the target email via the confirmation link FormSubmit sends.

## Author

**Vishnutharan Bavachelvan**

- LinkedIn: [vishnutharanbavachelvan](https://www.linkedin.com/in/vishnutharanbavachelvan-5419a02b3)
- GitHub: [Thaksigan23](https://github.com/Thaksigan23)

## License

This project is open source and available for personal use.
