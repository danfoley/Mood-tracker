# Stillwater — Mood Tracker

A private, browser-based dashboard for exploring mood journal entries stored in SQLite.

## Open the app

**[Open Mood Tracker on GitHub Pages](https://danfoley.github.io/Mood-tracker/)**

The link above works once GitHub Pages is enabled for this repository (Settings → Pages → Deploy from a branch → `main` → `/ (root)`).

## Using the app

Select **Connect Google Drive** to open Google’s account picker and grant read-only access. The app automatically searches for `feelings_journal_v3.sqlite` (falling back to earlier versions). No OAuth client ID or Drive file ID needs to be entered. You can also use **Open SQLite file** to load a local copy.

The dashboard shows mood trends, distribution, changes within a day, and searchable journal entries.

## Privacy

This is a public repository containing **application code only**. Do not commit SQLite databases, journal entries, OAuth access tokens, or secrets. Journal data is processed in your browser; the app does not upload it to GitHub.

## Source

The app is implemented in [index.html](./index.html).
