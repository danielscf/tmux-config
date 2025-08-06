# Tmux configuration

## Requirements

- `wl-clipboard` or `xclip`
- `pywal` (Optional)

## Plugins

Install `tpm` using

```sh
git clone https://github.com/tmux-plugins/tpm ~/.tmux/plugins/tpm
```

Source file

```sh
tmux source-file ~/.config/tmux/tmux.conf
```

## Theme

If `pywal` isn't present, rename `colors.conf.template` to `colors.conf`

## Clipboard

Comment and uncomment the options in `keybinds` for `wl-copy` and `xclip`
