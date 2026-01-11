# i3 Window Manager Configuration

Personal **i3wm** configuration focused on simplicity, keyboard-driven workflow, and minimal setup.

This configuration uses **Alt (Mod1)** as the main modifier and keeps all logic **inline inside the i3 config file** (no external scripts).

---

## ✨ Features

- Keyboard-centric tiling workflow
- Inline screenshot commands (clipboard or file)
- Screen brightness control via `brightnessctl`
- Volume and microphone control via `pactl`
- Clipboard manager with CopyQ
- Simple resize mode
- Minimal i3bar using i3status

---

## ⌨ Keybindings (Highlights)

| Keybinding               | Action                        |
| ------------------------ | ----------------------------- |
| `Alt + Enter`            | Open terminal                 |
| `Alt + d`                | App launcher (dmenu)          |
| `Alt + Shift + q`        | Close window                  |
| `Alt + h`                | Horizontal split              |
| `Alt + f`                | Toggle fullscreen             |
| `Alt + r`                | Resize mode                   |
| `Alt + v`                | Toggle CopyQ                  |
| `Alt + Shift + s`        | Screenshot → clipboard        |
| `Alt + Shift + Ctrl + s` | Screenshot → file + clipboard |
| `XF86Audio*`             | Volume / mute                 |
| `XF86MonBrightness*`     | Screen brightness             |

---

## 📁 Repository Structure

```text
i3-config/
├── config
├── .gitignore
└── README.md
```
