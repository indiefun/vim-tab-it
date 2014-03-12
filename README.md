## Description: 
vim plugin, modify the display method of the buf-it.vim, this script can show all buffer names in status line, and highlight the current buffer, you can use buffer switch command to switch buffer, the script will update the status line

## Installation
 * clone or download this repository
 * copy file tab_it.vim  into ~/.vim/plugin

## USAGE
 * you can use :bn to switch to next buffer, :bp to prev buffer, and :bd to close the buffer
 * also you can write .vimrc to add following map like me:
  * map \<left\> :bp\<cr\>
  * map \<right\> :bn\<cr\>
  * map \<leader\>d :bd\<cr\>
