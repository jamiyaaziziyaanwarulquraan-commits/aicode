# AICode

A small, free browser-based code editor inspired by the familiar layout of desktop code editors. It uses the open-source [Monaco Editor](https://github.com/microsoft/monaco-editor) for code editing and syntax highlighting.

## Use it

Open `index.html` in a modern browser. An internet connection is needed to load Monaco Editor and the icon/font assets. If Monaco cannot load, a plain text editor is provided as a fallback.

## Features

- Explorer, open-file tabs, syntax highlighting, and a starter HTML/CSS/JavaScript project
- Create files, open local text files, download the active file, and preview `index.html`
- Automatic saving to browser local storage; use **Ctrl+S** to save immediately
- Command palette with **Ctrl+Shift+P**

Files are stored locally in the browser and are not uploaded to a server. This is a lightweight starter app, not a full desktop IDE: it does not include extensions, a compiler, or access to the computer's filesystem beyond files you choose to open.
