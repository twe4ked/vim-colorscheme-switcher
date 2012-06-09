# Colorscheme Switcher

Change the color scheme from a list of color scheme names.

This is simply a clone of a script found on vim.wikia to make it easy to
Vundle. Version 2010-09-12 from http://vim.wikia.com/wiki/VimTip341.

## Keybindings

* `F8` - Next scheme
* `Shift-F8` - Previous scheme
* `Alt-F8` - Random scheme

## Commands

Set the list of color schemes used by the above (default is 'all'):

* `:SetColors all` - All `$VIMRUNTIME/colors/*.vim`
* `:SetColors my` - Names built into script
* `:SetColors blue slate ron` - These schemes
* `:SetColors` - Display current scheme names
* `:SetColors now` - Set the current color scheme based on time of day
