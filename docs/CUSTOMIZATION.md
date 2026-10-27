# Customize the profile

Before publishing, make the profile specific to you while keeping every claim verifiable.

## 1. Set the GitHub username

Replace every `YOUR_GITHUB_USERNAME` in `README.md` with the exact account username. The repository that publishes a profile README must have that exact name. Search the whole README after replacement to confirm none remain.

## 2. Personal links

Replace `YOUR_LINKEDIN_URL`, `YOUR_WEBSITE_URL`, and `YOUR_PUBLIC_EMAIL` only with public destinations you control. Delete any line you do not want to publish. Email is visible to everyone viewing the profile.

## 3. Biography and focus

Adjust the “About me”, “What I’m curious about”, and “Current exploration” copy to match your present interests and voice. Exploration language is intentional: change it to completed-work language only when the work is real and you can point to it.

## 4. Technologies

The current list is explicitly labeled “Technologies I’m exploring”; it is not a verified skill inventory. Remove items you are not exploring, add tools you actually use, and avoid implying mastery unless your experience supports that description.

## 5. Projects

The expandable project entry is a template, not a real project. Replace `PROJECT_NAME`, `YOUR_REPOSITORY_URL`, and `VERIFIED_TECHNOLOGY` with a real repository, accurate one-sentence description, technologies you used, and a truthful status (`EXPERIMENT`, `IN PROGRESS`, or `MAINTAINED`)—or remove the entire template until you have a verified project to feature. Add a demo or screenshot only if it is real and publicly accessible.

## 6. Colors and artwork

The image palette is defined in `assets/banner.svg` and `assets/footer.svg`. Update their color values together to preserve the visual system. The README body has no custom CSS: GitHub controls its page theme, so use semantic Markdown rather than relying on text color styling. See [`../assets/README.md`](../assets/README.md) for SVG editing and fallback notes.

## 7. Optional statistics

This README intentionally has no third-party analytics images, hardcoded metrics, or external service dependency. If you add live statistics later, use your exact username, descriptive alt text, and a reputable endpoint; treat the widget as optional and keep the rest of the profile complete when the service is unavailable. Never put an access token or secret in a public README URL.

## 8. Final checks

Search for `YOUR_`, `PROJECT_NAME`, `VERIFIED_TECHNOLOGY`, and placeholder labels before publishing. Confirm links and claims are yours, preview the rendered Markdown in GitHub, and check a narrow/mobile viewport. Use [`PUBLISHING.md`](PUBLISHING.md) for the publishing steps.
