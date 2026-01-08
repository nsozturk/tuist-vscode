# Tuist

Swift App development right from VSCode or VSCode-based editors

## Features

Describe specific features of your extension including screenshots of your extension in action. Image paths are relative to this README file.

For example if there is an image subfolder under your extension project workspace:

\![feature X](images/feature-x.png)

> Tip: Many popular extensions utilize animations. This is an excellent way to show off your extension! We recommend short, focused animations that are easy to follow.

## Requirements

If you have any requirements or dependencies, add a section describing those and how to install and configure them.

## Extension Settings

Include if your extension adds any VS Code settings through the `contributes.configuration` extension point.

For example:

This extension contributes the following settings:

- `myExtension.enable`: Enable/disable this extension.
- `myExtension.thing`: Set to `blah` to do something.

## Building VSIX Package

### Prerequisites

- Node.js and npm installed
- Project dependencies installed (`npm install`)

### Build Steps

1. **Install dependencies** (if not already done):

   ```bash
   npm install
   ```

2. **Create VSIX package**:

   ```bash
   npx @vscode/vsce package
   ```

   This will generate a `tuist-0.0.1.vsix` file in the project root.

### Installing the VSIX

#### Option 1: Install via VS Code UI

1. Open VS Code
2. Go to Extensions panel (⌘+Shift+X or Ctrl+Shift+X)
3. Click the `...` menu in the top-right
4. Select **"Install from VSIX..."**
5. Choose the generated `tuist-0.0.1.vsix` file

#### Option 2: Install via Command Line

```bash
code --install-extension tuist-0.0.1.vsix
```

## Known Issues

Calling out known issues can help limit users opening duplicate issues against your extension.

## Release Notes

Users appreciate release notes as you update your extension.

### 1.0.0

Initial release of ...

### 1.0.1

Fixed issue #.

### 1.1.0

Added features X, Y, and Z.

---

**Enjoy!**
