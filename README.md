# zsh-aliases
My personal aliases for development on linux

## How to use my aliases
Clone the repository 
```sh 
git clone https://github.com/rafaelpvs/zsh-aliases.git 
```
If you don't have the ```~/.aliases``` file run the commands
```sh
cd zsh-aliases
cp .aliases ~/
```

If you have the ```~/.aliases``` file run the command
```sh
cat .aliases >> ~/.aliases
```
Add cammands to your ```.zshrc``` file to source the aliases everytime you open the terminal
```sh
echo "source ~/.aliases" >> ~/.zshrc
```
