# INSTALLATION

```
git clone git@github.com:drblallo/rl-lsp.git
cd rl-lsp
npm install
npm run compile
npx @vscode/vsce package
```

then from vscode

view -> Extensions -> (...) -> Install from VSIX -> rl-lsp-0.0.1.vsix

if you have not installed rlc in /bin/ you will need to configure the path to it

view -> Extensions -> right click on rlc-lsp -> Extension setting -> set `RLC LSPPath` to point to the right directory
