# work-plan-notation
Syntax highlight for wpn (Work Plan Notation) for Sublime Text.

## Installation

### MacOS

#### Sublime Text 3+

From the repository folder, run:
```bash
cp wpn.sublime-syntax ~/Library/Application Support/Sublime Text 3/Packages/User
```

#### VS Code

From the repository folder, run:
```bash
cp -R syntaxes ~/.vscode/extensions/local.wpn-language-support-0.0.1
cp language-configuration.json ~/.vscode/extensions/local.wpn-language-support-0.0.1
cp package.json ~/.vscode/extensions/local.wpn-language-support-0.0.1
```
Then run Developer: Reload Window from VS Code’s Command Palette and open a .wpn file to check it works.
