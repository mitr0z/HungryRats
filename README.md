# HungryRats

**HungryRats** is an experimental desktop browser built around a simple idea:

> A browser should be customizable, transparent about privacy, and useful without forcing everything into the cloud.

HungryRats is currently in active development for **Windows** and is built with **Electron / Chromium**.

---

## ✨ Main Features

- Custom **black / purple UI**
- Custom themes and wallpapers
- HungryRats Search
- Local AI integration with **Ollama**
- AI sidebar for:
  - page summaries
  - explanations
  - selected text
  - translations
  - questions about the current page
- HungryRats Shield
  - ad blocking
  - tracker blocking
  - per-site exceptions
- Cookie Protection
  - third-party cookie protection
  - site exceptions
  - clear cookies/site data
- Privacy Dashboard
- Advanced tabs
  - pin tabs
  - duplicate tabs
  - mute / unmute
  - tab search
  - tab groups
  - reopen closed tabs
- i18n / multiple languages
- Reduced Motion support

---

## 🛡️ Privacy Philosophy

HungryRats aims to stay **local-first** whenever possible.

The goal is not to make exaggerated claims like:

- "100% anonymous"
- "untraceable"
- "perfect privacy"

Instead, HungryRats tries to clearly show what each protection actually does.

Current privacy-focused features include:

- ad and tracker blocking
- third-party cookie protection
- local settings and exceptions
- local AI support through Ollama
- Privacy Dashboard
- no HungryRats account required

Some features are still being improved and may require local configuration.

---

## 🤖 Local AI

HungryRats can use **Ollama** as a local AI backend.

Current development setup:

```text
Ollama:
http://localhost:11434

Model:
llama3.2:3b
```

HungryRats AI can be used to:

- summarize a page
- explain a page
- extract key points
- explain selected text
- translate selected text
- answer questions about the current page

> Ollama is not currently bundled automatically with HungryRats.  
> Public-ready setup and easier dependency installation are planned.

---

## 🔎 HungryRats Search

HungryRats Search uses a custom search interface.

The current development setup can use a local **SearXNG** backend.

```text
SearXNG:
http://localhost:8080
```

This means that the browser UI is included in HungryRats, but some search/AI features may require local services to be configured on the user's computer.

---

## 📥 Download

The current Windows build can be downloaded here:

**[Download HungryRats](https://mega.nz/file/aogXBTQa#g7S0IVtbR6fUc1cyx0vv_ftSGY-a8MyYvAm9U-5Xxhk)**

> HungryRats is still under development.  
> Expect bugs, incomplete features, and changes between builds.

---

## 🚧 Project Status

HungryRats is **not finished yet**.

Current development areas include:

- sleeping tabs
- memory saver
- vertical tabs
- workspaces
- split view
- downloads improvements
- bookmarks
- history
- local profiles
- private mode
- reader mode
- screenshot tools
- Picture-in-Picture
- accessibility improvements
- crash recovery
- update system
- branding / polish
- easier public installation

---

## 🧭 Roadmap

Some of the planned phases include:

```text
Phase 13  Sleeping Tabs
Phase 14  Vertical Tabs
Phase 15  Workspaces
Phase 16  Split View
Phase 17  Settings Reorganization
Phase 18  Custom Shortcuts
Phase 19  Command Palette
Phase 20  Performance
Phase 21  Downloads
Phase 22  Bookmarks
Phase 23  History
Phase 24  Local Profiles
Phase 25  Private Mode
Phase 26  Reader Mode
Phase 27  Screenshot Tool
Phase 28  Picture-in-Picture
Phase 29  Media Controls
Phase 30  Import / Export
Phase 31  Accessibility
Phase 32  Onboarding
Phase 33  Crash Recovery
Phase 34  Updates
Phase 35  Branding / Polish
```

The roadmap may change as HungryRats evolves.

---

## 🧪 Development

HungryRats is based on:

- Electron
- Chromium
- TypeScript
- HTML / CSS / JavaScript
- Ollama
- SearXNG
- Ghostery Adblocker for Electron

Exact dependencies may change during development.

---

## ⚠️ Important

HungryRats is an experimental project.

Do not rely on it yet for:

- critical work
- sensitive professional environments
- guaranteed compatibility with every website
- guaranteed blocking of every ad or tracker

Some websites may behave differently when privacy protections are enabled.

---

## 🎨 Identity

HungryRats uses a **black / purple** visual identity with a focus on:

- clean UI
- smooth animations
- strong customization
- local-first tools
- privacy transparency

### Tagline

> **Hungry for the web.**

---

## 📄 Website

The GitHub Pages website can be built from the repository's:

```text
index.html
```

---

## 🐭 HungryRats

Built as an independent experimental browser project.

**Hungry for the web.**
