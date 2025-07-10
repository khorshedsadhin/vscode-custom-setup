# My Visual Studio Code Setup

This repository contains my personal `settings.json` file for Visual Studio Code. This configuration is tailored for a fast, efficient, and keyboard-driven development workflow, with a strong emphasis on Vim keybindings and a clean, minimalist interface.

## Philosophy

The goal of this setup is to create a development environment that minimizes distractions and maximizes productivity. Key principles include:

-   **Keyboard First:** Heavily reliant on Vim for navigation and editing to keep hands on the keyboard.
-   **Minimalist UI:** Hiding unnecessary UI elements like the minimap and indentation guides to focus on the code.
-   **Automation:** Leveraging auto-save, format on save, and smart file handling to streamline common tasks.
-   **Consistency:** Ensuring a consistent experience across different languages and projects with standardized formatting and tools.

---

## Key Features

### 1. Editor & Font
-   **Font:** Uses **Fira Code** with font ligatures enabled for a more readable and aesthetically pleasing coding experience.
-   **Relative Line Numbers:** Essential for efficient movement with Vim commands (`10j`, `5k`, etc.).
-   **Clean UI:** The minimap and indentation guides are disabled to reduce visual clutter.
-   **Smart Suggestions:** `suggest.insertMode` is set to `replace` for a smoother autocompletion flow.

### 2. Workbench & Window
-   **Layout:** The sidebar is moved to the **right** and the activity bar to the **top** for a less intrusive layout.
-   **No Previews:** Files open directly without using the preview mode, preventing accidental tab closures.
-   **Streamlined Explorer:** Confirmation dialogs for deleting or moving files are disabled for faster file management.

### 3. Vim Keybindings
This setup is heavily customized for Vim users.
-   **Leader Key:** `<Space>` is set as the leader key for quick access to custom commands.
-   **Navigation:**
    -   Switch between buffers (tabs) with `Shift + H` and `Shift + L`.
    -   Navigate between split panes with `leader + h/j/k/l`.
    -   Create vertical and horizontal splits with `leader + v` and `leader + s`.
-   **File Management:**
    -   Quickly save, quit, or save-and-quit with `leader + w`, `leader + q`, and `leader + x`.
    -   Focus the file explorer with `leader + n + e`.
-   **Visual Mode:**
    -   Indent/outdent lines with `<` and `>` without leaving visual mode.
    -   Move selected lines up and down with `J` and `K`.
    -   Toggle comments on a selection with `leader + c`.

### 4. Terminal
-   **Font:** Uses **JetBrains Mono** for clarity.
-   **Default Profile:** Set to Command Prompt on Windows.
-   **Java Path:** The `JAVA_HOME` environment variable is configured directly within the terminal profile for seamless Java development.

### 5. Git Integration
-   **Autofetch:** Automatically fetches from remotes to keep your local repository up-to-date.
-   **Smart Commit:** Enables staging all changes when committing with no staged changes.
-   **No Confirm Sync:** Skips the confirmation dialog when syncing (pulling/pushing) changes.

---

## Installation

To use this configuration, follow these steps:

1.  **Install Recommended Extensions:** For the best experience, make sure you have the following VS Code extensions installed:
    -   `vscodevim.vim` - The core Vim emulation.
    -   `esbenp.prettier-vscode` - For code formatting.
    -   `PKief.material-icon-theme` - For file icons.
    -   `beardedbear.beardedtheme` - The "Bearded Theme Monokai Black" theme.
    -   A code runner extension if you use the `code-runner.executorMap`.

2.  **Open VS Code Settings:**
    -   Press `Ctrl + Shift + P` (or `Cmd + Shift + P` on macOS) to open the Command Palette.
    -   Type `Preferences: Open User Settings (JSON)` and press Enter.

3.  **Copy and Paste:**
    -   Copy the entire content of the `settings.json` file from this repository.
    -   Paste it into your `settings.json` file, replacing the existing content.

4.  **Restart VS Code:**
    -   Save the file and restart Visual Studio Code for all settings to take effect.

---
