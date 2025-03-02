# tmux-onedark-theme


My modified [odedlaz tmux theme](https://github.com/odedlaz/tmux-onedark-theme)

## Installation

- Install [tpm](https://github.com/tmux-plugins/tpm)
- Add this line to your `.tmux.conf`:
```tmux
set -g @plugin 'odedlaz/tmux-onedark-theme'
```

- Reload tmux configuration with `tmux source-file ~/.tmux.conf`

- Install the plugin with `prefix + I`

# IMPORTANT NOTE

- Copy `gitty` script to your path (I.E. `~/.local/bin`) and make it executable
> The script is used to display not pushed commits and untracked files in the status line


## Screenshots

### Not a repo
![Not a repo](./screenshots/not_a_repo.png)

### Clean repo
![Clean repo](./screenshots/all_ok.png)

### Untracked files
![Untracked files](./screenshots/untracked_files.png)

### Unpushed commits
![Unpushed commits](./screenshots/not_pushed_commits.png)

### Both mentioned above
![Both mentioned above](./screenshots/both.png)


## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details
