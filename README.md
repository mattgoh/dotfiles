## tmux

```console
mv tmux.conf ~/.tmux.conf
```

Color palette for tmux pane:

```bash
for i in {0..255}; do
    printf "\x1b[38;5;${i}mcolour${i}\x1b[0m\n"
done
```


## virtualenvwrapper

The installation instructions are outdated, incomplete, or inaccurate

```shell
# check where virtualenvwrapper.sh is located
# then edit source line to this location or create symlink
# from this path
which virtualenvwrapper.sh

# export appropriate python3 location
which python3

export VIRTUALENVWRAPPER_PYTHON=/usr/bin/python3

```

## Useful utils (Linux)

- `undervolt` - georgewhewell - [Link](https://github.com/georgewhewell/undervolt)
- `tlp` - [Link](https://support.system76.com/articles/battery/)
- `powertop`
- `tmux-power` - [Link](https://github.com/wfxr/tmux-power)
- `powerlevel10k` - [Link](https://github.com/romkatv/powerlevel10k)
