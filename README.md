# tmux

My tmux configuration.

## Plugins

- [tpm](https://github.com/tmux-plugins/tpm) - Tmux Plugin Manager
- [tmux-sensible](https://github.com/tmux-plugins/tmux-sensible) - Sensible defaults
- [dracula/tmux](https://github.com/dracula/tmux) - Dracula theme

## Key Bindings

Prefix is `C-z` (instead of default `C-b`).

| Binding | Action |
|---------|--------|
| `C-z k` | Select pane up |
| `C-z j` | Select pane down |
| `C-z h` | Select pane left |
| `C-z l` | Select pane right |

## Setup

1. Install [tpm](https://github.com/tmux-plugins/tpm):
   ```
   git clone https://github.com/tmux-plugins/tpm ~/.tmux/plugins/tpm
   ```
2. Clone this repo:
   ```
   git clone https://github.com/graffitiape/tmux ~/.config/tmux
   ```
3. Press `C-z I` inside tmux to install plugins.
