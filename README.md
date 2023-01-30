<h1 align="center">
	📖 42 & GIT ZSHRC CHEATSHEET
</h1>
<p align="center">
	<b><i>This repo is for making your work more efficient</i></b><br>
</p>

<p align="center">
	<img alt="GitHub code size in bytes" src="https://img.shields.io/github/languages/code-size/zstenger93/zshrc_aliases?color=lightblue" />
	<img alt="Code language count" src="https://img.shields.io/github/languages/count/zstenger93/zshrc_aliases?color=yellow" />
	<img alt="GitHub top language" src="https://img.shields.io/github/languages/top/zstenger93/zshrc_aliases?color=blue" />
	<img alt="GitHub last commit" src="https://img.shields.io/github/last-commit/zstenger93/zshrc_aliases?color=green" />
</p>
<p align="center">
	<b><i>I might should rather make this</i></b><br>
	<b><i>alias g='say go home && get a life'</i></b><br>
	:rofl: :rofl:
</p>

### 📋 How alias works:

> - alias (name of the alias)='(the command/s you want to assign to the alias)'

> - RTFM

### 💡 ZSHRC Themes via:

> - 

### 🛠️ Aliases I use:

> - To edit my aliases:
```shell
alias z='vi ~/.zshrc'
```

> - Touch
```shell
alias t='touch'
```

> - Move back one folder
```shell
alias .='cd ..'
```

> - Git add all and commit
```shell
alias ga='git add . && git commit -m'
```

> - Git diff
```shell
alias gd='git diff'
```

> - Git push
```shell
alias gp='git push'
```

> - Git clone the repo on my clipboard
```shell
c() {
	local copied_text
	copied_text=$(pbpaste)
	git clone $copied_text
}
```

> - Git status
```shell
alias gs='git status'
```

> - Git pull
```shell
alias p='git pull'
```

> - Add my libft as a git submodule (change it to yours..)
```shell
alias gsa='git submodule add https://github.com/zstenger93/libft.git'
```

> - Open my github profile (change it to yours..)
```shell
alias gh='open https://github.com/zstenger93'
```

> - Norm check
```shell
alias n='norminette'
```

> - Make commands
```shell
alias m='make'
```
```shell
alias mb='make bonus'
```
```shell
alias mc='make clean'
```
```shell
alias mf='make fclean'
```
```shell
alias mr='make re'
```

> - If you need a directory a lot of times for some reason
```shell
alias (name of the alias)='open (path to folder)'
```

> - AFK - Screen Lock
```shell
alias a='pmset displaysleepnow'
```
