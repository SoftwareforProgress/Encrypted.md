# 🔐 Encrypted.md

**Encrypted.md** is a minimalist, local-first Markdown note-taking app with end-to-end encryption by default. Built with [Go](https://golang.org) and [Wails](https://wails.io), it helps developers, educators, organizers, and advocates keep their sensitive notes secure — without sacrificing usability.

This project is maintained by the [Software for Progress Foundation](https://softwareforprogress.org), a nonprofit dedicated to advancing Open Source software for accessibility, education, and security.

---

## ✨ Features

- **Encrypted-by-default**: Notes are never stored in plaintext
- **Single passphrase unlock**: All notes stay encrypted at rest
- **No database**: Your folder structure is preserved on disk
- **In-memory decryption**: Notes are only decrypted when viewed
- **Markdown-native**: Edit using plain `.md` syntax
- **Exportable**: Export any note to `.md` when needed
- **Offline & local-first**: Nothing syncs to the cloud

---

## 🛠️ Tech Stack

- **Go** – Secure backend, AES encryption, file I/O
- **Wails** – Cross-platform desktop app framework (Go + Web)
- **Svelte** – Flexible frontend UI

---

## 📦 Coming Soon

- Syntax highlighting and dark/light theming
- Auto-lock after inactivity
