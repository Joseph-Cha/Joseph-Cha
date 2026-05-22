# Implementation Plan - Modern GitHub Profile Overhaul

This plan details the redesign and beautification of Joseph Cha's GitHub Profile README, incorporating premium aesthetics, badges, stats widgets, and a clean categorisation of projects (including game development, mobile/Flutter, full-stack web, and Christian-oriented applications).

## User Review Required

Documenting key sections for design review:
- **Badge and Widget Style**: We will use consistent dark/modern themes (`dracula` or `github_dark`) for all stats, streaks, and trophies widgets.
- **Categorization of Projects**: The projects are logically grouped into:
  1. ✝️ Christian & Community Projects
  2. 🎮 Game Development & Architecture
  3. 🌐 Web & Platform Projects
  4. 🧠 System Programming & Algorithms
- **"Developer" Terminal Block**: We will use a Neofetch-style terminal block representing the developer with a custom game controller ASCII art, replacing the C# MonoBehavior block.

## Open Questions
- **Theme Preference**: Do you prefer the `dracula` theme (purple/dark) or `github_dark` / `transparent` theme for stats widgets? (Defaulting to `dracula` for vibrant modern look similar to `utilForever`).
- **Additional Links**: Are there other social links (e.g. blog, Twitter/X) you'd like to add to the connect section?

## Proposed Changes

### GitHub Profile README

#### [MODIFY] [README.md](file:///Users/joseph.c/Work/Samples/tools/Joseph-Cha/README.md)
Update the README.md with the new design:
- Add a centered introduction with a dynamic header badge/banner.
- Insert the GitHub Trophy widget: `https://github-profile-trophy.vercel.app/?username=Joseph-Cha&theme=dracula&row=2&column=6`.
- Replace the C# Developer class snippet with a Neofetch-style ASCII game controller system info block.
- Update the **Tech Stack** section with sorted, styled, and aligned shields.
- Group and list the featured public and private repositories (highlighted appropriately) with star badges.
- Re-align **GitHub Statistics** using the Dracula theme with a side-by-side layout.
- Update the **Let's Connect** section using modern, flat-square styled social badges.

## Verification Plan

### Manual Verification
- Review the markdown layout on local VS Code / Markdown preview.
- Run a Git status to ensure changes are tracked correctly.
- Commit the changes using the commit guidelines defined in `CLAUDE.md`.
