# Welcome to KAWAII Icons

## What's in the folder

- This folder contains all of the files necessary for your icon theme extension.
- `package.json` - this is the manifest file that defines the location of the theme file and specifies the base theme of the theme.
- `fileicons/kawaii-icons-theme.json` - the icon theme definition file.

## Get up and running straight away

- Press `F5` to open a new window with your extension loaded.
- Open `File > Preferences > File Icon Themes` and pick your icon theme.
- Open a file that has a language associated. The languages' configured grammar will tokenize the text and assign 'scopes' to the tokens. To examine these scopes, invoke the `Developer: Inspect Editor Tokens and Scopes` command from the Command Palette (`Ctrl+Shift+P` or `Cmd+Shift+P` on Mac).

## Make changes

- Changes to the theme file are automatically applied to the Extension Development Host window.

## Adopt your theme to Visual Studio Code

- If the language is supported, a cute language logo will be displayed.

## Install your extension

- To start using your extension with Visual Studio Code copy it into the `<user home>/.vscode/extensions` folder and restart Code.
- To share your extension with the world, read on https://code.visualstudio.com/docs about publishing an extension.
