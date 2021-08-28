# NEOX's VS Code theme

## Install

1. Go to [VS Marketplace](https://marketplace.visualstudio.com/items?itemName=GitHub.github-vscode-theme).
2. Click on the "Install" button.
3. Then [select a theme](https://code.visualstudio.com/docs/getstarted/themes#_selecting-the-color-theme). Currently the following themes are available:
   - `Neox`

## Override this theme

To quickly test something, you can also override this (or any other) theme in your personal config file. Please follow the guide in the [color theme](https://code.visualstudio.com/api/extension-guides/color-theme) documentation.

## Contribute

1. Clone and open this [repo](https://github.com/Irere123/Neox-Theme) in VS Code
2. Press `F5` to open a new window with your extension loaded
3. Open `Code > Preferences > Color Theme` [`⌘k ⌘t`] and pick the "Neox" theme
4. Make changes to the [`/themes/NEOX-color-theme.json`](https://github.com/Irere123/Neox-Theme/blob/master/themes/NEOX-color-theme.json) file.
   - **UI**: For all changes to the "outer UI", like (status bar, file navigation etc.), take a look at the [Theme Color](https://code.visualstudio.com/api/references/theme-color) reference.
   - **Syntax**: For changes to the "code highlighting", examine the syntax scopes by invoking the [`Developer: Inspect Editor Tokens and Scopes`](https://code.visualstudio.com/api/language-extensions/syntax-highlight-guide#scope-inspector) command from the Command Palette (`Ctrl+Shift+P` or `Cmd+Shift+P` on Mac) in the Extension Development Host window.
5. Commit your changes and open a PR.

Note:

- If possible use colors from [NEOX's color system](https://neoxrw.netlify.com).
- Changes to the theme files are automatically applied to the Extension Development Host window, so no reloading should be necessary.

## Publish (internal)

> Note: Publishing a new version of this theme is only meant for maintainers.
