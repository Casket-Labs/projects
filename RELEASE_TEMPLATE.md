# Adding a project

Casket Labs lists **completed projects with publicly available releases**. This directory is maintained manually; adding a GitHub repository alone does not automatically add it to the catalog.

## 1. Choose a system and category

Open the appropriate file in `platforms/`, then pick one of the existing sections:

- **Games** — original homebrew games.
- **Game Ports** — existing games adapted for the target console.
- **Applications** — standalone software, media tools, and creative applications.
- **Tools and Utilities** — launchers, file managers, maintenance tools, and development utilities.

## 2. Add a simple entry

Replace the *No projects listed yet* text beneath that category with a table (or add another row to an existing table):

```markdown
| Project | Description | Links |
| :--- | :--- | :--- |
| [Project Name](https://github.com/Casket-Labs/REPOSITORY) | One-sentence summary of what the project does. | [Download](https://github.com/Casket-Labs/REPOSITORY/releases) · [Source](https://github.com/Casket-Labs/REPOSITORY) |
```

The project name may link directly to its repository or main website. Link **Download** to a real public download or release page. If the source is not published, omit the Source link; if a separate download is unavailable, don't invent one.

You may use a single link instead of both:

```markdown
| [Project Name](https://example.com/project) | One-sentence summary of the project. | [Project page](https://example.com/project) |
```

Only include a final download or project page that users can actually access.

## 3. Keep the directory easy to browse

- Place each project under one category for its target system.
- Keep entries alphabetized by project title **within their category**.
- Write descriptions in plain language, ideally one sentence.
- Keep details such as credits, changelogs, requirements, and instructions in the project's own repository.
- If a title supports multiple consoles, it may appear on each relevant system page with the appropriate download link.
- Don't add projects that are still in development, privately distributed, or not ready for public use.
- Credit upstream authors on the linked project page when relevant; don't misrepresent third-party work as an original Casket Labs release.

The catalog intentionally doesn't track individual release versions, developers, or update dates. It points visitors to the projects themselves for those details.
