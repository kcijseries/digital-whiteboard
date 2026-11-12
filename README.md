# Typing Blackboard (Offline)

A lightweight, offline-first browser blackboard for large-display typing, text highlighting, and formatted A4 printing. Built with vanilla HTML, CSS, and JavaScript with zero external network dependencies.

## Features
* **Large-Scale Display Typography:** Smooth font scaling from `24px` to `320px` with instant toggling between **Lexend** and **Letter Gothic (`LETTGOTH`)**.
* **Color & Highlighting:** 16-color text swatches (with live contrast preview) and 16 translucent highlight swatches for emphasizing key words or phrases.
* **Dark & Light Modes:** One-click switch between a high-contrast black chalkboard theme and a bright whiteboard theme.
* **Offline Persistence & File I/O:** Automatically saves progress to `localStorage`, and supports opening and saving plain `.txt` files.
* **Custom Print Layout:** Built-in print dialog with configurable font size (`10pt`–`40pt`) and A4 page margins.

## Getting Started
1. Download the `.7z` archive from this repository (or **Releases**) and extract all files into a single folder.
2. Double-click `index.html` to open it in any modern web browser—no internet connection or server required.

## Included Files
* `index.html` — Complete self-contained application (UI, styles, and logic).
* `Lexend-VariableFont_wght.ttf` & `LETTG__.TTF` — Bundled fonts for offline rendering.
