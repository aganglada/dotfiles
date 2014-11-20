dotfiles
========

my .dotfiles configuration

### Install

    curl -L http://install.ohmyz.sh | sh
    
## useful aliases:

##### tree alias

Do yo want your log looking pretty?

command:

    git log --graph --full-history --all --color --date=short --pretty=format:"%Cred%x09%h %Creset%ad%Cblue%d %Creset %s %C(bold)(%an)%Creset"
    
add it to your alias:

    git config --global alias.tree 'log --graph --full-history --all --color --date=short --pretty=format:"%Cred%x09%h %Creset%ad%Cblue%d %Creset %s %C(bold)(%an)%Creset"'


