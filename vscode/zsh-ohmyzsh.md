## Linux + oh my zsh + powerline fonts + visual studio code (vscode) terminal settings
> Thank you everybody, Your comments makes it better

### Install oh my zsh
http://ohmyz.sh/

```sh
sh -c "$(curl -fsSL https://raw.github.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
```

### Install powerline fonts
https://github.com/powerline/fonts

### or Install Nerd Fonts. (If you don't use powerline fonts)
https://www.nerdfonts.com/font-downloads
> recommend font: Hack Nerd Font https://github.com/ryanoasis/nerd-fonts/releases/download/v2.1.0/Hack.zip

### Change settings for vscode

#### How?
1. open vscode
2. open Command Pallete (Short Cut: `F1`)
3. type `settings` and Select `Preferences: Open Settings (JSON)`
4. Add or Edit below settings to Settings JSON file
5. Save.
6. That's all 

ps. This JSON type is `JSON with Comments`, so you can use comment syntax in it. 

```sh
"terminal.integrated.fontFamily": "Hack Nerd Font",

"terminal.integrated.defaultProfile.linux": "zsh",

```

### Change Theme for Mac OSX Terminal to agnoster

1. Add DEFAULT_USER=`whoami` in `~/.zshrc`
1. Change Theme to `agnoster` in `~/.zshrc`
1. Restart Terminal or `source ~/.zshrc` 


### Download `agnoster` theme and set up

1. Download https://github.com/mbadolato/iTerm2-Color-Schemes/zipball/master
2. Unzip
3. Open Mac Terminal
4. `CMD` + `,` open settings
5. on Left Sidebar, Click `Config` Icon and Select `Import...` 
6. Choose Terminal Schema: `UnzipPath/terminal/*.terminal`
7. I recommend `Solarized Dark.terminal` 
8. then, make it default (select imported schema and click "Default" button below)
9. That'all. if you restart terminal, you can see great `agnoster` theme with oh my zsh.

