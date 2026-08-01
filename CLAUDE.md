# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Repository purpose

This is `buech-dev/buech-dev` — a GitHub **profile README repository**. On GitHub, a repo named identically to the account owner is special-cased: the content of its `README.md` is rendered on the owner's public profile page (github.com/buech-dev). There is no application code, build tooling, package manifest, or test suite here — the repository's only meaningful artifact is `README.md` itself.

## Structure

- `README.md` — the entire content of the repo. Written primarily in German. It's a self-introduction (Christopher Büchner) covering current projects, tech stack, and embedded GitHub stats widgets (github-readme-stats.vercel.app, komarev.com profile-view counter).

## Working in this repository

- There is nothing to build, lint, or test. Changes are purely edits to `README.md` (or adding new static assets such as images if requested).
- Preserve the existing German-language voice and tone; don't switch content to English unless asked.
- The `<img>`/badge links (vectorlogo.zone, devicon, github-readme-stats, komarev) are live third-party services keyed to the `buech-dev` GitHub username — keep the username consistent if these are edited.
- Since this renders directly on a public GitHub profile, treat Markdown/HTML changes as user-facing: verify formatting (headings, tables, embedded HTML `<p>`/`<img>` blocks) stays valid GitHub-flavored Markdown before committing.
