# Itasca FLAC Language Support for Visual Studio Code

This extension provides **syntax highlighting and basic language support** for [Itasca *FLAC*](https://www.itascacg.com/software/flac) input (`.dat`) files and the inbuilt *FISH* scripting language.

FLAC (Fast Lagrangian Analysis of Continua) is an explicit finite difference program widely used for geotechnical analysis and design.


## Features

- Syntax highlighting for **FLAC** input files (up to *version 7*)
- Recognition of **abbreviated FLAC commands**
- Basic support for **FISH** scripting blocks
- Comment and number highlighting consistent with FLAC syntax

> This extension focuses on *syntax coloring only*. It does *not* include snippets, linting, or code validation.

## Installation

You can install this extension directly from the [Visual Studio Code Marketplace](https://marketplace.visualstudio.com/) or by searching *Itasca FLAC* inside VS Code’s Extensions panel.


## Contributing

Contributions, suggestions, and pull requests are very welcome!  
If you would like to help extend or refine this extension:

1. **Fork** the repository on GitHub:  
   [https://github.com/dkaramitros/vscode-flac](https://github.com/dkaramitros/vscode-flac)

2. **Clone** your fork locally and install dependencies:
   ```bash
   git clone https://github.com/<your-github-username>/vscode-flac.git
   cd vscode-flac
   ```

3. Open the project in **VS Code** and press **F5** to launch a new *Extension Development Host* for testing.

4. Make and test your changes (e.g., improving highlighting rules in `syntaxes/flac.tmLanguage.json`).

5. Submit a **pull request** with a short description of what you changed and why.

If you find an issue, please open it here: [GitHub Issues](https://github.com/dkaramitros/vscode-flac/issues)


## Known Issues

- Not all FLAC commands or FISH functions are yet supported.


## Release Notes

### 0.0.1
- Initial release
- Basic FLAC command and FISH highlighting
- Support for command abbreviations


## Credits

- Icon artwork for this extension created by [ChatGPT](https://chatgpt.com/).


## License

Released under the [MIT License](LICENSE).  
Copyright © 2025 [Dimitris Karamitros](https://github.com/dkaramitros)

**Enjoy working with FLAC in VS Code!**
