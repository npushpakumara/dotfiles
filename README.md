# Dotfiles

Welcome to my dotfiles repository! This collection contains my personal configurations for various tools and environments to streamline my workflow across multiple machines.

## Prerequisites

Before using these dotfiles, make sure you have the following installed:

- [Alacritty](https://github.com/alacritty/alacritty): A fast, cross-platform, GPU-accelerated terminal emulator.
- [Fish](https://fishshell.com/): An user-friendly shell with powerful features and sensible defaults.
- [Fisher](https://github.com/jorgebucaran/fisher): Plugin manager for Fish that simplifies adding, updating, and managing plugins.
- [Tide](https://github.com/IlanCosman/tide): Modern, highly customizable prompt theme for Fish.
- [z](https://github.com/jethrokuan/z): A directory jumping tool for Fish that allows quick navigation to frequently used directories.
- [fzf](https://github.com/PatrickF1/fzf.fish): A Fish wrapper for fzf, a command-line fuzzy finder for navigating files and directories.
- [MesloLGS Nerd Font](https://www.nerdfonts.com/): A patched font with a high number of glyphs and symbols, ideal for terminal usage with powerline and other applications.
- [GNU Stow](https://www.gnu.org/software/stow/): To manage and symlink the configurations.

## Managed Configurations

- **Fish Shell**: Custom prompts and aliases for an enhanced terminal experience.
- **Alacritty**: A clean and minimal terminal setup with custom themes and settings.
- **Git**: Simplified and powerful git commands with aliases and configurations.

## Installation

Clone the repository and use GNU Stow to set up the configurations:

```bash
git clone https://github.com/npushpakumara/dotfiles.git
cd dotfiles

stow .
```

Feel free to fork this repository and adapt the configurations to your needs.
