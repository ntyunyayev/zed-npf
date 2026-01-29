# zed-npf

A [Zed editor](https://zed.dev) extension providing syntax highlighting for [NPF (Network Protocol Framework)](https://github.com/tbarbette/npf) configuration files.

## Installation

This extension is not yet available in the Zed extension registry. To install it manually:

1. Clone this repository:
   ```bash
   git clone https://github.com/ntyunyayev/zed-npf.git
   ```

2. Open Zed and go to **Extensions** (`Cmd+Shift+X` / `Ctrl+Shift+X`)

3. Click **Install Dev Extension** and select the cloned `zed-npf` folder

## Usage

Once installed, Zed will automatically apply syntax highlighting to files with the `.npf` extension.

## Features

- Syntax highlighting for all NPF section types (`%script`, `%config`, `%variables`, etc.)
- Support for tags, roles, and parameters
- Embedded language highlighting (Bash scripts, Python code)
- Jinja template injection support

## Issues

Please report issues in the [main tree-sitter-npf repository](https://github.com/ntyunyayev/tree-sitter-npf/issues).
