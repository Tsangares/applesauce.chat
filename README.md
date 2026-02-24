# applesauce.chat

Landing page for [applesauce.chat](https://applesauce.chat) — a solo dev studio building products fast.

## Stack

- Pure HTML / CSS / JS — no frameworks, no build step
- [Inter](https://fonts.google.com/specimen/Inter) + [JetBrains Mono](https://fonts.google.com/specimen/JetBrains+Mono) typography
- Mobile-first responsive design

## Features

- Dark-mode-first design with purple/indigo gradient accents
- Bento grid layout for capabilities showcase
- Mouse-tracking glow effect on cards
- Scroll-triggered reveal animations
- Glassmorphism navigation with auto-hide on scroll
- Terminal-style about section with typing animation
- Subtle film grain texture overlay
- Ambient background glow blobs
- Product cards with live/dev/coming-soon status badges
- Fully responsive — works on all screen sizes

## Development

Just open `index.html` in a browser. No build tools needed.

```bash
# or use a local server
python -m http.server 8000
```

## Deploy

This is a static site — deploy anywhere:

- **GitHub Pages** — push to `main` and enable Pages in repo settings
- **Cloudflare Pages** — connect the repo, build command: (none), output: `/`
- **Netlify** — drag and drop the folder
- **Vercel** — import the repo

## Customization

Edit `index.html` to update:

- **Hero text** — change the headline and subtitle
- **Products** — swap placeholder cards with real products
- **Links** — update Discord invite, GitHub, and email
- **Colors** — modify CSS variables in `:root` to rebrand
- **Terminal** — edit the terminal lines in the about section

## License

MIT
