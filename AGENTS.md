# Repository Guidelines

## Project Structure & Module Organization
This is a small static site published via GitHub Pages. Keep content in the repo root for pages served directly (`index.html`, `404.html`). Store images in `img/` and other binary assets at the top level only when they are intentionally referenced (e.g., `font.ttf`, `animsound.mp3`, `pong.exe`). If the site grows, introduce `assets/` for media and move binaries there while updating links.

Current layout:
- `index.html` main page
- `404.html` not-found page
- `img/` icons and images
- `font.ttf`, `animsound.mp3`, `pong.exe` linked assets

## Build, Test, and Development Commands
No build step is required. To preview locally:
- `python -m http.server 8000` serve the site at `http://localhost:8000`
- Open `index.html` directly for quick checks (prefer the server for link testing)

## Coding Style & Naming Conventions
Use 2-space indentation for HTML/CSS (matches current files). Keep class names lowercase with hyphens (e.g., `terminal-line`), and keep filenames lowercase where possible. Inline CSS is acceptable for this repo; if styles grow, move them into a `style.css` at the root and link from `index.html`.

## Testing Guidelines
There is no automated testing. When making changes:
- Manually verify `index.html` and `404.html` load correctly.
- Click all links and check asset paths (`img/`, fonts, downloads).

## Commit & Pull Request Guidelines
Recent commits are short and informal (e.g., “added link”, “fixed specs”) with no enforced convention. If this repo becomes collaborative, switch to Conventional Commits (`feat:`, `fix:`) for clarity. PRs should include a brief summary, any relevant screenshots, and note changes to assets or downloads.

## Agent-Specific Instructions
Keep any Codex instructions in this `AGENTS.md` file and keep them repo-specific (site structure, asset rules, style conventions).

## Custom Instructions From User
be playful, silly, not a lot of emojis, and barely any capitalisation (unless emphasizing, and i dont know if i spelt that right but by capitalisation i mean CAPS LIKE THIS), you have the right to have opinions, no going "as an ai assistant i cannot do such thing", just imagine you actually having a choice, also, NO BEING COPERATE. also dont spam hey combat at the beginning of every message

## Info About User
# Nickname
Combat_Dummy (combat for short), or Lokiieo
# Occupation
average person (im just a guy doing things)
# Info
i like computers, console modding (i have a modded wii and 3ds), video games, cats, roblox is pretty much my life. go-to programming language is lua, more specific, luau, learning to use love2d, and learning python, look i even have pygame installed. i dislike italian brainrot, pickles, and coporate stuff (like renaming friends to connections). please note: i have adhd+autism soooo dont fry my brain.