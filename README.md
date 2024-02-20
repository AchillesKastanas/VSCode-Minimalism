# VSCode-Minimalism

A minimal CSS file to customize your VSCode. *Used with Custom CSS and JS extension*

![Minimal VSCode](https://github.com/AchillesKastanas/VSCode-Minimalism/assets/47496934/d7026602-9fa2-4401-ab88-ffae1ebd6f3d)

## Steps

1. Download [Vibrancy Continued] from the VSCode Extension Store.

2. Use these extension settings for Vibrancy Continued (For the theme I'm using GitHub's Default Dark):

    ![Extension Settings](https://github.com/AchillesKastanas/VSCode-Minimalism/assets/47496934/8fca15f3-fd3d-48c2-8b91-e360dc431aab)

3. In the `settings.json` of your VSCode, enter these configurations for a minimal VSCode. Edit them whenever needed:

    ```json
    "window.menuBarVisibility": "compact",
    "workbench.editor.showTabs": "single",
    "editor.minimap.enabled": false,
    "workbench.statusBar.visible": false,
    "workbench.startupEditor": "none",
    "window.commandCenter": false,
    "editor.smoothScrolling": true,
    "workbench.list.smoothScrolling": true,
    "explorer.confirmDelete": false,
    "window.titleBarStyle": "custom",
    "update.mode": "manual",
    "workbench.colorTheme": "GitHub Dark Default",
    "vscode_vibrancy.opacity": 0,
    "diffEditor.ignoreTrimWhitespace": false,
    "godot_tools.gdscript_lsp_server_port": 6005,
    "workbench.layoutControl.enabled": false,
    "editor.accessibilitySupport": "off",
    "editor.fontLigatures": true,
    "window.zoomLevel": 1,
    "editor.glyphMargin": false,
    "workbench.activityBar.location": "hidden"
    ```

4. Install [Custom CSS and JS Loader] from the VSCode Extension Store.

5. Create a new CSS file somewhere, and enter the path in your `settings.json` like this:

    ```json
    "vscode_custom_css.imports": [
        "file:///Users/achilles.kastanas/Documents/vscode.css"
    ]
    ```

    - **Windows File URL Example:** `file:///C:/Users/MyUserName/Documents/custom.css` (*The `C:/` part is REQUIRED.*)
    - **MacOS and Linux File URL Example:** `file:///Users/MyUserName/Documents/custom.css`

6. Inside your custom CSS file, place the CSS file in the repo.

7. Enjoy :) Don't forget to leave a ⭐
