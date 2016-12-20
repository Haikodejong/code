*start a new session*
```
tmux
tmux new
tmux new-session
```

*re-attach a detached session*
tmux attach OR
tmux attach-session

*re-attach an attached session (detaching it from elsewhere)*
tmux attach -d OR
tmux attach-session -d

*re-attach an attached session (keeping it attached elsewhere)*
tmux attach
tmux attach-session

*detach from currently attached session*
```
^b d
^b :detach
```

*rename-window to newname*
^b , <newname>
^b :rename-window <newn>

*list windows*
^b w

*list windows in chooseable menu	*
^a "

*go to window #*
^b #

*go to last-active window*
^b l

*go to next window*
`^b n`

*go to previous window*
`^b p`

*see keybindings*
`^b ?`

*list sessions*
```
^b s
tmux ls
tmux list-sessions
```

*create another window*
`^b c`

*exit current shell/window*
`^d	^d`

*split window/pane horizontally*
`^b "`

*split window/pane vertically*
`^b %`

*switch to other pane*
`^b o`

*kill the current pane*
`^b x OR (logout/^D)`

*collapse the current pane/split (but leave processes running)	*

*close other panes except the current one*
`^b !`

*cycle location of panes*
`^b ^o`

*swap current pane with previous*
`^b {`

*swap current pane with next*
`^b }`

*show time*
`^b t`

*show numeric values of panes*
`^b q`

*toggle zoom-state of current pane (maximize/return current pane)*
`^b z`

*break the current pane out of its window (to form new window)*
`^b !`

*re-arrange current panels within same window (different layouts)*
`^b [space]`