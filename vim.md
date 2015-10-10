Type :help
```console
:help sp (split window)
CTRL-W w (move between windows)
ctrl-w s (split current window horizontally, loading same file in new window)
ctrl-w v (split current window vertically, loading same file in new window)
:sp filename (split horizontally, loading filename in new window)
:vsp filename (split vertically, loading filename in new window)
:only (close all windows except current)
 ```

 Working with TABS
 ```console
vim -p first.txt  second.txt
:tabe filename (edit specified file in new tab)
:tabfind filename (open a new tab with filename given)
:tabc (close current tab)
:tabonly (close all other tabs to show only current)
:tabnew	" opens tabpage after the current one
:tabn (go to the next tab)
:tabp (go to previous tab)
:tabfirst (go to first tab)
:tablast (go to last tab)
gt (go to next tab)
gT (go to previous tab)
{i}gt go to tab in position i
```

Create and save file
```console
:w filename
```

** Type O to pen a line ABOVE the cursor. **
** Type o to open a line below the cursor and place you in Insert mode. **

** Type a to insert text After cursor **
** Type A to insert text after end of line **

Paste
```console
On INSERT mode CTRL-SHIFT-v
p (paste previously deleted text after cursor)
```

Copy and Paste Text
```console
Type v to get in visual mode and move cursor with jklh to highlight what you want to copy
Type y to yank (copy) or d (to cut) the highlighted text
Type p to put (paste) the text
"+yy (copy to system clipboard)
NOTE: you can also use y as an operator; yw yanks one word.
```

Replace
```console
rx (replace character after cursor with x)
R (replace more than one character without modifying rest of line)
```

Change
```console
ce (change until the end of a word)
```

Search
```console
/word (search and move cursor to word)
?word (search backward direction)
** To keep searching for same word type n **
** To search in opposite direction type N **
** CTRL-o to move cursor back **
** CTRL-i to move cursor forward **
```

Undo
```console
u (undo)
U (fix or undo a whole line)
Ctrl-r or R (undo the undo's)
```

Deletion
```console
dw (deletes word after cursor)
d$ (deletes everything after cursor)
de (deletes to the end of the current word:w)
dd (deletes whole line)
```

Appending
```console
A (append to end of line)
```

Navigation
```console
Ctrl-d (scroll down)
Ctrl-u (scroll up)
Shift-l (move to end of current window)
Shift-m (move to middle of current window)
Shift-h (move to top of the current window)
G (move to end of file)
gg (move to the first line)
```

Moving Cursor
```console
e (move cursor by end of word)
w (move cursor by word)
0 (move cursor to start of line)
$ (move cursor to end of line)
number G (move cursor to line number)
```

Execute external Command
** Type :! followed by an external command to execute **


** Typing a number before a motion repeats it that many times. **
