SNORTTI PERSONAL PORTFOLIO
==========================

FILES
-----
index.html  - Website structure and written content.
style.css   - Colors, layout, responsive design, and animations.
script.js   - Mobile navigation, scroll reveals, copy-email button, and footer year.
assets/images/james-snortti-satiah.jpg - Optimized high-resolution portfolio portrait.
assets/images/james-snortti-satiah-avatar.jpg - Cropped, responsive portrait for branding.
assets/images/favicon.png - Portrait-derived website icon.

OPEN ON WINDOWS 11
------------------
1. Extract this ZIP file.
2. Open Visual Studio Code.
3. Click File > Open Folder.
4. Select the extracted "snortti-portfolio" folder.
5. Open index.html.
6. If you have the Live Server extension:
   - Right-click index.html
   - Select "Open with Live Server"
   If you do not have Live Server, open the folder in File Explorer and double-click index.html.
   The website will open in your browser. Google Fonts requires an internet connection.

PERSONALIZE BEFORE PUBLISHING
-----------------------------
1. Search in index.html for "Snortti" and adjust the display name if you prefer another version.
2. Check the About section and university wording for accuracy.
3. Check the project descriptions against what you actually built.
4. Add your GitHub and LinkedIn URLs once ready. Do not invent or publish placeholder URLs.
5. The contact email currently uses supportreachio@gmail.com as the contact address. Change it if you want a separate personal email.
6. Add a downloadable CV only after placing your final PDF in the project folder and linking it from the page.
7. Add real project demo/source-code links only when they are publicly accessible.

GITHUB PAGES DEPLOYMENT (NO BUILD REQUIRED)
-------------------------------------------
This is a static website. It needs no Node.js server, database, package install, or build step.

1. Create a GitHub repository. For a user site, name it YOUR-GITHUB-USERNAME.github.io.
   Alternatively, use any repository name for a project site.
2. Upload the contents of this project folder to the repository root. Ensure index.html,
   style.css, script.js, and the assets/ folder are at the same root level; do not upload
   only a parent folder that nests these files one level deeper.
3. Push or commit the files to the main branch.
4. In GitHub, open the repository's Settings > Pages.
5. Under Build and deployment, choose "Deploy from a branch", select main and /(root),
   then save. GitHub Pages serves the root index.html directly without a build command.
6. Wait for the Pages deployment to finish and open the URL GitHub provides. User sites
   use https://YOUR-GITHUB-USERNAME.github.io/; project sites use
   https://YOUR-GITHUB-USERNAME.github.io/REPOSITORY-NAME/.

All local stylesheet, script, and portrait references are relative paths, so they work
for both user and project sites. Google Fonts is an optional external font service; the
CSS includes fallback fonts if it cannot be reached.

SEO URL METADATA
----------------
The Open Graph title and description are set. No canonical or absolute Open Graph URL/image
is hard-coded because the final public domain and repository URL have not been confirmed.
After the site is published, add a canonical link and absolute og:url/og:image values using
the exact public URL; this is especially important when using a project-site URL.

IMPORTANT
---------
- This is a static portfolio, so it does not require a database or backend server.
- The contact button opens the visitor's email app; it is not a server-powered contact form.
- Do not publish private details, passwords, tokens, or confidential project configuration.
- Before publishing, proofread all personal details and only claim skills/experience you can discuss honestly.
