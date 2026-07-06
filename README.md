# Taskdash

A local-first task dashboard + agent OS. Runs entirely on your machine — your data never leaves your computer.

## Install (macOS)

    curl -fsSL https://github.com/taskdashapp/taskdash/releases/latest/download/install.sh | bash

This downloads the latest release, verifies its checksum, installs Taskdash to your
Applications folder, and launches it.

> Taskdash is currently distributed unsigned, so the installer clears the macOS
> quarantine flag for you (that's why it's a command-line install rather than a
> double-click .dmg). It installs at the user level so Taskdash can auto-update later.

## Updating

Taskdash checks for updates on its own and installs them automatically.

## What it is

- Tasks, todos, notes, journal, habits, canvas — one dashboard, minimal buttons.
- Local-first — a small server runs on 127.0.0.1; nothing is sent to any remote server.
- Agent OS — a scriptable kernel (paths, actions, events, state, plugins).

## License

Business Source License 1.1 — free for personal, educational, and evaluation use;
commercial use requires a license. Converts to Apache 2.0 on 2030-04-13. See LICENSE.
