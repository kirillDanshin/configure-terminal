# Configure terminal
my terrminal setup commands

# The commands itself

```
# clone
git clone https://github.com/powerline/fonts.git
# install
cd fonts
./install.sh
# clean-up a bit
cd ..
rm -rf fonts
# install python-devel. one of this commands will fail but it's ok.
# yum command will work on fedora too.
sudo yum install python-devel
sudo apt-get install python-dev
# install thefuck
sudo pip install thefuck
# setup oh-my-zsh
sh -c "$(curl -fsSL https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"
```
