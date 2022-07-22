# My personal Neovim Config

This is still somewhat experimental for me.

Currently I'm trying to get LSP and Java working. So be aware you need to install some things as defined [LunaVim's Java branch](https://github.com/LunarVim/nvim-basic-ide/tree/java-ide-0.7).

```bash
:LspInstall jdtls
```

```bash
git clone https://github.com/microsoft/java-debug ~/.config/nvim/java-debug

cd ~/.config/nvim/java-debug

./mvnw clean install
```


```bash
git clone https://github.com/microsoft/vscode-java-test.git ~/.config/nvim/vscode-java-test

cd ~/.config/nvim/vscode-java-test

npm install

npm run build-plugin
```

## Based on Neovim from scratch

by chrisatmachine.com/

Each video will be associated with a branch so checkout the one you are interested in, you can follow along with this [playlist](https://www.youtube.com/watch?v=ctH-a-1eUME&list=PLhoH5vyxr6Qq41NFL4GvhFp-WLd5xzIzZ).

