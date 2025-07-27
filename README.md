# 🧮 Calculator Project – Zig (Shared)

👥 Shared with ALI CS Club

---

This is the **shared Zig calculator repository** for ALI CS Club members.  
It includes both:

- `cli/` – A terminal-based calculator written in idiomatic Zig.  
- `gui/` – A graphical calculator built using a Zig GUI library like `zgt` or `zgui`.

Each version is in its own folder and compiled using `zig build`.

---

## 📁 Project Structure

```
calculator-zig-shared/
├── cli/
│   └── calculator.zig         # CLI version – compiled & run with zig
└── gui/
    └── calculator_gui.zig     # GUI version – built with a Zig GUI library
```

---

## 🚀 How to Run

### CLI Version

```bash
cd cli
zig run calculator.zig
```

### GUI Version

> ⚠️ Requires a Zig-compatible GUI library like `zgt` or `zgui`  
> You may need to initialize a build.zig file depending on the GUI framework used.

```bash
cd gui
zig build run
```

---

## 🤝 Contribution Guidelines

- If you're working **independently**, please **fork** this repo or create a **branch**, and submit a **pull request** when your work is ready to merge.
- If you're working **together with a club member** (e.g., in a meeting), only **one person should edit and push at a time** to avoid conflicts.
- Keep code clean, idiomatic, and well-documented. Follow Zig conventions and place files in the correct folder (`cli/` or `gui/`).

---

## 🧠 Purpose

This project helps members learn and experiment with:

- Manual memory management and strong type safety in Zig (CLI version)
- GUI development using lightweight Zig libraries (GUI version)
- Modern low-level systems programming and GitHub collaboration

Happy hacking in Zig! ⚡
