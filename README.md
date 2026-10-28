# Pasta’s portfolio

A static portfolio for my Minecraft Bedrock addons, scripts, and visual packs. Built with HTML, CSS, and a small inline script. No build step required.

## Preview locally

```sh
python3 -m http.server 8000
```

Open http://localhost:8000. GitHub Pages publishes the site when changes merge into `main`.

## Update the content

Project entries live in `index.html`. Each `.project-card` has a category (`visual`, `system`, or `horror`), artwork from `assets/`, a description, and a CurseForge link. Keep artwork square so the full image stays visible.

The Discord username lives in the contact dialog. Update the displayed handle and `discordUsername` together if the handle changes. Colors, type, spacing, and responsive layouts live in `styles.css`.

The frontend-design and no-ai-slop skills are installed in `.agents/skills/`; their sources are recorded in `skills-lock.json`.
