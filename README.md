# 🪶 Morpankh VS Code Theme

A modern, borderless VS Code dark theme inspired by the vibrant and mesmerizing hues of peacock feathers. Designed with deep midnight backgrounds, emerald teals, sky cyans, morpankh purples, and warm amber accents for a seamless, sleek coding experience.

---

## 🎨 Color Palette

| Accent | Hex Code | Applied Elements |
| :--- | :--- | :--- |
| **Deep Midnight** | `#040404` / `#070e17` | Editor & Workbench Background |
| **Emerald Teal** | `#00f5d4` | Primary Selection, Active Tabs, ENV Keys |
| **Amber Orange** | `#ff842d` | String Values, Intellisense Matching Highlights |
| **Dark Teal** | `#0c2423` | Sidebar Item Active & Hover Backgrounds |
| **Sky Cyan** | `#d0e1f9` | Foreground Text, Terminal Output |

---

## ✨ Features

- **Borderless Aesthetics:** Completely removed harsh grey/white outline borders across menus, inputs, sidebars, and popups (`#00000000`).
- **Tailored .env Highlighting:** Special TextMate scopes mapped for key-value pair readability in configuration files.
- **Custom Settings UI & Widgets:** Integrated dark palette applied to settings panels, autocomplete suggest widgets, and hover tooltips.
- **Integrated Terminal Styling:** Optimized ANSI terminal colors matching the peacock theme palette.

---

## 📸 Preview

![Theme Preview](./screenshots/preview.png)
*(Replace this path with your theme preview image)*

---

## ⚙️ Recommended VS Code Settings

For the best visual experience, add the following to your VS Code `settings.json`:

```json
{
  "window.titleBarStyle": "custom",
  "window.customTitleBarVisibility": "auto",
  "files.associations": {
    ".env*": "properties"
  }
}

```
## Local Installation & Development

## Clone this repository:
git clone [https://github.com/pranitaaeer/morpankh-vscode-theme.git](https://github.com/pranitaaeer/morpankh-vscode-theme.git)

##Copy the theme folder to your VS Code extensions directory:

Windows: %USERPROFILE%\.vscode\extensions

macOS / Linux: ~/.vscode/extensions

Reload VS Code (Ctrl + Shift + P -> Developer: Reload Window).

Go to Preferences: Color Theme and select Morpankh Dark Theme.

## License
This project is licensed under the MIT License.