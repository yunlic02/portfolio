# Hosting your portfolio (free, ~10 minutes)

Your site is a self-contained folder: `index.html` + an `assets/` folder of images and video.
Any of these work — pick whichever feels easiest:

## Option A — Netlify Drop (fastest, no account needed to preview)
1. Go to https://app.netlify.com/drop
2. Drag the whole `portfolio-site` folder onto the page.
3. Netlify gives you a live URL immediately (e.g. `random-name-123.netlify.app`).
4. Sign up free to keep the link permanently and set a custom subdomain (e.g. `cetrinacheong.netlify.app`).

## Option B — GitHub Pages (good if you want a `github.io` link tied to your name)
1. Create a free GitHub account if you don't have one.
2. Create a new repository, e.g. `portfolio`.
3. Upload `index.html` and the `assets/` folder to it (GitHub's web uploader works fine — drag and drop).
4. Go to Settings → Pages → set source to the `main` branch, root folder.
5. Your site will be live at `https://<your-username>.github.io/portfolio/` within a few minutes.

## Option C — Just send the folder
If you don't want to host it yet, you can still zip this folder and attach it to
applications, or send it via WeTransfer/Google Drive — reviewers can unzip and open
`index.html` locally in any browser. It just won't have a shareable link.

---

## Before you send this out

A few things worth doing before this goes live:

- **Add your LinkedIn URL** — search `index.html` for `LinkedIn — add your URL` and replace
  the `href="#"` with your profile link.
- **Check with GetHarley** whether you're clear to publicly share practitioner-facing assets
  (the CurrentBody promo, product spotlight tiles, webinar posters) — some of this may be
  intended for internal or client use only.
- **Swap in the two photo slideshows I couldn't finish.** "Red Beauty & Brunch Club" and
  "Women's Health Mother's Day Shoot" (under Events & Activations) currently show placeholder
  slides because their source photos are `.HEIC` files, and this build environment has no HEIC
  decoder and no internet access to install one. Easiest fix on your Mac: select all the HEIC
  photos in Finder (in `Events & Activations/Red Beauty & Brunch Club with GetHarley/` and
  `Events & Activations/Mother's Day Shoot/`), right-click → Quick Actions → **Convert Image** →
  JPEG. Then in `index.html`, search for `slide-placeholder` and swap each placeholder `<div>`
  for an `<img>` tag pointing at the new JPEGs (copy the pattern already used for the other
  photos in those same slideshows — e.g. `iwd-photo-1.jpg`).
- **Fill in outcomes where you have them.** Several pieces (Synergy6 reel, GTG promo, sizzle
  reel, most of Design & Visual Identity and Campaigns & Email) are described by what you did,
  not what it achieved, because I didn't have a number to cite — the Practitioner AI Agent email
  in particular has no send-performance data at all, so it's described qualitatively only. If you
  get reach, saves, click-throughs, or feedback quotes for any of these, add a line like the
  "Contributed to..." ones already in the Reels section — it'll make those pieces noticeably
  stronger.
- **Swap in higher-res or additional images** if you have them — the Product Spotlight and IG
  Lives & Webinars slideshows in particular could take more entries if you add them to the
  matching subfolders and ask me to rebuild.
