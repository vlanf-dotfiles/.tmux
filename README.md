## Installation

1. Go to home directory
2. Clone repo
3. Run commands:
```sh
cd ~/.tmux
git submodule update --init
./setup.sh
```
4. In tmux run `prefix` + `I`
5. Enjoy

## Keybindings

### tmux-sensible

https://github.com/tmux-plugins/tmux-sensible

* `prefix + Ctrl-p` - previous windows
* `prefix + Ctrl-s` - next window
* `prefix + R` - source file

### tmux-resurrection

https://github.com/tmux-plugins/tmux-resurrect

* `prefix + Ctrl-s` - save
* `prefix + Ctrl-r` - restore

### tmux-pain-control

https://github.com/tmux-plugins/tmux-pain-control

* `prefix + hjkl` - move to pane
* `prefix + HJKL` - resize current pane by 5 cells
* `prefix + |-\_` - split pane
* `prefix + > <` - move window to right or left
