<h1 align="center">
	📖 42 & GIT ZSHRC CHEATSHEET
</h1>
<h2 align="center">
	<b><i>alias fa='few alias for lazy people'</i></b><br>
</h2>

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

<div align=center>
	<a href="https://ohmyz.sh/">
		<img src="https://ohmyz.sh/img/OMZLogo_BnW.png">
	</a>
</div>

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

> - Grep only the number of norm errors
```shell
alias n='n | grep Error: |  wc -l'
```

> - Grep only the error lines with their location
```shell
alias n='n | grep Error'
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

> - Brew install
```shell
alias b='brew install'
```

> - Valgrind
```shell
alias v='valgrind'
```

> - Valgrind memcheck
```shell
alias vmem='valgrind --leak-check=full --show-leak-kinds=all --track-origins=yes --error-limit=no --tool=memcheck'
```

> - Git commit history
```shell
alias gl='git log'
```

> - Git commit history short
```shell
alias glo='git log --oneline'
```

> - Git commit history with changes shown in the commits
```shell
alias gld='git log -p'
```

> - Git checkout
```shell
alias gco='git checkout'
```
