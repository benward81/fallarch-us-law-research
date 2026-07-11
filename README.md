# Fallarch v1.0.0 - Sovereign Legal Practice Management 2026

> **Fallarch is a browser-based legal practice management tool for attorney firms, built for offline-first matter tracking, US law research, conflict checks, and a verifiable audit trail in version 1.0.0.**

[![Platform](https://img.shields.io/badge/Platform-browser-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-v1.0.0-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/benward81/fallarch-us-law-research?style=flat-square)](https://github.com/benward81/fallarch-us-law-research)

---

<p align="center">
  <a href="https://benward81.github.io/fallarch-us-law-research/">
    <img src="https://img.shields.io/badge/Download-Fallarch%20Latest-brightgreen?style=for-the-badge" alt="Download Fallarch">
  </a>
</p>

> **[Direct Download - Fallarch v1.0.0](https://benward81.github.io/fallarch-us-law-research/)**

---

[Download Latest Build](https://benward81.github.io/fallarch-us-law-research/)

---

## Overview

Fallarch gives legal teams a self-contained workspace for managing matters without a server-based backend. Since it ships as a single HTML browser app and stores its main data locally, it suits firms that value offline access and a straightforward deployment path.

The application combines case organization, legal research, and accountability tooling in one interface. It includes client and matter management, timeline and fee tracking, document handling, and advice workflows, along with conflict detection, signed advice records, and an exportable change log for review.

---

## Core Capabilities

- Single-file browser app with no server requirement
- Offline-first interface with responsive layout and PWA support
- Client, matter, timeline, fee, document, and advice tabs for practice management
- US law research corpus with practice-area statutes
- Conflict checking across local data and broadcast mesh
- Hashed audit chain for tracking state changes
- Exportable JSON history for reviewing updates and records
- Advice signing with sha256, adviser ID, and timestamp
- IndexedDB primary storage with localStorage fallback for persistence

---

## Installation

1. Download or clone the repository to your local machine.
2. Open the main HTML file in a modern browser, or host it as a static site if you prefer a shared deployment.
3. If you are using the published build, open the latest download link and launch it directly in the browser.

For local development:
1. Clone the repo.
2. Open the project folder.
3. Launch the HTML file in your browser.

---

## How to Use Fallarch

Begin by creating a client record, then add matters and keep the related timeline, fees, documents, and advice notes organized inside the app.

Typical workflow:
1. Open Fallarch in your browser.
2. Create or load a local workspace.
3. Add client and matter details.
4. Use the research area to review US law references and practice-area statutes.
5. Run conflict checks against stored data.
6. Sign advice entries when a reviewed note should be recorded.
7. Export JSON state changes when you need a portable history.

---

## Configuration

Fallarch is set up mainly through local browser storage instead of a centralized server.

Storage behavior:
- IndexedDB is used first for local persistence
- localStorage is used as a fallback when needed
- App data remains inside the browser environment unless you export it

If you host the app as a static file, no extra backend configuration is required.

---

## Requirements

- A modern browser with JavaScript support
- IndexedDB support for primary local storage
- localStorage support as a fallback
- Enough local storage space for your matters, documents, and history exports
- Optional static hosting if you want to publish the app as a browser-accessible build

---

## FAQ

**How do I get updates?**  
Use the latest published build from the download link and replace your local copy when a new version is released.

**Where is my data stored?**  
Data stays in the browser using IndexedDB first, with localStorage as a fallback.

**Can I use it without a network connection?**  
Yes. The app is built for offline browser use.

**How do I change settings?**  
Settings and app state are handled locally in the browser. Check the app interface and your browser storage if you need to review or reset data.

**What should I do if the app does not load correctly?**  
Try a modern browser, clear the site data for the app, and reopen the HTML file or static build.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
