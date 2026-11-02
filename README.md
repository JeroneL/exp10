# Online Resume / CV — Jerone L

A responsive, single-page online resume and portfolio built with HTML, CSS, and vanilla JavaScript. It is ready to deploy to Vercel as a static site.

## Run locally on your Mac

1. Unzip the downloaded project.
2. Open the `online-resume-cv` folder in VS Code.
3. Open `index.html` in a browser, or use the VS Code Live Server extension.
4. No npm install or build command is required.

## Before publishing

Open `index.html` and update:
- `your.email@example.com` to your real email address.
- The LinkedIn and GitHub links to your own profiles.
- Project descriptions, skills, dates, and internship details to match your final CV.
- Any skill bar percentages to reflect your actual proficiency.

The website currently uses the name and project details provided in the draft. Check all facts carefully before sharing it with recruiters.

## Deploy to Vercel (recommended: GitHub import)

1. Create or sign in to a GitHub account.
2. Create a new repository, for example `online-resume-cv`.
3. Upload the contents of this folder to the repository. Make sure `index.html`, `style.css`, `script.js`, and `vercel.json` are in the repository root, not inside another nested folder.
4. Sign in to https://vercel.com using GitHub.
5. Click **Add New → Project**, then import your `online-resume-cv` repository.
6. In project settings, use these values:
   - Framework Preset: **Other**
   - Root Directory: `./`
   - Build Command: leave blank
   - Output Directory: leave blank (or `.` if Vercel asks for a value)
   - Install Command: leave blank
7. Click **Deploy**. Vercel will give you a public URL such as `your-project.vercel.app`.
8. Every future push to the connected GitHub repository will trigger a new deployment.

## Alternative: Vercel CLI

Install Node.js first, then run these commands in Terminal from this folder:

```bash
npm install -g vercel
vercel
```

Follow the prompts. To publish a production deployment, run:

```bash
vercel --prod
```

## CV download / print

Click **Download / Print CV** on the page. In the print dialog, choose **Save as PDF**. The stylesheet includes a print layout. For a polished recruiter-ready PDF, confirm your personal contact details and review the print preview first.

## Project files

- `index.html` — page structure and content
- `style.css` — responsive design, visuals, and print layout
- `script.js` — mobile navigation, print action, and current year
- `vercel.json` — static-site URL configuration
