# Kishan Kalola — Portfolio Deployment Guide

Your portfolio is in **`index.html`** (single file — photo, styles, scripts all embedded).
Your CV PDF is **`Kishan_Kalola_CV.pdf`** — keep it next to `index.html` so the "Download CV" button works.

---

## 🎨 Design system reference (save this)

**Style direction:** Apple/Stripe-level refined minimalism — premium, calm, professional.

**Colors:**
- `--bg: #fbfbfd` — main background (warm off-white)
- `--bg-warm: #f5f5f7` — alternate section background
- `--bg-dark: #1d1d1f` — dark sections (feature metric, contact)
- `--ink: #1d1d1f` — primary text
- `--ink-soft: #424245` — secondary text
- `--muted: #6e6e73` — tertiary text
- `--accent: #0a4d8c` — deep navy blue (links, accents)
- `--gold: #b8956a` — warm gold (italic accents on dark backgrounds)
- `--success: #00875a` — green dots / "Available" status

**Fonts:**
- Inter (300–800) — all sans-serif text
- Instrument Serif (italic) — accent words like "*measured*", "*introduction*", "*scale*"

**Design principles:**
- Generous whitespace
- One bold statement per section
- Soft shadows, rounded corners (14–24px)
- Subtle hover lifts (-2px translateY)
- Soft 0.9s fade-up reveal animations
- No bold colors, no shouty animations

---

## 🚀 Deploy to GitHub Pages (5 minutes)

### Step 1 — Create a new repo
1. Go to https://github.com/new (sign in)
2. Repository name: **`portfolio`** (exactly this, lowercase)
3. Set to **Public**, don't initialize with README
4. Click **Create repository**

### Step 2 — Upload your files
1. On the empty repo page, click **"uploading an existing file"**
2. Drag and drop BOTH: `index.html` and `Kishan_Kalola_CV.pdf`
3. Scroll down, click **Commit changes**

### Step 3 — Enable Pages
1. **Settings** → **Pages** (left sidebar)
2. Source: **Deploy from a branch**
3. Branch: `main` / `(root)` → **Save**
4. Wait 1–2 minutes. Live at:

```
https://kalolakishan.github.io/portfolio/
```

### Step 4 — Share it
- Pin it on LinkedIn (Featured section + bio link)
- Add the URL to your CV header
- Paste it in every cold email / WhatsApp outreach

---

## ✏️ How to edit in another Claude conversation later

Save these 3 files: `index.html`, `Kishan_Kalola_CV.pdf`, this `DEPLOY.md`.

In a future Claude chat, upload `index.html` and paste this:

```
I have an existing portfolio website built as a single HTML file.
I'm attaching index.html. Please read it fully before changing anything.

Design context (do not change these unless I ask):
- Style: Apple/Stripe-level refined minimalism
- Colors: --bg #fbfbfd, --bg-warm #f5f5f7, --bg-dark #1d1d1f, --ink #1d1d1f,
  --accent #0a4d8c (deep navy), --gold #b8956a (italic accents),
  --success #00875a, --muted #6e6e73
- Fonts: Inter (sans) + Instrument Serif (italic accents)
- Photo is embedded as base64 — DO NOT remove or replace
- Chart is custom SVG — DO NOT replace with Chart.js or any library
- Mobile breakpoints: 880px and 720px

What I want to change:
[describe your changes]

Please output the complete updated index.html as a file.
```

---

## 🔄 Quick edits without Claude

For small text edits (faster than waiting for AI):

1. Open `index.html` in any text editor (VS Code, Notepad, even GitHub's web editor)
2. Use **Find & Replace** (Ctrl+F / Cmd+F)
3. Common edits:
   - Update phone: search `8128488070`
   - Update email: search `kalolakishan07@gmail.com`
   - Update metric: search `₹54L` or `₹1.2Cr` or `1000+`
   - Add a skill: find `<li>Google Search & Display` and copy-paste a new line

---

## 🌐 Custom domain (optional, ~₹800/year)

To use `kishankalola.com` instead of github.io:

1. Buy at **Namecheap** or **GoDaddy**
2. Repo → Settings → Pages → Custom domain → enter `kishankalola.com`
3. At your domain registrar, add DNS:
   - 4 A records → `185.199.108.153`, `185.199.109.153`, `185.199.110.153`, `185.199.111.153`
   - 1 CNAME: `www` → `kalolakishan.github.io`
4. Done — free HTTPS auto-enables in ~10 min

---

## ✅ What's in this portfolio

- Glass-effect nav with "Get in touch" CTA
- Hero with "Performance marketing, *measured.*" + photo (with glassmorphic name plate)
- 4-stat band (2+ yrs · ₹14L/mo · 10× · 1000+)
- "A short *introduction*." section with tool ticker
- **Dark-section ₹54L → ₹1.2Cr hero metric** (silver gradient numbers, gold arrow)
- 6 results cards (ROAS, Revenue, Budget, Leads, CPL, Reach)
- Animated SVG revenue chart (navy, soft gradient fill)
- Newspaper-style experience timeline (3 roles)
- 4 case study cards (Hexakill, Summer Waves, Isha, Metropolis)
- Skills with Expert/Advanced/Intermediate levels
- 4 certification cards
- Dark contact section: "Let's *scale* something together."
- All links live: Email, Phone, LinkedIn, WhatsApp, CV download
- Mobile responsive (390px → 1440px tested)

Good luck — go close some interviews 🚀
