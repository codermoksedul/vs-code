# vs-code

<h1>VS Code settings.json code here<h1/>

```
<p>
{
  "liveSassCompile.settings.formats": [
    {
      "format": "expanded",
      "extensionName": ".min.css",
      "savePath": "/css",
      "savePathReplacementPairs": null
    }
  ],
  "workbench.colorTheme": "Learn with Sumit - Peace of the eye",
  "files.autoSave": "onFocusChange",
  "editor.fontSize": 20,
  "editor.fontFamily": "Operator Mono, Consolas, 'Courier New', monospace",
  "editor.cursorBlinking": "expand",

  // config related to code formatting
  "editor.defaultFormatter": "esbenp.prettier-vscode",
  "editor.formatOnSave": true,
  "[javascript]": {
    "editor.formatOnSave": false,
    "editor.defaultFormatter": null
  },
  "[javascriptreact]": {
    "editor.formatOnSave": false,
    "editor.defaultFormatter": null
  },
  "javascript.validate.enable": false, //disable all built-in syntax checking
  "editor.codeActionsOnSave": {
    "source.fixAll.eslint": true,
    "source.fixAll.tslint": true,
    "source.organizeImports": true
  },
  "eslint.alwaysShowStatus": true,
  // emmet
  "emmet.triggerExpansionOnTab": true,
  "emmet.includeLanguages": {
    "javascript": "javascriptreact"
  },
  "terminal.integrated.defaultProfile.windows": "Git Bash",
  "workbench.iconTheme": "vscode-icons",
  "editor.wordWrap": "on"
}
<p/>
```

