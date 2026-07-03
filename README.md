# MD:// Viewer

A fully offline, client-side Markdown & mini-repo renderer. Open the HTML file (or visit the hosted link below) and drop in a `.md` file or a `.zip` — everything renders instantly, right in your browser. Nothing is ever uploaded anywhere.

**Live site:** https://giriaryan694-a11y.github.io/MD-Viewer/

---

## What it does

- Renders `.md` / `.markdown` files with full formatting: headings, tables, task lists, blockquotes, code blocks with syntax highlighting.
- Displays embedded images, SVGs, and videos referenced inside the markdown.
- Renders ` ```mermaid ` code blocks as live diagrams (flowcharts, sequence diagrams, state diagrams, etc.).
- Unzips a `.zip` in-browser and shows it as a browsable file tree — click through folders and files like a lightweight repo viewer, with relative image/video paths resolved correctly.
- Dark, light, and eye-saver (paper) themes, with a responsive layout that works on both desktop and phone screens.
- **Read Aloud (local TTS)** — reads the currently open file out loud using your browser/OS's own built-in voices (e.g. Chrome/Windows voices), with a voice picker and a speed control (0.5×–2×). Fully local — no audio or text is sent anywhere.
  - **Note:** Android browsers don't reliably support local text-to-speech through the web. If you open Read Aloud on Android, you'll get a popup telling you to use the desktop version of a browser (Chrome, Edge, Safari on Windows/Mac/Linux) or try a different browser that supports it.
- **Create / Edit markdown** — write a new `.md` file from scratch or edit the one you currently have open, in a split editor with a live preview and a formatting toolbar (bold, headings, links, images, lists, tables, code blocks, diagram blocks). Download the result as a `.md` file when you're done — nothing is saved or sent anywhere until you choose to download it.

## Why Markdown

Markdown (`.md`) is one of the best formats for sharing notes and research — it's plain text, readable without any special software, version-control friendly, and still supports rich formatting (headings, tables, images, diagrams, checklists). That makes it a great format for writing up findings, documenting a project, or keeping structured personal notes, without being locked into a specific app or proprietary file format.

## When / why to use this

- **Personal notes and private research** — write your notes in Markdown and preview them properly without installing an editor or extension.
- **Reviewing a research write-up or report** — drop the `.md` file (or a `.zip` of a whole notes folder) and read it fully formatted, with any diagrams and images rendered.
- **Sharing findings offline or air-gapped** — since rendering happens entirely client-side, it works well in environments where you don't want files touching a server.
- **Quickly previewing a repository's docs** — zip up a folder (e.g. a project with a `README.md` and an `/assets` or `/docs` folder) and browse it like a mini file explorer, without cloning it anywhere or pushing it online.
- **Checking how a Markdown file will look** before pasting it into GitHub, a wiki, or any other Markdown-based platform.

---

Made By Aryan Giri | giriaryan694-a11y
