<p align="center">
  <img src="logo.png" alt="Deluge Editor Logo" width="128" height="128" />
</p>

# Deluge Editor

<p align="center">
  <strong>A dedicated desktop wrapper for the Zoho Deluge Tryout environment.</strong>
</p>

<p align="center">
  <a href="#features">Features</a> •
  <a href="#download--install">Download</a> •
  <a href="#developer-guide">Developer Guide</a> •
  <a href="#license">License</a>
</p>

---

## Features

- 🚀 **Dedicated Workspace**: Runs Zoho Deluge in a standalone window, separate from your browser tabs.
- 🪟 **Native Experience**: Improved window management and taskbar integration.
- ⚡ **Lightweight**: Built with Electron for performance.

## Download & Install

**No prerequisites needed!**

1.  Go to the **[Releases](https://github.com/Hackb07/deluge-editor-win11/releases)** page.
2.  Download the latest `.exe` installer (e.g., `Deluge Editor Setup 1.0.0.exe`).
3.  Run the installer to set up the application.

---

## Developer Guide

If you want to build the application yourself or contribute, follow the steps below.

### Prerequisites (For Developers)

- [Node.js](https://nodejs.org/) (v14 or higher recommended)
- [npm](https://www.npmjs.com/) (usually comes with Node.js)

### Installation

1.  Clone the repository:
    ```bash
    git clone https://github.com/Hackb07/deluge-editor-win11.git
    cd deluge-editor-win11
    ```
2.  Install dependencies:
    ```bash
    npm install
    ```

### Usage

To start the application in development mode:

```bash
npm start
```

### Build

To create a distributable installer for Windows:

```bash
npm run dist
```

The output installer will be in the `dist` folder.

## Technologies Used

- [Electron](https://www.electronjs.org/)
- [Electron Builder](https://www.electron.build/)



