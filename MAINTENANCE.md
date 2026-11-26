# Maintaining the portfolio

Edit [index.html](index.html) for site content and layout. The `work`, `research`, `experience`, and `contact` section IDs match the links in the header. Keep the IDs and header links in sync if you rename a section.

## Add a project

1. In the `work` section, copy a `<article class="project">` inside the `projects` grid. Add `project-wide` when the entry should span the full grid.
2. Fill in the title, project context, and a short description of what the project does. Credit the team and describe individual contributions when they can be verified.
3. Link to the canonical repository. Add a demo link if the demo is publicly accessible. Keep the link text specific to the destination.

For publications, check author order, venue, and results against the publisher or conference page. Link directly to the paper or abstract.

## Check a change

- Open the local preview using the command in the [README](README.md).
- Check the project grid on desktop and at a narrow mobile width.
- Tab through the header and project links. Confirm the section links land on their headings and links have visible focus.
- Open each changed external link and review dates, roles, and award names.
- Review the diff before committing. The embedded portrait data is long, so avoid reformatting that line during unrelated edits.
- Record visitor-facing changes in the [changelog](CHANGELOG.md).
