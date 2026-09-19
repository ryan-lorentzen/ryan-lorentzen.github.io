# Ryan Lorentzen — portfolio website

A restrained, mobile-friendly personal website built with plain HTML and CSS. No npm install, build step, paid plan, or backend required.

## Preview locally

Open `index.html` in your browser. You can also serve the folder using `python -m http.server 8000` and visit http://localhost:8000.

## IMPORTANT: Customize before publishing

1. **Add your internship.** Open `index.html`, find `INTERNSHIP`, remove the HTML comment around the sample `timeline-item`, and replace employer, dates, and duties with your *actual* information. Put it above EconoMap in the Experience section. No employer or results have been guessed.
2. **Update your résumé.** Replace `resume.pdf` with the newer PDF containing your internship. The included file is your current résumé; it has not yet been updated with that internship. It also contains your phone number, which becomes publicly accessible if you publish the site as-is. Decide whether you want that on a public website.
3. **Add direct project URLs.** The EconoMap and AI Classroom Copilot cards currently link to your general GitHub profile rather than guessing project repository URLs. Replace each relevant `href="https://github.com/ryan-lorentzen"` with the exact project URL once confirmed. Add demo URLs or screenshots if you have them.
4. **Review your information.** Make sure education, GPA, dates, project status, email, and profile links are current, and confirm the project descriptions reflect your personal contributions. The illustrative project visuals are design mockups, **not screenshots of real software**.
5. **Optional:** Edit the hero headline and introduction to match the type of SWE roles you are targeting. Edit the look and layout in `styles.css`.

## Free hosting: GitHub Pages

1. On GitHub, create a **public** repository named `ryan-lorentzen.github.io` (provided `ryan-lorentzen` is your actual GitHub username).
2. Upload everything **inside** this folder to the repository root so `index.html`, `styles.css`, `favicon.svg`, and `resume.pdf` are at the root. You can upload through GitHub's Add file → Upload files interface and commit, or use Git locally.
3. Go to **Settings → Pages**. Under **Build and deployment**, choose **Deploy from a branch**, then select `main`, `/(root)`, and **Save**.
4. Once deployed, open `https://ryan-lorentzen.github.io/`. GitHub notes that publication can take up to around 10 minutes.
5. For updates, edit the files and push/commit again. The site will redeploy.

Free-account GitHub Pages publishing uses a public repository. Do not commit private information or confidential employer code. The site is public even when a paid account allows a private source repository.

Official guide: https://docs.github.com/en/pages/quickstart

## Structure

- `index.html` — all website content
- `styles.css` — colors, design, layout, and mobile styles
- `favicon.svg` — site icon
- `resume.pdf` — current résumé, replace before final publication

## Design

The updated edition keeps the restrained layout and no decorative motion, adds understated teal and blue accents, and removes the entire hero code window and availability banner. The latest CSS overrides are grouped under `COLOR REFINEMENT` at the end of `styles.css`.
