# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Zweck des Repositories

Dies ist `buech-dev/buech-dev` — ein GitHub-**Profil-README-Repository**. Repositories, die exakt wie der Benutzername ihres Besitzers heißen, werden von GitHub speziell behandelt: Die `README.md` im Root-Verzeichnis wird direkt auf der öffentlichen Profilseite des Besitzers angezeigt (github.com/buech-dev).

Es gibt hier keinen Anwendungscode, kein Build-System, kein Package-Manifest und keine Testsuite. Das gesamte Repository besteht aus einer einzigen Datei, `README.md`, auf Deutsch verfasst, die den Autor (Christopher Büchner) und seinen Tech-Stack beschreibt.

## Arbeiten in diesem Repository

- Die einzige inhaltlich relevante Datei zum Bearbeiten ist `README.md`.
- Es gibt keine Build-, Lint- oder Testbefehle — Änderungen sind reine Markdown/HTML-Edits, die von GitHub gerendert werden.
- Die README bindet externe Badge-/Statistik-Bilder ein (github-readme-stats.vercel.app, komarev.com) sowie Icons von devicon/vectorlogo.zone; diese sind extern verlinkt, nicht im Repository gespeichert.
- Änderungen auf Deutsch verfassen, passend zum bestehenden Ton und emoji-reichen Stil, sofern nicht anders gewünscht.
- Da diese Seite öffentlich sichtbar ist, jede inhaltliche Änderung als für alle Besucher des GitHub-Profils sichtbar behandeln.

## Agent skills

### Issue tracker

Issues werden als GitHub Issues in `buech-dev/buech-dev` getrackt (über die `gh`-CLI). Siehe `docs/agents/issue-tracker.md`.

### Triage labels

Standard-Label-Vokabular: `needs-triage`, `needs-info`, `ready-for-agent`, `ready-for-human`, `wontfix`. Siehe `docs/agents/triage-labels.md`.

### Domain docs

Single-context-Layout (`CONTEXT.md` + `docs/adr/` im Repo-Root, werden bei Bedarf angelegt). Siehe `docs/agents/domain.md`.
