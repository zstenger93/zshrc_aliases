<h1 align="center">
	📖 42 & GIT ZSHRC CHEATSHEET
</h1>
<h2 align="center">
	<b><i>alias fa='few alias for lazy people'</i></b><br>
</h2>
<p align="center">
	<b><i>I might should rather make this</i></b><br>
	<b><i>alias g='say go home && get a life'</i></b><br>
	:rofl: :rofl:
</p>

<h2>Menu</h2>
- [ZSH Themes](#zshrc-themes-via:)

<div align="center">
<h1>📋 How alias works:</h1>

alias (name of the alias)='(the command/s you want to assign to the alias)'

RTFM

<h1>💡 ZSHRC Themes via:</h1>

<div align=center>
	<a href="https://ohmyz.sh/">
		<img src="https://ohmyz.sh/img/OMZLogo_BnW.png">
	</a>
</div>

<h1>🛠️ Aliases I use:</h1>
<h2>Norm</h2>

```shell
alias n='norminette'
```

Grep only the number of norm errors
```shell
alias n='n | grep Error: |  wc -l'
```

Grep only the error lines with their location
```shell
alias n='n | grep Error'
```
<h2>Git</h2>

Git clone the repo on my clipboard
```shell
c() {
	local copied_text
	copied_text=$(pbpaste)
	git clone $copied_text
}
```

Git add all and commit
```shell
alias ga='git add . && git commit -m'
```

Git diff
```shell
alias gd='git diff'
```

Git push
```shell
alias gp='git push'
```

Git status
```shell
alias gs='git status'
```

Git pull
```shell
alias p='git pull'
```

Add my libft as a git submodule (change it to yours..)
```shell
alias gsa='git submodule add https://github.com/zstenger93/libft.git'
```

Git commit history
```shell
alias gl='git log'
```

Git commit history short
```shell
alias glo='git log --oneline'
```

Git commit history with changes shown in the commits
```shell
alias gld='git log -p'
```

Git checkout
```shell
alias gco='git checkout'
```
<h2>Make</h2>

Make
```shell
alias m='make'
```
Make bonus
```shell
alias mb='make bonus'
```
Make clean
```shell
alias mc='make clean'
```
make fclean
```shell
alias mf='make fclean'
```
make re
```shell
alias mr='make re'
```
<h2>Open links or folders</h2>

Open my github profile (change it to yours..)
```shell
alias gh='open https://github.com/zstenger93'
```

Open my intra profile
```shell
alias i='open https://profile.intra.42.fr/'
```

If you need a directory a lot of times for some reason
```shell
alias (name of the alias)='open (path to folder)'
```
<h2>Basic</h2>

To edit my aliases:
```shell
alias z='vi ~/.zshrc'
```

chmod
```shell
alias ch='chmod +x'
```

Touch
```shell
alias t='touch'
```

Move back one folder
```shell
alias .='cd ..'
```

AFK - Screen Lock
```shell
alias a='pmset displaysleepnow'
```

Brew install
```shell
alias b='brew install'
```
<h2>Valgrind</h2>

Valgrind
```shell
alias v='valgrind'
```

Valgrind memcheck
```shell
alias vmem='valgrind --leak-check=full --show-leak-kinds=all --track-origins=yes --error-limit=no --tool=memcheck'
```
</div>