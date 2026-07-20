# Changelog

All notable public changes to AI Coding OS are documented here.

## 3.0.1 — 2026-07-20

- Fix `install.sh` failure caused by a leftover `skills/ai-builder-os` folder
  that was never renamed during the AI Builder OS → AI Coding OS rename,
  breaking fresh installs. See #1.

## 3.0.0 — 2026-06-24

- Install the free framework and five basic skills globally for selected Agents.
- Support Claude Code, Codex, GitHub Copilot, Cursor, and Qoder.
- Add separate framework-dependent installation for paid skill packs.
- Keep project memory, domain knowledge, outputs, and thin adapters project-local.
- Standardize skills on uppercase `SKILL.md` entry files.
- Provide zero-dependency Bash and PowerShell installers.
- Replace legacy onboarding with concise bilingual READMEs and v3 User Guides.
