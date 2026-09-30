# Jayas 360 Edits

A working space for Insta360 video projects, content planning, captions, thumbnails, presets, and lightweight automation.

## Recommended workflow

- Edit original 360 and exported video on the desktop in Insta360 Studio, DaVinci Resolve, Premiere, or CapCut.
- Store original camera files and finished high-resolution exports in Google Drive or OneDrive.
- Use this repository for project notes, shot lists, captions, thumbnails, presets, scripts, and small proxy assets.
- Keep credentials in a local `.env` file. Copy `.env.example` to `.env`; never commit `.env`.
- Use Codespaces for planning, scripts, and automation. It is not the primary location for editing full-resolution footage.

## Repository layout

```text
projects/       Project briefs, timelines, and edit notes
shot-lists/     Camera plans and selected timecodes
captions/       Captions, hooks, titles, and descriptions
thumbnails/     Thumbnail concepts and small preview assets
presets/        Export, color, audio, and caption presets
scripts/        Optional organization and content helpers
exports/        Lightweight previews only; keep masters in cloud storage
```

## Getting started

1. Install Git and your preferred desktop video editor.
2. Install Insta360 Studio for camera-specific reframing and exports.
3. Copy `.env.example` to `.env` and fill only the services you actually use.
4. Keep original footage outside this repository.
5. Open the repository locally for desktop work, or select **Code → Create codespace on main** for planning and scripts.

## Collaboration

Add collaborators from GitHub repository settings only when they need access. Give reviewers read access when possible and contributors write access when they will modify project files. Do not use this repository as a substitute for a shared raw-footage library.

## Media policy

Do not commit camera originals, full-resolution masters, cache folders, credentials, or private client footage. GitHub blocks regular files over 100 MiB, and Git LFS should be used only after deciding who needs the files and where the authoritative media library lives.

