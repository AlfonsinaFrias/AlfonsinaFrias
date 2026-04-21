# Alfonsina Frias Vargas — Personal Website

## Files included

| File | Page |
|------|------|
| `index.html` | Home page |
| `about.html` | About page |
| `portfolio.html` | Portfolio (both collections) |
| `italy.html` | Impactful Partnership in Italy (detail) |
| `PROJECT-TEMPLATE.html` | Template — duplicate this for each new project |
| `style.css` | All shared styles |

---

## How to publish on GitHub Pages

1. Go to [github.com](https://github.com) and sign in
2. Click **New repository**
3. Name it exactly: `yourusername.github.io` (use your real GitHub username)
4. Set it to **Public**, then click **Create repository**
5. Upload ALL the files in this folder (index.html, about.html, style.css, etc.)
   - Click **Add file → Upload files**
   - Drag everything in, including the `images/` folder
6. Go to **Settings → Pages**
7. Under "Source", select **Deploy from a branch → main → / (root)**
8. Click Save — your site will be live at `https://yourusername.github.io` within a minute!

---

## Adding your photos

Create a folder called `images/` and place your photos inside it. Then update the `src` attributes in the HTML files.

### Photos needed:

**Shared:**
- `images/avatar.jpg` — Your small circular profile photo (nav bar)

**Home page (index.html):**
- `images/hero-1.jpg` — Left hero image (tall/portrait orientation)
- `images/hero-2.jpg` — Center hero image (your main portrait)
- `images/hero-3.jpg` — Right hero image
- `images/work-1.jpg` — Experiential initiatives preview card
- `images/work-2.jpg` — Research preview card

**About page (about.html):**
- `images/about-portrait.jpg` — Your full portrait on the about page

**Italy project (italy.html):**
- `images/italy-hero.jpg` — Main hero photo (right side, large)
- `images/italy-1.jpg` through `italy-5.jpg` — Gallery photos

**Portfolio thumbnails (portfolio.html):**
- `images/italy-thumb.jpg`
- `images/bte-thumb.jpg`
- `images/delasalle-thumb.jpg`
- `images/brunchibition-thumb.jpg`
- `images/cemla-thumb.jpg`

---

## Adding new project pages

1. Duplicate `PROJECT-TEMPLATE.html`
2. Rename it (e.g. `bte-design-sprint.html`)
3. Edit the title, description, photo paths, and links inside
4. In `portfolio.html`, update the `href` on the matching project card to point to your new file

---

## Customizing text

All content is plain HTML — just open the files in any text editor (TextEdit, Notepad, or VS Code) and change the text between the tags.

For example, to update your email:
- Open `index.html`
- Find `friasvargas@gmail.com` and replace with your email
