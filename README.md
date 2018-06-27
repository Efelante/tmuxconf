# tmuxconf
## Installation
Tested on: `tmux` version 2.1, `tmux-resurrect` (sha1: 42f77b).

Requirements: `tmux-resurrect`, `git`, `bash`.

Clone the repo:
```bash
git clone https://github.com/Efelante/tmuxconf.git clone_path/repo_name
```
Inside `clone_path/repo_name/.tmux.conf` change the path to your `tmux-resurrect` repo.

Inside your home directory create the symbolic link to the `.tmux.conf`:
```bash
ln -s clone_path/repo_name/.tmux.conf ~/
```
Run tmux and load config:
```bash
tmux
tmux source ~/.tmux.conf
```
