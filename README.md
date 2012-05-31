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

`Ctrl + E` Prefix  

`Alt + |` Split vertically  
`Alt + -` Split horizontally

`Alt + H` Go to the left pane  
`Alt + J` Go to the bottom pane  
`Alt + K` Go to the top pane  
`Alt + L` Go to the right pane  

`Alt + Arrow` Resize pane  

`Alt + PageUp` Copy mode and page up  
`Alt + [` Copy mode  
`Alt + ]` Paste  

`Alt + 8` Choose a session to attach  
`Alt + 9` Cycle left through sessions  
`Alt + 0` Cycle right through sessions  

`Alt + D` Detach  

Notes
-----

The status bar is hidden by default (type `tmux set status` to toggle it)
because creating windows in not part of my workflow.
I'd rather open a new tab in my terminal, or a new terminal.
