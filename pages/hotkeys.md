---
layout: default
title: HotKeys Cheat Sheet
---
NB: these are the bits that I am learning on top of what I know so may not be very comprehensive.

# Command line

`systemctl suspend` to suspend from cli

# Kitty

[kitty overview](https://sw.kovidgoyal.net/kitty/overview/)

* New tab `ctrl+shift+t` 
* Close tab `ctrl+shift+q` 
* Next tab `ctrl+shift+right`
* Previous tab `ctrl+shift+left`
* Set tab title `ctrl+shift+alt+t`

Windows don't worry about yet

* Browse scrollback in less `ctrl+shift+h`
* Browse last cmd output `ctrl+shift+g`

# Fish

* 
* `Ctrl+R` for history search
* `dirh` prints the history
* `cdh` displays a prompt to quickly navigate the history
* `prevd` moves backward through the history. It is bound to `Alt+←`
* `nextd` moves forward through the history. It is bound to `Alt+→`

# Lazy/NeoVim

To paste when inserting `Ctrl+R`` then `+`

`P` to insert before the cursor. 

`"` to open a named register `"xyy` save line to register x `"xp` to paste it.

## Spell check
[This guide is good](https://neovim.io/doc/user/spell.html)

`[s` and `]s` to search.

`z=` to list possible words

`zg` adds a word to the word list.


## Visual mode
 enter with `v` but also `V` to select a line.

Commands work in visual mode, `w` to select word for example


`o` to go to the other end of the selected area.

`V` to go into a line wise visual mode.

`Control-v` for block visual mode.
 
