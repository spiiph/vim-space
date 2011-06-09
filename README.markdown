# space.vim

space.vim is a plugin which remaps the `<Space>` key to act as a clever
key to repeat motions. It hooks into several of the more complex motion
commands, such as search commands, diff movement commands, quickfix and
location list commands, tag commands and more. When a command that space.vim
has hooked into is issued, it remaps the `<Space>` key to repeat that
command, and it also remaps `<S-Space>` and `<BS>` to do the inverse.
