Installation
------------

To install, run

    git clone git://github.com/nviennot/tmux-config.git ~/.tmux
    cd ~/.tmux
    make install

To update the repository, run

    make update

Key Bindings
-------------

`Alt + E` Prefix (you probably won't need it)  

The following key bindings do not require you to send the prefix keystroke:

`Alt + |` Split vertically  
`Alt + -` Split horizontally

`Alt + H` Go to the left pane  
`Alt + J` Go to the bottom pane  
`Alt + K` Go to the top pane  
`Alt + L` Go to the right pane  

`Alt + Arrow` Resize pane  

`Alt + PageUp` Copy mode and page up  
`Alt + U` Copy mode
`Alt + I` Paste  

`Alt + 8` Choose a session to attach  
`Alt + 9` Cycle left through sessions  
`Alt + 0` Cycle right through sessions  

`Alt + D` Detach  

Ubiquitous Tmux
----------------

You can use `tmux-login` as a login shell to always run your favorite shell
inside a tmux session.

**Important:** It's nearly impossible to get a terminal without a tmux session,
so attaching to a remote tmux session (e.g. doing pair programing) can be challenging.
Running `konsole zsh` or `xterm zsh` (replace with your terminal) spawns a
terminal without tmux.

Notes
-----

The status bar is hidden by default (type `tmux set status` to toggle it)
because creating windows is not part of my workflow.
I'd rather open a new tab in my terminal, or a new terminal.
To me, Tmux is a fix to what my terminal should have builtin.
