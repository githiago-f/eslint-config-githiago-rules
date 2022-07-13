# eslint-config-githiago-rules
My eslint default rules

## Instalation guide

```bash 
pnpm add -D eslint-config-githiago-rules@git@github.com:githiago-f/eslint-config-githiago-rules.git
```

## Utilization guide

```jsonc
// .eslintrc.json
{
  "extends": ["githiago-rules"]
}
```

## VSCode optional configuration

At `.vscode/settings.json` file, add the following lines:

```jsonc
{
  "eslint.format.enable": true,
  "eslint.codeActionsOnSave.mode": "problems",
  "editor.formatOnSave": false,
  "editor.codeActionsOnSave": {
    "source.fixAll.eslint": true
  }
}
```
