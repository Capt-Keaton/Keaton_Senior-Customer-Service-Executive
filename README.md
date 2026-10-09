# Keaton Clarke | Senior Customer Service Executive Portfolio

A five-page personal portfolio website for **Sylvester Keaton Clarke**, a contact centre Team Leader and Senior Customer Service Executive based in Accra, Ghana. It is built to be shared with recruiters and hiring managers.

**Live site:** `https://<your-github-username>.github.io/<repository-name>/`
(Replace the placeholders with your GitHub username and repository name once GitHub Pages is switched on.)

> *"Live Full...Die Empty"*

---

## What is on the site

| Page | Desk | What it shows |
| --- | --- | --- |
| 1. Home | Desk 1 · Reception | Introduction, Service Pass card, headline results, overview and favourite quote |
| 2. Experience | Desk 2 · Service log | Full role-by-role history, key escalation cases, plus separate Education and Languages sections |
| 3. Skills & Wins | Desk 3 · Control room | Three team members promoted into managerial roles, skills, results, support console and certifications |
| 4. How I Work | Desk 4 · Floor manual | "How I run a floor": six operating principles |
| 5. Contact | Desk 5 · Front desk | Two emails, two phone numbers (both on WhatsApp), LinkedIn, location and a resume download |

## Features

- Five pages in one file, with Next and Back navigation and a scrolling results ticker
- Light and dark theme toggle (remembers the visitor's choice, and follows their device setting by default)
- Refined indigo-to-teal gradient design with Playfair Display and Inter fonts
- Icons on every contact detail (email, call, WhatsApp, LinkedIn, location, download)
- Resume PDF embedded in the page, so the download button works without any extra file
- Responsive layout for phones, tablets and desktops
- No frameworks, no build step and no installs. It works on GitHub Pages as soon as the files are uploaded
- Tab icon, theme colour and link-preview details for sharing on WhatsApp and LinkedIn
- Tested: all five pages open and switch without errors

## Files in this repository

```
index.html                  The entire website (HTML, CSS and JavaScript in one file)
README.md                   This file
Keaton_Clarke_Resume.pdf    Standalone copy of the ATS resume (optional, the site also embeds it)
.nojekyll                   Tells GitHub Pages to serve the files exactly as they are
```

## Publish it on GitHub Pages

1. Sign in to GitHub and create a **new public repository** (for example `keaton-portfolio`).
2. Click **Add file → Upload files**. Drag in the **files themselves** (`index.html`, `README.md`, `Keaton_Clarke_Resume.pdf` and `.nojekyll`), not a zip file, then **Commit changes**. `index.html` must sit at the top level of the repository, not inside a folder.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, set **Source** to **Deploy from a branch**, choose the **main** branch and the **/ (root)** folder, then **Save**.
5. Wait one to two minutes. GitHub shows your live link at the top of the Pages screen:
   `https://<your-github-username>.github.io/<repository-name>/`
6. Share that link with recruiters, and add it to your LinkedIn profile and resume.

Tip: name the repository `<your-github-username>.github.io` to get a shorter address with no repository name at the end.

## Updating the site

- **Text and results:** open `index.html` on GitHub, click the pencil icon, edit the wording and commit. The live site refreshes within a minute or two.
- **Colours:** change the values at the top of the `<style>` block (`--a`, `--b`, `--c`, `--d` and `--g`).
- **Photos:** the headset illustration on the Home page is a drawing. To use a real photo, add the image file to the repository and replace the `<svg class="il" ...>` block with an `<img src="your-photo.jpg" alt="Keaton Clarke at work">` tag.
- **Resume:** the PDF is stored inside `index.html`. To change it, ask for the page to be rebuilt with the new resume, or replace the long text value in the `RES` variable near the bottom of the file with a new base64 version of your PDF.

## Contact

- Email: keatonclarke37@gmail.com | clarkekeaton75@gmail.com
- Phone and WhatsApp (both numbers active on WhatsApp): +233 204148130 | +233 594949743
- LinkedIn: https://www.linkedin.com/in/keaton-c-535616161
- Location: Accra, Ghana

---

© 2026 Sylvester Keaton Clarke. All rights reserved.
