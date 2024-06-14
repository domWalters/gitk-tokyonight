# Tokyonight for [gitk](https://git-scm.com/docs/gitk)

> A dark theme for [gitk](https://git-scm.com/docs/gitk).

![Screenshot](./screenshot.png)

## Install with git

```bash
git clone https://github.com/domwalters/gitk-tokyonight "$HOME/.config/git"
```

## Issues

`gitk` doesn't have all the options to fully align with other versions of this
theme.

Notably, the following aspects of the UI remain non-configurable:

- [The colours of search terms](https://github.com/dracula/gitk/issues/14)
- Panel outlines

## Troubleshooting

- If you have issues with resizing the UI, or the colours of the bars between
  panels, try to change the value of `want_ttk` to `1`.
    - [Related issue on the Dracula theme](https://github.com/dracula/gitk/issues/11)

## Inspiration

- [Tokyonight theme for `vscode`](https://github.com/enkia/tokyo-night-vscode-theme)
- [Tokyonight theme for `neovim`](https://github.com/folke/tokyonight.nvim)
- [Dracula theme for `gitk`](https://github.com/dracula/gitk)

## License

[MIT License](./LICENSE)
