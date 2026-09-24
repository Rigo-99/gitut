# here set the ssh keys





Define the command `git graph` to see the graph of the repo with (id, user, message, branch pointers) for each commit.
```
git config --global alias.graph "log --all --graph --pretty=format:'%C(yellow)%h%C(reset) [%C(cyan)%an%C(reset)] %C(white)%s%C(reset) %C(auto)%d%C(reset)'"
```

Set your user/mail
```
git config --global user.name YOUR-NAME
git config --global user.email YOUR-EMAIL 
```


