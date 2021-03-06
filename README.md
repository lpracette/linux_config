# My dot files

## Quick install of console only dotfiles
```console
mkdir -p ~/.dotfiles && pushd ~/.dotfiles && \
bash -c "$(curl -sL --proto-redir -all,https https://raw.githubusercontent.com/lpracette/dotfiles/master/install.sh)" && \
popd
```
will install configuration files for:
* git [.gitconfig](https://github.com/lpracette/dotfiles/blob/master/.gitconfig)
* tmux [.tmux.conf](https://github.com/lpracette/dotfiles/blob/master/.tmux.conf)
* vim [.vimrc](https://github.com/lpracette/dotfiles/blob/master/.vimrc)
* ctags [.ctags](https://github.com/lpracette/dotfiles/blob/master/.ctags)
* zsh [.zshrc](https://github.com/lpracette/dotfiles/blob/master/.zshrc) [.shell_alias](https://github.com/lpracette/dotfiles/blob/master/.shell_alias) [.shell_env](https://github.com/lpracette/dotfiles/blob/master/.shell_env) [.shell_functions](https://github.com/lpracette/dotfiles/blob/master/.shell_functions)
* bash [.bashrc](https://github.com/lpracette/dotfiles/blob/master/.bashrc) [.shell_alias](https://github.com/lpracette/dotfiles/blob/master/.shell_alias) [.shell_env](https://github.com/lpracette/dotfiles/blob/master/.shell_env) [.shell_functions](https://github.com/lpracette/dotfiles/blob/master/.shell_functions)


## Quick oneliner for a very basic vim config
```console
echo "colo desert|set nu|set et|set ts=4|set nowrap|set hls|set is|set pt=<F2>|inoremap jk <esc>" > ~/.vimrc
```
|Command               |Explanation                                                                             |
|----------------------|----------------------------------------------------------------------------------------|
|``colo desert``       |Load color scheme 'desert'.                                                             |
|``set nu``            |Precede each line with its line number.                                                 |
|``set et``            |Use the appropriate number of spaces to insert a ``<Tab>``.                             |
|``set ts=4``          |Number of spaces that a ``<Tab>`` in the file counts for.                               |
|``set nowrap``        |Lines longer than the width of the window will not wrap.                                |
|``set hls``           |When there is a previous search pattern, highlight all its matches.                     |
|``set is``            |While typing a search command, show where the pattern, as it was typed so far, matches. |
|``set pt=<F2>``       |Specifies the key sequence that toggles the 'paste' option.                             |
|``inoremap jk <esc>`` |Remap jk to ``<esc>`` in insert mode.                                                   |


## i3 setup
see [i3.md](https://github.com/lpracette/dotfiles/blob/master/i3.md)
