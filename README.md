# Windows-rice

Shareable Windows dotfiles for YASB, GlazeWM, Fastfetch, Cava, btop, PowerShell, and related tools.

## Configurations

- YASB: `configs/yasb/config.yaml`
- YASB stylesheet: `configs/yasb/styles.css`
- GlazeWM: `configs/glazewm/config.yaml`
- Fastfetch: `configs/fastfetch/config.jsonc`
- Fastfetch logo: `configs/fastfetch/ascii.txt`

## Project links

- [YASB](https://github.com/amnweb/yasb)
- [GlazeWM](https://github.com/glzr-io/glazewm)
- [Fastfetch](https://github.com/fastfetch-cli/fastfetch)
- [Cava](https://github.com/karlstav/cava)
- [btop](https://github.com/aristocratos/btop)
- [JetBrainsMono Nerd Font](https://github.com/ryanoasis/nerd-fonts/tree/master/patched-fonts/JetBrainsMono)

## Using these dotfiles

1. Clone this repository.
2. Install the tools you want from their official project pages.
3. Copy each config into the tool's local config directory.
4. Adjust paths, monitor settings, workspaces, hotkeys, and app names for your machine.
5. Reload the relevant application and keep a local backup before changing system-wide settings.

The current YASB config lives at `%USERPROFILE%\\.config\\yasb`. GlazeWM normally uses `%USERPROFILE%\\.glzr\\glazewm`, and Fastfetch normally uses `%USERPROFILE%\\.config\\fastfetch`.

## Weather API key

The tracked YASB weather config intentionally contains an empty `api_key`. Anyone using the weather widget must add their own WeatherAPI key locally. 

## Optional tools

Cava provides terminal audio visualizations and btop provides a terminal system monitor. They are documented here because they are part of the local setup, but this repository does not require either tool to run YASB, GlazeWM, or Fastfetch.

## Public assets

Use `public/` for screenshots, terminal-showdown images, wallpapers you have permission to redistribute, and other non-sensitive assets. Do not place API keys, logs, personal documents, private screenshots, or identifying system information there.

## Safety notes

- Review every file before pushing it to a public repository.
- Keep machine-specific overrides in ignored `*.local.*` files.
- Do not commit logs, backups, credentials, or files containing personal paths.
- The wallpaper path and application launch commands may need adjustment on another machine.