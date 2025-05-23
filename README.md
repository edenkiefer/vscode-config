# vscode-config

Configurações e plugins "padrões" que uso no VSCode, é praticamente pra eu não esquecer as configs que geralmente uso.

Primeira coisa a fazer é instalar a fonte [JetBrains Mono](https://www.jetbrains.com/pt-br/lp/mono/) no PC.

Depois instalar as extensões no VSCode:
- Auto Rename Tag
- Better Comments
- Code Spell Checker
- ESLint
- Github Copilot
- GitLens
- Markdown Preview Enhanced
- Min Theme
- Paste JSON as Code
- Path Intellisense
- Portuguese - Code Spell Checker
- Prettier - Code formatter
- Prettier ESLint
- Symbols
- Tailwind CSS IntelliSense

Agora é só copiar e colar:

### settings.json

```json
{
  //format
  "editor.defaultFormatter": "esbenp.prettier-vscode",
  "prettier.singleQuote": true,
  "prettier.semi": false,
  "prettier.jsxSingleQuote": false,
  "prettier.trailingComma": "all",
  "prettier.bracketSameLine": false,
  "prettier.printWidth": 80,
  "editor.formatOnSave": true,
  "editor.codeActionsOnSave": [
    "source.organizeImports",
    "source.fixAll",
    "source.fixAll.eslint"
  ],
  "editor.rulers": [80, 120],
  "editor.tabSize": 2,
  //editor
  "editor.bracketPairColorization.enabled": true,
  "editor.cursorSmoothCaretAnimation": "on",
  "editor.minimap.enabled": false,
  "editor.renderLineHighlight": "gutter",
  "editor.semanticHighlighting.enabled": false,
  "breadcrumbs.enabled": false,
  //font
  "editor.fontFamily": "'JetBrains Mono', monospace",
  "editor.fontLigatures": true,
  "editor.fontSize": 16,
  "editor.lineHeight": 1.6,
  //explorer
  "explorer.compactFolders": false,
  "explorer.confirmDragAndDrop": false,
  //terminal
  "terminal.integrated.fontFamily": "'JetBrains Mono', monospace",
  "terminal.integrated.fontSize": 15,
  //workbench
  "workbench.startupEditor": "none",
  "workbench.colorTheme": "Min Dark",
  "workbench.iconTheme": "symbols",
  "workbench.editor.labelFormat": "short",
  "workbench.activityBar.location": "top"
}
```
