# Release listing template

This file is a **copy-and-paste template** for adding a completed project to the appropriate `platforms/<system>/README.md`.

1. Remove the *No releases have been manually listed...* line when adding the first release.
2. Insert the table headers below once, followed by one row per completed project.
3. Replace all example values with real project data. Do not publish the example row itself.
4. Keep projects alphabetical by title. Use actual release/download URLs.
5. Optionally include an expandable `<details>` section for longer installation or compatibility notes.

## Release table template

```markdown
| Project | Version | Type | Developers | Links |
| :--- | :--- | :--- | :--- | :--- |
| [Project Name](https://github.com/Casket-Labs/PROJECT) | v1.0.0 | Application | [Developer](https://github.com/USERNAME) | [Download](https://github.com/Casket-Labs/PROJECT/releases/tag/v1.0.0) · [Source](https://github.com/Casket-Labs/PROJECT) |
```

## Optional expandable details

Paste under the release table if you want extra information without making the index difficult to scan:

```html
<details>
  <summary><strong>Project Name</strong> — release details</summary>

  **Description:** Short description of what the project does.

  **Platforms:** PS2

  **Developers:** Developer names and links.

  **Installation:** Short summary, with a link to the full instructions.

  **Compatibility / notes:** Hardware requirements, known limitations, etc.

  **Links:** [Release](https://github.com/Casket-Labs/PROJECT/releases/tag/v1.0.0) · [Source](https://github.com/Casket-Labs/PROJECT)
</details>
```

## Listing policy

Include a project only when it has a publicly accessible completed release (or other clearly identified final download). Don't list planned projects, experiments, unreleased work, or another author's project without clarifying the Casket Labs contribution. Link to attribution, license, and upstream material where applicable.

Multiple releases of the same project can either use the latest stable version in a single table row or, when historically important, have separate rows with clearly labeled versions. Avoid dead or unverified links.
