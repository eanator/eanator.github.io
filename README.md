# Bingo Betty Website

Official website for **Bingo Betty**, the underground bingo roguelite.

## Live Site

[playbingobetty.com](https://playbingobetty.com)

## Structure

```
├── index.html          # Main landing page
├── presskit/
│   └── index.html      # Press kit page
├── assets/
│   ├── style.css       # Shared styles
│   ├── Stepalange.otf  # Custom font
│   └── images/         # All game assets
├── CNAME               # Custom domain config
└── .nojekyll           # Disable Jekyll processing
```

## Deployment

This site is hosted on GitHub Pages.

### Setup Instructions

1. Create a new GitHub repository
2. Push all files to the `main` branch
3. Go to **Settings → Pages**
4. Set Source to "Deploy from a branch" and select `main`
5. The CNAME file will configure the custom domain automatically

### DNS Configuration

Add these DNS records to your domain registrar:

**For apex domain (playbingobetty.com):**
- Type: `A`
- Name: `@`
- Value: `185.199.108.153`
- Value: `185.199.109.153`
- Value: `185.199.110.153`
- Value: `185.199.111.153`

**For www subdomain (optional):**
- Type: `CNAME`
- Name: `www`
- Value: `<your-github-username>.github.io`

## Links

- [Steam Page](https://store.steampowered.com/app/4045170/Bingo_Betty/)
- [Twitter/X](https://x.com/BingoBettyGame)
- [Gameplay Trailer](https://www.youtube.com/watch?v=rKn2ACMp2dw)

---

© 2025 Elias Austin. All rights reserved.
