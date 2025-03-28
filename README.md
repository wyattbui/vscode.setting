## MY SETTING VSCODE

###Export danh sách extensions đang cài
```bash
code --list-extensions > vscode-extensions.txt
```
💡 Import lại (máy khác):
```bash
cat vscode-extensions.txt | xargs -n 1 code --install-extension
```
