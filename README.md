# Extension-Manager

Allows exporting of the VS Code Extensions for reimport into new profile

## Export from VS Code

```bash
code --list-extensions | sed -e 's/^/code --install-extension /' > my_vscode_extensions.sh
```

## Import to VS Code

```bash
bash ./my_vscode_extensions.sh
```
