# MacOS Terminal com OhMyZsh

## 1. Baixar Script de Customização

```shell
git clone https://github.com/andersonbraz/customize-teminal-macos.git
cd customize-teminal-macos
```

## 2. Executar Script de Customização

```shell
chmod 755 custom-macos-terminal.sh
./custom-macos-terminal.sh
```

## 3. Ajustar ZSH

```shell
code ~/.zshrc
```

### 3.1. Configurar Tema

```shell
ZSH_THEME="powerlevel9k/powerlevel9k"
```

### 3.1. Configurar Plugins

```shell
plugins={
    git
    docker
    zsh-syntax-highlighting
    zsh-autosuggestions
}
```


## Reference

[How to Configure your macOs Terminal with Zsh like a Pro](https://www.freecodecamp.org/news/how-to-configure-your-macos-terminal-with-zsh-like-a-pro-c0ab3f3c1156/)