<img width="468" height="448" alt="image" src="https://github.com/user-attachments/assets/5e582054-355b-4183-81f3-495c725f9ef6" /># ⚡ QuickNoteAC

> **Fast • Lightweight • Simple • Private**

**QuickNoteAC** is a lightweight and fast desktop note-taking application for **Windows**.
It is designed for quick writing, text editing, searching, and easy access to your notes without unnecessary complexity.

[**Fa version**](https://github.com/ali-cheshomi/QuickNoteAC/blob/main/README-FA.md)
---

## ✨ Features

* 📝 **Text Editor**

  * Bold / Italic / Underline / Strikethrough
  * Change text size and color
  * Text highlighting
  * Left, center, and right alignment
  * RTL / LTR support
  * Persian and English text support

* 🔍 **Fast Search**

  * Quickly search within your notes
  * Persian, English, and Unicode support
  * Multiple search results
  * Next / Previous result navigation
  * Automatic scrolling to the selected result
  * `Ctrl + F` shortcut

* 💾 **Auto Save**

  * Automatically save changes
  * Manual save
  * Automatically load notes on startup
  * Local data storage

* ☑️ **Checkboxes**

  * Create checkboxes for paragraphs
  * Toggle checkbox state with a double-click
  * Automatically strike through completed items

* 🖥️ **Mini Mode**

  * Small and compact window
  * Designed to stay accessible alongside other applications
  * Quickly switch back to Full Mode

* 🔒 **Blur Mode**

  * Blur note content
  * Prevent accidental editing
  * Automatically close the Search Box when enabled

* 📌 **Always on Top**

  * Keep QuickNoteAC above other windows

* 📋 **Clipboard & Editing**

  * Copy / Cut / Paste
  * Undo / Redo
  * Select All

* 📊 **Word & Character Counter**

  * Word count
  * Character count
  * Whitespace characters are excluded from the character count

* 🖥️ **System Tray**

  * Access QuickNote from the system tray
  * Restore the application
  * Control Taskbar visibility
  * Exit the application

---

## 🌍 Language Support

QuickNoteAC is designed to work with both Persian and English text.

* 🇮🇷 Persian
* 🇬🇧 English
* Mixed Persian and English text
* RTL / LTR
* Unicode

---

## ⌨️ Keyboard Shortcuts

| Shortcut   | Action              |
| ---------- | ------------------- |
| `Ctrl + F` | Open / Close Search |
| `Enter`    | Perform Search      |
| `Ctrl + C` | Copy                |
| `Ctrl + X` | Cut                 |
| `Ctrl + V` | Paste               |
| `Ctrl + Z` | Undo                |
| `Ctrl + Y` | Redo                |

---

## 📦 File Formats

| Format | Description                                |
| ------ | ------------------------------------------ |
| `.acn` | QuickNoteAC's native file format             |
| `.txt` | Plain text export                          |
| `*.*`  | Support for selecting different file types |

QuickNoteAC also supports **Save As**, allowing you to create a separate copy of your note.

---

## ⚙️ Requirements

QuickNoteAC is available in two versions:

### .NET 8

The **.NET 8 Desktop Runtime** is required to run the .NET 8 version of QuickNoteAC.

[Download .NET 8 Desktop Runtime — Microsoft](https://dotnet.microsoft.com/en-us/download/dotnet/8.0)

### .NET 10

The **.NET 10 Desktop Runtime** is required to run the .NET 10 version of QuickNoteAC.

[Download .NET 10 Desktop Runtime — Microsoft](https://dotnet.microsoft.com/en-us/download/dotnet/10.0)

> **Note:** If the required .NET Desktop Runtime is not installed, QuickNoteAC may not start.

---

## 🔥 Getting Started

1. Download the latest release from **Releases**.
2. Extract the downloaded ZIP file.
3. Choose the desired version.
4. Install the required .NET Desktop Runtime if necessary.
5. Run `QuickNoteAC.exe`.
6. Start taking notes. ✍️

> Your saved note will be automatically loaded when QuickNoteAC starts.

---

## 🚀 Start QuickNoteAC with Windows

QuickNoteAC can be configured to **start automatically when Windows starts**.

This feature is **optional**. If you want QuickNoteAC to launch automatically, you can place a shortcut to `QuickNoteAC.exe` in the Windows Startup folder.

### 📁 Default Startup Folder

To open the Startup folder, press `Win + R` and enter:

```text
shell:startup
```

The default Startup folder path is:

```text
%APPDATA%\Microsoft\Windows\Start Menu\Programs\Startup
```

### ➕ Add QuickNoteAC to Startup

To launch QuickNoteAC automatically when you sign in to Windows:

1. Locate `QuickNoteAC.exe`.
2. Right-click it and select **Create shortcut**.
3. Copy or move the created shortcut to the Startup folder.
4. Restart Windows or sign out and sign back in to verify that QuickNoteAC starts automatically.

> **Note:** Adding QuickNote to Startup is completely optional. You can continue to launch the application manually if preferred.

---

## 💾 Data Storage

QuickNoteAC stores your notes **locally on your computer** and does not require an internet connection for normal use.

No user account or online service is required.

---

## 🖼️ Screenshots

> Screenshots will be added here.

* [Main Window](images/QuickNoteACScreenshot1.png)
* [Search](images/QuickNoteACScreenshot1.png)

---

## 🐛 Bug Reports

If you encounter a problem, please create an **Issue** and include the following information:

* Windows Version
* QuickNoteAC Version
* Steps to Reproduce
* Expected Behavior
* Actual Behavior
* Screenshot / Screen Recording

---

## 💡 Feature Requests

Have an idea that could make QuickNoteAC better?

Feel free to create a **Feature Request** and describe:

* What feature would you like to see?
* Why would it be useful?
* How should it work?
* Is there a similar feature in another application?

---

## 🗺️ Roadmap

Some features that may be introduced in future versions:

* 🎨 More text formatting options
* 🌓 More themes
* ⚙️ Settings panel
* ⌨️ Additional keyboard shortcuts
* 🔍 Improved search
* 📂 Better file management
* 📄 More export formats
* 🎨 UI improvements
* ⚡ Performance improvements

> The roadmap may change during development.

---

## 🔐 Privacy

QuickNoteAC is primarily a **local desktop application**.

Your notes are stored on your computer, and normal use does not require an online account or cloud service.

---

## 🔒 License

**QuickNote is Proprietary / Closed Source.**

Copyright © 2026 **MRACco / MRAC / MR_AC / Ali Chechomi**

All rights reserved.

The source code, binaries, branding, design, and related assets are proprietary and may not be copied, modified, redistributed, repackaged, reverse engineered, or used commercially without prior written permission from the copyright holder.

> This repository is intended for software releases, documentation, bug reports, and feature requests.

---

## ❤️ About

QuickNoteAC was built with one simple goal:

> **Write fast. Stay focused. Keep your notes always within reach.**

Built with ❤️ by **MRAC**

---

<div align="center">

### ⚡ QuickNoteAC

**Fast • Lightweight • Simple • Private**

Copyright © 2026 MRACco / MRAC / MR_AC / Ali Chechomi

**All rights reserved.**

</div>
