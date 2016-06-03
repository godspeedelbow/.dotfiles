.dotfiles
=============

.sublime
-------------

**Install**

- Create symlink: `ln -s ~/.dotfiles/sublime/User/ ~/Library/Application\ Support/Sublime\ Text\ 3/Packages/User`

Credits: https://chrisarcand.com/sublime-text-settings-and-dotfiles/

.atom
-------------

**Install**

- Create Atom folder: `mkdir ~/.atom`
- Create symlink: `ln -s ~/.dotfiles/.atom/* ~/.atom/``

**Update packages**

- To make a snapshot, run `make packages.list`.
- To update packages, run `make install-all-packages`.

Credits: https://discuss.atom.io/t/installed-packages-list-into-single-file/12227/10
