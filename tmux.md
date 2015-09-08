Open with tmux -2 (so it doesn't pick up a different scheme for vim)

Ctrl-b options reference:

Basics
```console
? get help
```

Session management
```console
s list sessions
$ rename the current session
d detach from the current session
```

Scrolling
```console
Ctrl-b then [ (gets into scroll mode)
q (quits scrool mode)
```

Windows
```console
c create a new window
, rename the current window
w list windows
% split horizontally
" split vertically
n change to the next window
p change to the previous window
0 to 9 select windows 0 through 9
```

Panes
```console
% create a horizontal pane
" create a vertical pane
h move to the left pane. *
j move to the pane below *
l move to the right pane *
k move to the pane above *
k move to the pane above *
q show pane numbers
o toggle between panes
} swap with next pane
{ swap with previous pane
! break the pane out of the window
x kill the current pane
```

Miscellaneous
```console
t show the time in current pane
```

List Sessions:
```console
tmux ls
Ctrl-b s
```

Create a new session:
```console
tmux new -s session-name
```

Attaching to an existing session:
```console
tmux a
tmux a -t session-name
```

Detaching from a session:
```console
tmux detach
Ctrl-b d
```

Killing a session:
```console
tmux kill-session -t session-name
```

[ NOTE: You can kill windows the same way, but using kill-window instead. You can also kill tmux altogether with killall tmux. ] 
