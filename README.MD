Installation instructions  :

Optional: install [starship.rs](https://starship.rs) and/or source-highlight

```bash
mkdir $HOME/projects/
cd $HOME/projects/
git clone --recursive https://github.com/gquiniou/dotfiles.git
ln -s $HOME/projects/dotfiles/mybashrc $HOME/.mybashrc
ln -s $HOME/projects/dotfiles/aliases $HOME/.aliases
ln -s $HOME/projects/dotfiles/mydotemacs $HOME/.mydotemacs
ln -s $HOME/projects/dotfiles/env $HOME/.myenv

echo "source \$HOME/.mybashrc" >> $HOME/.bashrc
echo "(load \"~/.mydotemacs\" nil t)" >> $HOME/.emacs
```
