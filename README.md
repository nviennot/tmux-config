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

`Alt + =` Equal vertial panes  
`Alt + +` Equal horizontal panes  
`Alt + Arrow` Resize pane  

`Alt + PageUp` Copy mode and page up  
`Alt + U` Copy mode
`Alt + I` Paste  

`Alt + 8` Choose a session to attach  
`Alt + 9` Cycle left through sessions  
`Alt + 0` Cycle right through sessions  


Notes
-----

The status bar is hidden by default (type `tmux set status` to toggle it)
because creating windows is not part of my workflow.
I'd rather open a new tab in my terminal, or a new terminal.
To me, Tmux is a fix to what my terminal should have builtin.
