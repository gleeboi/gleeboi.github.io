# GLEEBOI — Portfolio

Personal portfolio site for **Oshinibosi Abdulazeem (GLEEBOI)**, Data Scientist / Machine Learning Engineer.

Built with plain HTML5, CSS3, and vanilla JavaScript — no frameworks, no build step. Deploys directly to GitHub Pages.

## Folder structure

```
portfolio/
├── index.html
├── css/
│   ├── style.css        # design tokens, layout, components
│   ├── animations.css   # scroll-reveal keyframes/classes
│   └── responsive.css   # breakpoints
├── js/
│   ├── app.js            # nav, loader, scroll progress, reveal, typing, ripple
│   └── particles.js      # canvas constellation background
├── assets/
│   ├── images/            # (empty — see below)
│   ├── icons/              # (empty — inline SVGs used instead)
│   ├── svg/                # (empty)
│   └── cv/
│       └── Abdulazeem_Ayomide_Data_Scientist_CV.pdf
└── README.md
```

## Deploying to GitHub Pages

1. Create a new repository named exactly `gleeboi.github.io` (must match your GitHub username).
2. Upload every file in this folder, **keeping the folder structure intact** (drag the whole `portfolio` folder contents in, or use `git add . && git commit -m "portfolio" && git push`).
3. Go to **Settings → Pages** in the repo, confirm the source is the `main` branch, root folder.
4. Wait 1–2 minutes, then visit `https://gleeboi.github.io`.

## Adding content later

- **CV**: replace `assets/cv/Abdulazeem_Ayomide_Data_Scientist_CV.pdf` with an updated file of the same name (the download button already points to this path).
- **Project images**: drop images into `assets/images/` and reference them with `<img src="assets/images/yourfile.jpg">` inside a `.project-card` in `index.html`.
- **New projects**: duplicate a `.project-card` block in the Projects section and edit the text, tags, and links.
- **New certifications**: duplicate a `.cert-card` block in the Certifications section; add a `<a class="btn btn-ghost">View Credential</a>` link if you have a URL.
- **GitHub repo links / live demos**: add `<a class="btn btn-ghost">` buttons inside `.project-links` for each project.

## Notes

- All content is sourced directly from the CV and capstone project documentation provided — no experience, metrics, or certifications were invented.
- The capstone project (UrbanNest Hospitality Analytics) was a group project; the portfolio card discloses this rather than presenting it as solo work.
- Animations respect `prefers-reduced-motion`.
