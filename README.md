# Achyut Tripathi — React Portfolio

A responsive React + Vite portfolio based on the supplied peach/ivory editorial reference design.

## Run locally

1. Install Node.js 18+.
2. In this folder run `npm install`.
3. Run `npm run dev` and open the local URL shown by Vite.
4. Run `npm run build` to create the production site in `dist/`.

## Personal details and assets

- Main content is in `src/main.jsx` (navigation, experience, projects, education, skills and certificates).
- Visual styles are in `src/styles.css`.
- Replace `public/assets/images/achyut-profile.jpg` to update the portrait.
- Certificate PDFs and previews are in `public/assets/certificates/`.
- Resume is in `public/assets/Achyut-Tripathi-Resume.pdf`.

## Before publishing

- Replace generic LinkedIn and GitHub links with your actual profile URLs.
- Add verified project repository/live URLs and screenshots when ready.
- The contact form uses a `mailto:` action; it does not require a backend but opens the visitor's email application.
- Confirm the MBA start year and update it in `src/main.jsx` if needed.

## Deploy

Deploy the project to Vercel, Netlify, or any static hosting provider. For Vercel, import the folder/repository and use the default Vite build command `npm run build` with output directory `dist`.
