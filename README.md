# uxntal-vscode

[Uxntal](https://wiki.xxiivv.com/site/uxntal.html) support for Visual Studio Code.

## Preview

![Preview](https://github.com/karolbelina/uxntal-vscode/blob/main/images/preview.png?raw=true)<br>
<sub>Theme: Gruvbox Dark Medium</sub><br>
<sup>Font: IBM Plex Mono</sup>

## Installing

You can install the latest release from [the marketplace](https://marketplace.visualstudio.com/items?itemName=karolbelina.uxntal). The extension will be updated automatically as new versions become available.

Alternatively, download a VSIX from the [releases](https://github.com/karolbelina/uxntal-vscode/releases) page and install the extension with the `Extensions: Install from VSIX` command within VS Code, or from the command line via:

```console
code --install-extension uxntal-0.2.0.vsix
```

## Testing

This extension uses [vscode-tmgrammar-test](https://github.com/PanAeon/vscode-tmgrammar-test) for testing. Check out its [Installation](https://github.com/PanAeon/vscode-tmgrammar-test#installation) section for tips on how to install it as a standalone command line tool.

Once you have it, run the whole test suite with

```console
vscode-tmgrammar-snap tests/*.tal
```

or provide the path to an individual test case.

## License

This software is licensed under the MIT license.

See the [LICENSE](LICENSE) file for more details.
