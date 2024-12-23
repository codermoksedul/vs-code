# vs-code

### VS Code settings.json code here

```
{
  "css.validate": false,
  "tailwindCSS.emmetCompletions": true,
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
    "source.fixAll.eslint": "explicit",
    "source.fixAll.tslint": "explicit",
    "source.organizeImports": "explicit"
  },
  "eslint.alwaysShowStatus": true,
  // emmet
  "emmet.triggerExpansionOnTab": true,
  "emmet.includeLanguages": {
    "javascript": "javascriptreact"
  },
  "terminal.integrated.defaultProfile.windows": "Git Bash",
  "workbench.iconTheme": "vscode-icons",
  "editor.wordWrap": "on",
  "workbench.startupEditor": "none",
  "powermode.combo.counterEnabled": "hide",
  "powermode.combo.location": "off",
  "powermode.enabled": true,
  "powermode.combo.counterSize": 2,
  "powermode.shake.intensity": 0,
  "powermode.explosions.size": 5,
  "explorer.confirmDragAndDrop": false,
  "javascript.updateImportsOnFileMove.enabled": "always",
  "security.workspace.trust.untrustedFiles": "open",
  "explorer.confirmDelete": false,
  "liveServer.settings.donotShowInfoMsg": true,
  "typescript.updateImportsOnFileMove.enabled": "always",
  "terminal.integrated.env.windows": {},
  "console-ninja.featureSet": "Community",
  "git.openRepositoryInParentFolders": "never",
  "githubPullRequests.createOnPublishBranch": "never",
  "git.autofetch": true,
  "hediet.vscode-drawio.resizeImages": null
}


```
### Eslintrc code here

```
{
  "extends": [
    "airbnb",
    "airbnb/hooks",
    "eslint:recommended",
    "prettier",
    "plugin:jsx-a11y/recommended"
  ],
  "parser": "babel-eslint",
  "parserOptions": {
    "ecmaVersion": 8
  },
  "env": {
    "browser": true,
    "node": true,
    "es6": true,
    "jest": true
  },
  "rules": {
    "react/react-in-jsx-scope": 0,
    "react-hooks/rules-of-hooks": "error",
    "no-console": 0,
    "react/state-in-constructor": 0,
    "indent": 0,
    "linebreak-style": 0,
    "react/prop-types": 0,
    "jsx-a11y/click-events-have-key-events": 0,
    "react/jsx-filename-extension": [
      1,
      {
        "extensions": [".js", ".jsx"]
      }
    ],
    "prettier/prettier": [
      "error",
      {
        "trailingComma": "es5",
        "singleQuote": true,
        "printWidth": 100,
        "tabWidth": 4,
        "semi": true,
        "endOfLine": "auto"
      }
    ]
  },
  "plugins": ["prettier", "react", "react-hooks"]
}

```



