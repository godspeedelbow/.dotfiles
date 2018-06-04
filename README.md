dotfiles-public
=============

git
-------------

- Create symlink: `ln -s ~/dotfiles-public/.gitconfig ~/.gitconfig`

iTerm
-------------

- Go to `Settings > General`. Check `Load preferences from a custom folder or URL:`, select the path to the `~/dotfiles-public/iterm`

VSCode
-------------

- Create symlink: `ln -s ~/dotfiles-public/vscode/settings.json ~/Library/Application\ Support/Code/User/settings.json`

Sublime
-------------

- Create symlink: `ln -s ~/dotfiles-public/sublime/User/ ~/Library/Application\ Support/Sublime\ Text\ 3/Packages/User`

Credits: https://chrisarcand.com/sublime-text-settings-and-dotfiles/

Atom
-------------

**Setup**

- Create Atom folder: `mkdir ~/.atom`
- Create symlink: `ln -s ~/dotfiles-public/.atom/* ~/.atom/`

**Update packages**

- To make a snapshot, run `make packages.list`
- To install/update packages, run `make install-all-packages`

Credits: https://discuss.atom.io/t/installed-packages-list-into-single-file/12227/10
