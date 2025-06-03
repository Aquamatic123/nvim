# 🚀 Installation


# (Optional) Backup your current config
```mv ~/.config/nvim ~/.config/nvim.backup ```

# Clone this repo
```git clone https://github.com/Aquamatic123/nvim ~/.config/nvim```

# Launch Neovim


> 💡 On first launch, plugins will install automatically using [lazy.nvim](https://github.com/folke/lazy.nvim).

---

### 🛠️ Requirements

Before using this config, make sure you have the following tools installed:

#### 🐧 Linux (Ubuntu/Debian)

```
sudo apt update
sudo apt install neovim git ripgrep fd-find build-essential nodejs npm python3-pip
```

#### 🍎 macOS

```
brew install neovim git ripgrep fd node python
```

#### 🪟 Windows

1. [Download Neovim](https://github.com/neovim/neovim/releases) and extract it into a folder in your `PATH`
2. [Download Git for Windows](https://git-scm.com/download/win)
3. [Download ripgrep](https://github.com/BurntSushi/ripgrep/releases)
4. [Download fd](https://github.com/sharkdp/fd/releases)
5. [Download Node.js](https://nodejs.org/)
6. [Download Python](https://www.python.org/)

> 📁 On Windows, place your config in:  
> `%userprofile%\AppData\Local\nvim`

