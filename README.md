# Brajesh Kumar Singh — Interactive Portfolio & CV

Professional, modern, fully interactive single-page portfolio website.

## What's Included

- **Hero** with professional photo and strong personal branding (Brajesh Kumar Singh | Arahaan)
- **About** section with key stats
- **Interactive Experience Timeline** — click any role to see full details in modal
- **Skills** section with beautiful hover interactions
- **My Works** — fully filterable grid (Web Apps, Presentations, Excel & Data, AI Creations, Writing & Books)
  - 8 curated project cards
  - Click any card to open rich detail modal
- **Featured Literary Work** — dedicated beautiful section for *"Itvaar Ka Ek Din"* by Arahaan
- **Social + Contact** with working form (simulated submission)
- Fully responsive, dark modern professional theme with emerald accents
- Downloadable resume (original .docx)
- Keyboard accessible (ESC closes modals)

## How to Host on Vercel (Recommended)

### Option 1: GitHub + Vercel (Best for updates)

1. Create a new repository on GitHub (e.g. `brajesh-portfolio`)
2. Upload the entire folder contents (or `git push`)
3. Go to [vercel.com](https://vercel.com) → Import Project → Select your GitHub repo
4. Vercel will auto-detect it as a static site and deploy instantly
5. Your live URL will be something like `https://brajesh-portfolio.vercel.app`

### Option 2: Direct Deploy (Drag & Drop)

1. Zip the `brajesh-kumar-portfolio` folder
2. Go to Vercel Dashboard → Add New Project → "Import Third-Party Git Repository" or use the "Deploy" button for static files (Vercel supports drag-and-drop for simple static sites in some flows)
3. Or use Vercel CLI if preferred:
   ```bash
   npm i -g vercel
   vercel --prod
   ```

## Customization Tips

- **Add real projects**: Edit the `worksData` array in `index.html` (around line ~420). Each object has `category`, `title`, `shortDesc`, `desc`, `tools`, `impact`.
- **Update social links**: Change the `href` values in the Social section.
- **Book details**: The book modal and section can be expanded with real excerpts or purchase links later.
- **Add more experience**: The `experiences` array in JS can be extended.
- The resume download button links to `assets/resume.docx` — keep it updated.

## Tech Stack

- Pure HTML + Tailwind CSS (via CDN)
- Vanilla JavaScript (no dependencies)
- Font Awesome icons
- Fully self-contained — no build step required

---

Created with care for Brajesh Kumar Singh (Arahaan).  
This is a living portfolio — update the Works section as you create new campaigns, visuals, and stories.

**Live demo ready to deploy instantly on Vercel.**