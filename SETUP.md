# Setup — Gaurav Sharma Engineering Profile

## 1. Use the correct repository

Create or open the **public** repository named exactly `Gauravsharmadevops` under the account `Gauravsharmadevops`. GitHub only treats a repository as the profile README when the repository name matches the username.

## 2. Upload files without changing their paths

Upload these files/folders to the repository root:

- `README.md`
- `assets/engineering-profile.svg`
- `.github/workflows/snake.yml`

Commit the changes. The single integrated SVG is intentional: it makes the profile read as one connected design instead of a stack of unrelated panels.

## 3. Enable the contribution animation

Open **Settings → Actions → General** and ensure actions are allowed. The workflow needs `Contents: Read and write` permission (set in the YAML). Then open **Actions → Generate contribution snake → Run workflow**. The first run publishes the animation to the `output` branch. The README uses that generated file. If the workflow has not completed yet, the snake image will not appear immediately.

## 4. Personalize before publishing

- Edit `assets/engineering-profile.svg` to change the SVG's visible copy. Keep the SVG tags/IDs intact unless you know the impact.
- Add a real LinkedIn or portfolio URL only when you are ready to share it; no invented contact links are included.
- Project cards are labelled **planned builds** on purpose. Update the content after you have actually completed and pushed those projects.
- The README says beginner/foundations explicitly; update your capability labels as your hands-on experience grows.

## Notes

GitHub profile READMEs support Markdown and images/GIFs. The main design is an SVG with subtle SVG-native animation, rather than JavaScript/CSS, which a README cannot run. Browser and GitHub rendering can differ slightly. Contribution-snake generation is provided by the open-source `Platane/snk` GitHub Action.
