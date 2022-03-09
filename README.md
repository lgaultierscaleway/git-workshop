# git-workshop

https://www.atlassian.com/fr/continuous-delivery/continuous-integration/trunk-based-development
not too many active remote branches, delete when stale
--> local branches, squash & rebase locally, push when it compiles
MAC USERS ONLY
https://raw.githubusercontent.com/git/git/master/contrib/completion/git-completion.bash
--> add this to bash config file
if [ -f ~/.config/bash/git-completion.bash ]; then
source ~/.config/bash/git-completion.bash
fi
Main configuration:
git config --global core.editor {vim,emacs,nano}
git config --global user.name "Louis PORTAY"
git config --global user.email "lportay@scaleway.com"
git config --global init.defaultBranch {master,trunk}
git config --global core.pager {slit,bat}
git config --global commit.template ~/.gitmessage.txt
Main git commands

switch
checkout
add
commit
remote
log
