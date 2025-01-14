# vscode-config

Configurações e plugins "padrões" que uso no VSCode, é praticamente pra eu não esquecer as configs que geralmente uso.

Primeira coisa a fazer é instalar a fonte [JetBrains Mono](https://www.jetbrains.com/pt-br/lp/mono/) no PC.

Depois instalar as extensões no VSCode:
- Min Theme
- Symbols
- Better Comments
- Svg Preview
- Color Highlight
- Tailwind CSS IntelliSense
- ESLint
- Prettier ESLint
- vscode-styled-components

Agora é só copiar e colar:

### settings.json

```json
{
   "window.zoomLevel": 0.8,
   "editor.fontFamily": "'JetBrains Mono', monospace",
   "editor.fontSize": 14,
   "editor.lineHeight": 1.8,
   "editor.fontLigatures": true,
   "workbench.colorTheme": "Min Dark",
   "workbench.iconTheme": "symbols",
   "symbols.hidesExplorerArrows": false,
   "workbench.startupEditor": "newUntitledFile",
   "workbench.editor.labelFormat": "short",
   "explorer.compactFolders": false,
   "editor.semanticHighlighting.enabled": false,
   "breadcrumbs.enabled": false,
   "editor.minimap.enabled": false,
}
```
