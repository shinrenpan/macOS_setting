## 必裝軟體

- [Homebrew], 按照官方 bash 指令安裝
- [XcodesApp], 直接下載 app 或使用 [Homebrew] 安裝
- Xcode, 使用 [XcodesApp] 安裝, 而不是從 App Store 下載
- [JetBrains Mono] 字型
- [zim]
- [Starship], 使用 [Homebrew] 安裝
- [Homebrew] git 替代 macOS git, brew install git 後, 重新開啟終端機就行 (macOS Sequoia), 不需要再任何設置


## 指令設置

### GitHub SSH Key

在 ~./ssh 使用下面指令

```
ssh-keygen -t ed25519 -C "your_email@example.com"
```

copy .pub 檔內容至 github -> settings -> SSH and GPG keys -> New SSH key

## 檔案

### starship.toml

[Starship] 設置檔  
下載存放至 ~/.config, 並在 ~/.zshrc 檔案加入

```
eval "$(starship init zsh)"
```

### Custom.terminal

終端機設置檔  
下載後點擊即可安裝

### Custom.xccolortheme

Xcode theme  
下載至存放至 ~/Library/Developer/Xcode/UserData/FontAndColorThemes


[Homebrew]: https://brew.sh
[XcodesApp]: https://github.com/XcodesOrg/XcodesApp
[JetBrains Mono]: https://www.jetbrains.com/lp/mono/
[zim]: https://github.com/zimfw/zimfw
[Starship]: https://starship.rs