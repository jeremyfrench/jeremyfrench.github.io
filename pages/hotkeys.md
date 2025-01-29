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

Windows:

* New window `ctrl+shift+enter`
* Close window `ctrl+shift+w`
* Next window `ctrl+shift+]`
* Previous window `ctrl+shift+[`
* change layout `ctrl+shift+l`

* Browse scrollback in less `ctrl+shift+h`
* Browse last cmd output `ctrl+shift+g`

# Fish

* `Ctrl+R` for history search
* `dirh` prints the history
* `cdh` displays a prompt to quickly navigate the history
* `prevd` moves backward through the history. It is bound to `Alt+←`
* `nextd` moves forward through the history. It is bound to `Alt+→`

# Lazy/NeoVim
This section is mostly notes from [LazyVim for ambitious developers](https://lazyvim-ambitious-devs.phillips.codes/)

Space Space is similar to Shift Shift in phpstorm

Press `esc` if you need to enter and a snippet is selected

` /` does whole project grep!

`ctrl+z` suspend and `fg` to return (look into fg and bg)

# Picker

type for fuzzy search

`esc` for normal mode then can navigate with hjkl 

`s` to allow fast picking

`cntrl` dufb to scroll the preview window



# Clipboard

LazyVim default register is system clipboard

To paste when inserting `Ctrl+R`` then `+`

`P` to insert before the cursor. 

`"` to open a named register `"xyy` save line to register x `"xp` to paste it.

can use delete `x` or `d` to delete and store in register.

Capital register name will append to register

## Spell check
[This guide is good](https://neovim.io/doc/user/spell.html)

` us` to turn on spellings.

`[s` and `]s` to search.

`z=` to list possible words

`zg` adds a word to the word list.


## Visual mode
 enter with `v` but also `V` to select a line.

Commands work in visual mode, `w` to select word for example


`o` to go to the other end of the selected area.

`V` to go into a line wise visual mode.

`Control-v` for block visual mode.
 
## Widows tabs etc

Lazy vim doesn't use tabs by default so `tabe` `q` `gT` will work but are not the way

What look like tabs are 'buffers'

`H` and `L` (uppercase left and right) to switch between buffers

also `:bprev` and `:bnext`

` ,` space comma to bring a list of open buffers if there are too many.  

` b` gives a buffer 'sub menu' with options.

` bd` close buffer

windows = splits

` w` to show sub menu

`ctrl+` nav keys hjkl to move between them

`ctrl+w` also fast to window menu

`ctrl+w q` to quit window.

Tabs work differently, bunch other things together.

## Marks

`m` then letter to bookmark (capital letters are global)
`'` then letter to go to bookmark

`''` to go back one


## Code folding

`zc` close fold

`zo` open fold

## Code assistance.

 `gd` go to definition (not tabs)

`gr` go to reference list.

 go back `ctrl+i` forward again  `ctrl+o`

` ss` Search Symbols (in file)

` cs` to open tree view for current file

 ` xx` to open the browser then `[q` and `]q` work for browsing issues.

 `crl+j` to go to issue browser window. Enter to jump to issue

 ` ca` open up fixes window.

 `K` for Kontext help.

 `gc` for commenting. works with commands `gc5` then enter for five lines `gc%` to comment out matcing brac `S` gives smart search options.

 `=` to fix indentation `=S` to choose area to fix.

` gs` git status file picker.

` gh` staging changes

` gg` open lazygit if installed


# Lynx

start `lynx -cfg=.lynxrc`

`q` quit

Type `a` to save a bookmark

Type `v` to view bookmarks

# vit task
vit visual

`:help` when in it for help.

`d` done
`a` add a task

`task` has a lot.


