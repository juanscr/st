# st
In this project my own build for the suckless terminal can be found. This build
does only what I think works for me and my workflow. Furthermore, there aren't
any major differences to the stantard st build as a minimum amount of patches
have been done to preserve simplicity.

This build has:
- An alpha value that determines the transparency of the background of the
terminal.
- Only scrollback using keys, as mouse scrollback it's unnecessary and can be
achieved by using other tools as tmux.
- A vim-like keys, to facilitate easy movement through the terminal and text.

Build based on __st 0.8.3__.
