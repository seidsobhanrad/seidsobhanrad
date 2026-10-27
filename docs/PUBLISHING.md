# Publish the GitHub profile README

The GitHub profile README appears when a repository is public, has a `README.md` at its root, and is named exactly after the account username.

## Create the profile repository

1. Sign in to GitHub using the account that should own the profile.
2. Create a new repository. Name it exactly your GitHub username (not your display name), for example `YOUR_GITHUB_USERNAME` only if that is literally your account name.
3. Set the repository to **Public** and initialize it with a README only if you are creating the files directly on GitHub. If GitHub offers a profile-README prompt for the matching repository, follow it.
4. Before publishing from this workspace, replace all personal placeholders using [`CUSTOMIZATION.md`](CUSTOMIZATION.md). Do not publish the sample project entry as if it were real.

## Add the files

Choose one of these approaches:

- **GitHub website:** In the matching repository, use **Add file → Upload files** to add `README.md`, the `assets/` SVGs and `assets/README.md`, and `docs/`. Commit the changes to the default branch.
- **Git locally:** From a local clone of the matching repository, copy these profile files into its root, inspect `git status` and `git diff`, then commit and push using your normal GitHub workflow.

Do not overwrite unrelated files in an existing repository. This folder is now a local Git repository with the profile files staged, but it has no remote configured yet, so nothing has been pushed.

## Verify publication

Open `https://github.com/YOUR_GITHUB_USERNAME` after replacing the placeholder with your actual username. Confirm the profile README appears, local images load, links lead to the intended public pages, and the content is readable at a narrow/mobile width. If the profile README does not appear, check that the repository is public, its name exactly matches the username, and `README.md` is at its root on the repository's default branch.
