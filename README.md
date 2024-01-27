# dotfiles

## Description
My dotfiles for bspwm

## Warning
This is my personal dotfiles, so it's not recommended to use it without understanding what it does.

## Setup
```
$ yay -S xorg xorg-xinit alacritty bspwm sxhkd nitrogen picom rofi numlockx betterlockscreen
```

## Previews
<details>
<summary>Clean screen</summary>
<img src="./imgs/Captura de tela de 2024-01-27 00-29-57.png"/>
</details>

<details>
<summary>Rofi Launcher</summary>
<img src="./imgs/Captura%20de%20tela%20de%202024-01-27%2002-39-23.png"/>
</details>

<details>
<summary>Rofi Power Menu</summary>
<img src="./imgs/Captura%20de%20tela%20de%202024-01-27%2002-41-29.png"/>
</details>

<details>
<summary>Rofi Run Menu</summary>
<img src="./imgs/Captura%20de%20tela%20de%202024-01-27%2002-42-08.png"/>
</details>

<details>
<summary>Neofetch</summary>
<img src="./imgs/Captura%20de%20tela%20de%202024-01-27%2002-44-59.png"/>
</details>

## Zsh

[Zsh theme](https://github.com/spaceship-prompt/spaceship-prompt)

and at the end of the .zshrc file, add the following lines:

```
SPACESHIP_PROMPT_ORDER=(
  user          # Username section
  dir           # Current directory section
  host          # Hostname section
  git           # Git section (git_branch + git_status)
  hg            # Mercurial section (hg_branch  + hg_status)
  exec_time     # Execution time
  line_sep      # Line break
  jobs          # Background jobs indicator
  exit_code     # Exit code section
  char          # Prompt character
)
SPACESHIP_USER_SHOW=always
SPACESHIP_PROMPT_ADD_NEWLINE=false
SPACESHIP_CHAR_SYMBOL="❯"
SPACESHIP_CHAR_SUFFIX=" "
```

### Credits
Pretty much every color scheme is from [catppuccin](https://github.com/catppuccin). Polybar design is from [ericmurphyxyz](https://github.com/ericmurphyxyz/dotfiles), modified for my needs. Rofi theme is from [catppuccin](https://github.com/catppuccin/rofi/tree/main/deathemonic) too, modified to combine with the polybar theme and because some icons are broken. The wallpaper is from [here](https://www.reddit.com/r/wallpaper/comments/crmlwi/you_look_lonely_1920_x_1080/).


