# Macro Clicker

A lightweight Windows auto clicker and macro recorder built with Python.

## Features

- **Auto Clicker** - Automate mouse clicks with configurable settings.
- **Macro Recording** - Record actions to create reusable macros.
- **Macro Playback** - Replay recorded macros automatically.
- **Macro Editing** - Edit and customize recorded actions.
- **Image Recognition** - Optional image-based automation.
- **Global Hotkeys** - Control actions using keyboard shortcuts.
- **Settings** - Save application preferences between sessions.

## Getting Started

1. Download or extract the Macro Clicker files.
2. Open `MacroClicker.exe`.
3. Configure the auto clicker or create a macro.
4. Start the automation and stop it when finished.

No Python installation is required to run a properly packaged executable.

## Image Recognition

Image recognition requires the relevant optional dependencies to be included in the build. If image recognition is unavailable, verify that OpenCV, Pillow, and NumPy were installed before packaging the application.

## Settings and Data

Macro Clicker saves its settings and image assets in the current Windows user's application data directory:

`%APPDATA%\MacroClicker`

Settings and assets may not automatically travel with the executable when it is moved to another folder or computer. Back up your macros and any required image files before moving or deleting application data.

## Troubleshooting

**The application won't open**
- Try launching the executable again.
- If it still fails, run a diagnostic build from the terminal to see error messages.
- Check that the application was packaged with its required dependencies.

**The application icon hasn't changed**
- Make sure the EXE was rebuilt using the correct `.ico` file.
- Refresh File Explorer or restart it if the old icon is still cached.

