# Install the redesigned profile

1. Open https://github.com/Mah-Noor11/Mah-Noor11 (the profile repository).
2. Download the ZIP and extract it.
3. Copy `README.md` and the full `assets/` folder to the root of that repository. **Keep the original non-SVG assets** (especially `assets/Mah-Noor-Academic-CV.pdf`) when replacing the folder. This package does not include the existing CV PDF.
4. Commit the files to the default branch, normally `main`.
5. Visit https://github.com/Mah-Noor11 to see the new profile.

## Important

- The animated name, roles, decorative orbit, connection icons and footer are SVG assets. They are built to work as embedded images in GitHub README Markdown. Some viewers or reduced-motion settings may show a still frame.
- Project links and social links are clickable. SVG hover popups and embedded JavaScript are not supported by GitHub README.
- The header and footer do not require a third-party service. Technology badges use shields.io and the streak card uses github-readme-streak-stats, so those elements require network availability.
- The existing Academic CV PDF must remain in assets/ for its link to work.
- If you want to customize roles, change the four strings in `assets/roles.svg`; change the display name in `assets/hero.svg` (you may need to increase the SVG clipping width for longer names).
- For production, preview on desktop and mobile and check accessibility with motion reduction enabled.
