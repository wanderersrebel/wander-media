# Wande Media — Social Content & Ad Site

Single-file static site (no build step). Open `index.html` in any browser.

## Deploy free (pick one)

### Option A — Netlify Drop (fastest, form works)
1. Go to https://app.netlify.com/drop
2. Drag the whole `wander-media` folder in.
3. Done — you get a live URL. The booking form works automatically
   (it uses Formspree).

### Option B — GitHub Pages
1. Push this folder to GitHub.
2. Repo Settings → Pages → source: `main` branch, `/root`.
3. The form posts via Formspree and works on GitHub Pages.

## What to edit
- **Logo / name**: `.logo` text near top of `<body>`.
- **Hero copy**: `.hero h1` and `.lead`.
- **Channels**: the `#channels` section with your three channel cards.
- **Services**: the four `.scard` items under `#services`.
- **Portfolio**: replace each `.shot .ph` placeholder with your real
  image (use `<img src="...">` or set a background). Keep 1080×1350 /
  9:16 / 1080×1080 sizes.
- **Calendar link**: the "Book a call" buttons → your Cal.com
  or Calendly URL.
- **Socials / email**: footer links + `wandererswindow@gmail.com`.
- **Colours**: the `:root` CSS variables (teal + ember brand).

## Channels
- **WanderHouse Tribe** — Afro x Club, Tribal Future
- **Mimi & Friends TV UK** — Kids animation
- **Wanderers Rebel Travel** — Travel shorts + long-form

## Colours
Teal `#2dd4bf` + Ember `#ff7a45` on near-black `#0b0f14`.
