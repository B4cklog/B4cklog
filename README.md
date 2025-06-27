# B4cklog

Monorepo for B4cklog — a personal game backlog management system with Android client, Spring Boot backend, and React + TypeScript web interface.

## Documentation

- Main documentation: [B4cklog-Docs](https://github.com/B4cklog/B4cklog-Docs)
- Each submodule has its own README for quick start and specifics.

## Project Structure

- `client/` — Android application (Kotlin)
- `server/` — Backend REST API (Spring Boot, Kotlin)
- `web/` — Web frontend (React, TypeScript)
- `docs/` — Main documentation vault (Obsidian-ready, Markdown)

## Getting Started

### Prerequisites

- Git
- Java 21+ (for Spring Boot server)
- Android Studio (for Android client)
- Node.js and npm/yarn (for web client)

### Cloning the repository

To clone the repository including all submodules (`client`, `server`, `web`), run:

```bash
git clone --recurse-submodules https://github.com/B4cklog/B4cklog.git
```

### Working with Submodules

Each submodule is a separate git repository and can be opened/used independently. See their respective README files for details.
