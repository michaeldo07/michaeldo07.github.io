# GitHub Pages deployment

This repository publishes [michaeldo07.github.io](https://michaeldo07.github.io/) from the root of `main`. In **Settings → Pages**, the source is **Deploy from a branch**, with branch **main** and folder **/ (root)**. GitHub Pages serves `index.html` as the home page.

## Publish and verify

1. Preview the changes locally and commit them to `main` once reviewed.
2. In the repository’s [Actions tab](https://github.com/michaeldo07/michaeldo07.github.io/actions), look for **pages build and deployment**. Open the run for the relevant commit and check that deployment succeeded.
3. Open the [live site](https://michaeldo07.github.io/) and check the affected section. If deployment succeeded but the page looks stale, try a hard refresh or a private window.

## Recover a previous version

If a change breaks the live site, revert the specific commit that introduced it and let GitHub Pages deploy the revert. Use GitHub’s revert workflow if available or run `git revert <commit-sha>` locally and push the revert to `main` after reviewing it. Check the resulting deployment and live page.

If deployment fails, check the Actions run for the reported error and verify that `index.html` is still at the root of the publishing branch.

[GitHub Pages publishing source documentation](https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site)
