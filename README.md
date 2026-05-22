# 🦇 Cave Web Solution · Ultimate VS Code Setup

A complete, zero‑bloat VS Code configuration for modern web development.
Hand‑crafted by the **Cave Web Solution** team, tested daily on real projects.

## ✨ What’s Inside
- ⚡ **Performance‑tuned settings** → startup under 3 seconds
- 🎨 **Cave Dark Pro** – a custom, eye‑comfort theme
- 🔤 **JetBrains Mono** – the best coding font (with ligatures)
- 🧩 **38 curated extensions** – only the ones you actually need
- ⌨️ **40+ productivity shortcuts** – organised by category
- ✂️ **Snippets** for HTML, CSS, JavaScript & React
- 🏢 **Multi‑root workspace** template

---

## 🚀 Quick Start (5 minutes)

### 1. Install the font
Download [JetBrains Mono](https://www.jetbrains.com/lp/mono/) and install it.
On macOS double‑click the `.ttf` files; on Windows right‑click → Install.

### 2. Copy the settings
- Open VS Code, press `Ctrl+Shift+P` and search **“Preferences: Open User Settings (JSON)”**.
- Replace the content with our `settings.json`.
- Restart VS Code.

### 3. Install the extensions
- Open the file `extensions.json` from this repository.
- In VS Code, press `Ctrl+Shift+P` → **“Extensions: Install from VSIX”** is not needed; instead, you can run a script (see below) or install them manually.
- **Manual method:** Search for each extension ID in the Extensions view and install.

### 4. Apply the Cave Dark Pro theme
- Copy `cave-dark-pro-theme.json` to your VS Code extensions folder:
  - **Windows:** `%USERPROFILE%\.vscode\extensions\cave-dark-pro-theme\`
  - **macOS/Linux:** `~/.vscode/extensions/cave-dark-pro-theme/`
  - Create the folder if needed, then paste the file inside and restart VS Code.
- Then go to `Ctrl+K Ctrl+T` and select **Cave Dark Pro**.

### 5. Import the keybindings (optional)
- Press `Ctrl+Shift+P` → **“Preferences: Open Keyboard Shortcuts (JSON)”**
- Append the contents of `keybindings.json`.

### 6. Add the snippets
- Press `Ctrl+Shift+P` → **“Preferences: Configure User Snippets”** → choose a language.
- Copy the corresponding snippet file content.

---

## ⚙️ Performance Tweaks

- **Disable unused extensions** – Right‑click any extension → Disable.
- **Use a workspace** – Open the `cave-web.code-workspace` file to enable project‑specific settings.
- **Increase memory limit** – In `settings.json`, `files.maxMemoryForLargeFilesMB` is set to 4096 (4GB).
- **Exclude heavy folders** – `node_modules`, `dist`, `.git` are already excluded from the watcher.

---

## 💡 Top 5 Tips for Beginners
1. **Command Palette is king:** `Ctrl+Shift+P` lets you do *anything* without the mouse.
2. **Emmet magic:** type `ul>li*5` then press `Tab` to expand instantly.
3. **Multi‑cursor:** Hold `Alt` and click anywhere, or `Ctrl+D` to select the next occurrence.
4. **Rename symbol:** `F2` renames a variable/function across the whole project.
5. **Zen Mode:** `Ctrl+K Z` for distraction‑free coding.

*Full tip collection available on our Wiki.*

---

## 🤝 Contributing
Pull requests welcome. This setup is maintained by Cave Web Solution.
