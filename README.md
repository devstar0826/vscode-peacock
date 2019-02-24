# vscode-peacock README

A Visual Studio Code extension that subtly changes the workspace color of your workspace. Ideal when you have multiple VS Code instances and you want to quickly identify which is which.

## Install

1. Open **Extensions** sidebar panel in Visual Studio Code. `View → Extensions`
1. Search for `Peacock`
1. Click **Install**
1. Click **Reload**, if required

## Features

Commands can be found in the command palette. Look for commands beginning with `Peacock:`

- Change the titlebar to
  - user defined color
  - a random color
  - the primary color for angular, vue, or react
- Saves colors to your workspace in the `.vscode/settings.json` file
- Sets the foreground to white or black based on the contrast for the background color

## Commands

| Command                       | Description                                                              |
| ----------------------------- | ------------------------------------------------------------------------ |
| Peacock: Reset Colors         | Removes any of the color settings from the `.vscode/setttings.json` file |
| Peacock: Enter a Color        | Prompts you to enter a color using hex and RGB format                    |
| Peacock: Color to Vue Green   | Sets the color to Vue.js's main color, #42b883                           |
| Peacock: Color to Angular Red | Sets the color to Angular's main color, #b52e31                          |
| Peacock: Color to React Blue  | Sets the color to React.js's main color, #00b3e6                         |
| Peacock: Color to Random      | Sets the color to a random color                                         |

![Animated GIF](./resources/peacock.gif)

## Roadmap

There are may features in the roadmap. Please refer to the [issues list and feel free to grab one and contribute](https://github.com/johnpapa/vscode-peacock/issues)!

## Changes

See the [CHANGELOG](CHANGELOG.md) for the latest changes.

## Credits

Inspiration comes in many forms. These folks and teams have contributed either through ideas, issues, pull requests, or guidance. Thank you!

- [@josephrexme](https://twitter.com/josephrexme) for the name and icon for Peacock
- [@codebeast](https://twitter.com/codebeast) for the CLI suggestions
- [@\_clarkio](https://twitter.com/_clarkio) and [@\burkeholland](https://twitter.com/burkeholland) for several issues/ideas
- the VS Code team and their incredibly [helpful guide for creating extensions](https://code.visualstudio.com/api/get-started/your-first-extension?wt.mc_id=devto-blog-jopapa)

![Sketchnote](./resources/peacock-sketchnote.png)
