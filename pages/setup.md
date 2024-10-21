---
layout: default
title: Random Setup notes
---

# Random setup notes
This is a page where I note the things I have set up on my laptop so that I can recreate and remember what I have done

## Tooling

* kitty 
* Neovim
* Lazyvim starter
* lazygit
* fish (command prompt)
* Opendyslexic nerd font
* vit (task manager)



## Reading
 * Folio e reader

Espeek-ng trying to get set up through speech-dispatcher so that I can get a better text to speech experiences.

## Website
This is done with bundler also ruby-dev

* `sudo apt install ruby`
* `sudo apt install make`  This is needed to make gems and native extensions
* `sudo apt install ruby-dev`
* `sudo apt install build-essential` to build extensions, this may include make?
* `sudo apt-get install libmagickwand-dev imagemagick` for some ruby image library, do I have images?


Installing ruby bundler seems to break things
`sudo gem instll bundler` seems to work better.


## How to...
### correct spellings in Neovim

`:set spell spelllang=en_gb`

This will turn on spelling and the locale

(This guide is good)[https://neovim.io/doc/user/spell.html]

`[s` and `]s` to search.

`z=` to list possible words

`zg` adds a word to the word list.


