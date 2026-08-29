# Wande Media — Social Content & Ad Site

Single-file static site (no build step). Open `index.html` in any browser.

## Deploy free (pick one)

### Option A — Netlify Drop (fastest, form works)
1. Go to https://app.netlify.com/drop
2. Drag the whole `content-service` folder in.
3. Done — you get a live URL. The booking form works automatically
   (it uses Netlify's `data-netlify="true"` attribute).

### Option B — GitHub Pages
1. Create a repo, push this folder.
2. Repo Settings → Pages → source: `main` branch, `/root`.
3. The booking form won't post on GitHub Pages. Either:
   - swap the `<form>` to a mailto link, or
   - use Formspree (formspree.io): set `action="https://formspree.io/f/XXXX"`
     and `method="POST"`, remove the `data-netlify` attrs.

## What to edit
- **Logo / name**: `.logo` text near top of `<body>`.
- **Hero copy**: `.hero h1` and `.lead`.
- **Stats**: the three `.stat` blocks.
- **Services**: the four `.card` items under `#services`.
- **Portfolio**: replace each `.shot .ph` placeholder with your real
  image (use `<img src="...">` or set a background). Keep 1080×1350 /
  9:16 / 1080×1080 sizes.
- **Calendar link**: the `#book` "Open my calendar" button → your Cal.com
  or Calendly URL.
- **Socials / email**: footer links + `hello@wande.media`.
- **Colours**: the `:root` CSS variables (teal + ember brand).

## Colours
Teal `#2dd4bf` + Ember `#ff7a45` on near-black `#0b0f14`.
