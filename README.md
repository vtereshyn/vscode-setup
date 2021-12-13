# 🔥 My vscode settings

It is often necessary to reinstall from scratch. in order not to do the installation from the beginning, I will save it here.

### `settings.json`

```json
{
  "workbench.colorTheme": "GitHub Dark Default",
  "security.workspace.trust.untrustedFiles": "open",
  "editor.fontSize": 11,
  "editor.fontFamily": "Fira Code, Menlo, Monaco, 'Courier New', monospace",
  "editor.fontLigatures": true,
  "editor.bracketPairColorization.enabled": true,
  "[jsonc]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[typescriptreact]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "workbench.iconTheme": "material-icon-theme",
  "[typescript]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[json]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[xml]": {
    "editor.defaultFormatter": "DotJoshJohnson.xml"
  },
  "[vue]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[javascript]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "debug.javascript.autoAttachFilter": "smart",
  "debug.allowBreakpointsEverywhere": true,
  "debug.console.closeOnEnd": true,
  "explorer.confirmDelete": false,
  "material-icon-theme.folders.theme": "specific",
  "material-icon-theme.activeIconPack": "react",
  "terminal.integrated.fontFamily": "MesloLGS NF",
  "[yaml]": {
    "editor.defaultFormatter": "redhat.vscode-yaml"
  }
}
```

### Extensions

```ssh
code --install-extension alefragnani.Bookmarks
code --install-extension apollographql.vscode-apollo
code --install-extension dbaeumer.vscode-eslint
code --install-extension DotJoshJohnson.xml
code --install-extension eamodio.gitlens
code --install-extension esbenp.prettier-vscode
code --install-extension GitHub.github-vscode-theme
code --install-extension GitHub.vscode-pull-request-github
code --install-extension GraphQL.vscode-graphql
code --install-extension jpoissonnier.vscode-styled-components
code --install-extension ms-azuretools.vscode-docker
code --install-extension ms-vscode-remote.remote-containers
code --install-extension PKief.material-icon-theme
code --install-extension redhat.vscode-yaml
code --install-extension svelte.svelte-vscode
```