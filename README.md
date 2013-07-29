# MY GIT CONFIG FILES

Just some files I'm too lazy to rewrite every time I'm using a new computer or a new account.

If you're lazier than me, from your home you can pull this project after forked it :

	git init 
	git remote add origin https://github.com/you/my-git-config-files.git
	git pull origin master

The .gitignore is conveniently whitelist configured so you can add/commit/push what you really want.

## Auto-completion and PS1 :

You can get git commands auto-completion in bash after adding this line in your ~/.bash_profile or ~/.bashrc or something else :   
`source /usr/local/git/contrib/completion/git-completion.bash`

And if you can't breathe anymore anytime you don't know your project status, you can add these lines too :

	GIT_PS1_SHOWDIRTYSTATE=true
	export PS1='[\u@\h 👀  \w$(__git_ps1)]\$ '

