# Zed config

This repo is the Zed config directory, symlinked to `~/.config/zed/` (Zed's
config path on macOS and Linux).

## Files

- `settings.json` — editor / UI settings
- `keymap.json` — keybinds (Ctrl-based, VSCode/Windows layout)
- `tasks.json` — tasks
- `themes/` — FireCode theme

`prompts/` is gitignored. Extensions are declared in `settings.json`
(`auto_install_extensions`) and install on launch.

## Restore

From the cloned repo (remove an existing `~/.config/zed` first):

    mkdir -p ~/.config
    ln -s `pwd` ~/.config/zed
