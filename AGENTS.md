# Repository Guidelines

## Project Structure

This repository is a Slidev presentation for the 2026 software-engineering course. `slides.md` is the deck entrypoint and contains the global front matter plus the four lesson imports. Edit lesson content in `pages/01-se-with-llm.md` through `pages/04-references.md`; keep reusable images in `assets/`. `style.css` contains deck-wide CSS overrides. `README.md`, `package.json`, and `pnpm-lock.yaml` describe setup and dependencies. Generated output belongs in ignored `dist/` or `.slidev/` directories and should not be committed.

## Change Feedback

After making changes, do not run checks or perform visual inspection; the user keeps the deck rendering live and will provide feedback. Respond to that feedback as quickly as possible.

## Style and Naming

Use Markdown with Slidev front matter and `---` slide separators. Preserve the existing Chinese/English teaching style, concise headings, and `[待补]` markers for unfinished material. Name lesson files with two-digit numeric prefixes and descriptive kebab-case names, such as `pages/03-agentic-coding.md`. Use two-space indentation in CSS and inline HTML, meaningful image `alt` text, and `object-fit: contain` when sizing screenshots so their aspect ratios are preserved.

## Content and Assets

Edit authoritative Markdown and CSS sources rather than generated files. Prefer the existing files under `assets/`; add new assets only with clear names and appropriate licensing. Do not place API keys, personal data, or other secrets in slides, notes, or committed assets.

## Commits and Pull Requests

This checkout has no existing commits, so no repository-specific history convention is established. Use short imperative Conventional Commit-style subjects, for example `docs: add agent workflow slide`. Pull requests should explain the affected lesson(s), list validation commands and results, link any relevant issue, and include screenshots or an export preview when layout or visuals change.
