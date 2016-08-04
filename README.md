# Configure terminal
my terrminal setup commands

# The commands itself

```
cd ~
# clone
git clone https://github.com/powerline/fonts.git
# install
cd fonts
./install.sh
# clean-up a bit
cd ..
rm -rf fonts
# install python-devel. one of this commands will fail but it\'s ok.
# yum command will work on fedora too.
sudo yum install -y python-devel
sudo apt-get install -y python-dev
# install thefuck
sudo pip install thefuck
# install oh-my-zsh deps
sudo yum install -y git zsh
sudo apt-get install -y git zsh
# setup oh-my-zsh
sh -c "$(curl -fsSL https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"
sed -i 's/ZSH_THEME="robbyrussell"/ZSH_THEME="agnoster"/g' .zshrc
sed -i 's/plugins=(git)/plugins=(git lol go golang iwhois npm sudo systemadmin fancy-ctrl-z cp thefuck)/g' .zshrc
echo "alias gs='git status'
alias gush='git push '
alias gull='git pull '
alias ga='git add '
alias gc='git commit'
alias gd='git diff'
alias gch='git checkout'
alias gk='gitk --all&'
alias gx='gitx --all'
alias gb='git branch '" >> .zshrc
# install htop
sudo yum install -y htop
sudo apt-get install -y htop
```
