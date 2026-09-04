# Applications Marketing Landing Pages

Official product landing pages directory for our iOS, Android, and web applications.

---

## Directory Structure

```
landings/
├── index.html              # Hub directory page showcasing all products
├── deepy/
│   ├── index.html          # Deepy Flagship Landing Page (/deepy)
│   └── assets/
│       ├── icon.png        # App Icon
│       └── screenshots/    # High-resolution iOS app screenshots (1.png - 8.png)
├── _template/
│   └── index.html          # Starter template for future app landing pages
└── README.md
```

---

## Live URLs for Marketing & App Store Connect

| Field | URL |
|---|---|
| **Deepy Marketing URL** | `https://quangvietnguyen.github.io/landings/deepy/` |
| **All Apps Hub** | `https://quangvietnguyen.github.io/landings/` |
| **Deepy Support URL** | `https://quangvietnguyen.github.io/support/deepy/` |
| **Deepy Privacy Policy** | `https://quangvietnguyen.github.io/privacy/deepy/` |

---

## Deploying to GitHub Pages

1. Push to GitHub:
   ```bash
   cd /home/vietnguyen/dev/landings
   git init
   git add .
   git commit -m "feat: launch Deepy landing page and multi-app product hub"
   git branch -M main
   git remote add origin git@github.com:quangvietnguyen/landings.git
   git push -u origin main
   ```
2. In GitHub repository: **Settings** → **Pages** → Source: **Deploy from a branch** (`main` / `/root`).
3. Your live landing page will be at `https://quangvietnguyen.github.io/landings/deepy/`.

---

## Adding a New App Landing Page in the Future

1. **Copy Template:**
   ```bash
   cp -r _template new-app
   mkdir -p new-app/assets/screenshots
   ```
2. **Add Visuals:** Put your app screenshots into `new-app/assets/screenshots/`.
3. **Register in Hub:** Add a card in [`landings/index.html`](file:///home/vietnguyen/dev/landings/index.html).
