# Shortcut Key

Code fast and jjfly :p

# Direction

    h => left, j => down, k => up, l => right
    /* use (h j k l) instead of the arrow keys */

# Move Cursor

    w   move to the begin of next word
    e   move to the end of next word
    r   move to the begin of prev word
    $   move to the end of the line
    ^   move to the beginning of the line
    gg  move to the begginning of the file
    G   move to the end of the file
    :n  move to line n
    ngg move to line n
    fx  move to the x character of the line, type ";" to next, "," to prev

# Page Up & Down

    ctrl + b    page up
    ctrl + f    page down

# Switch to Insert Mode

    i   switch to insert mode before the current cursor position
    I   switch to insert mode at the beginning of the line
    a   switch to insert mode after the current cursor position
    A   switch to insert mode at the end of the line
    o   switch to insert mode at the next new line
    O   switch to insert mode at the prev new line
    s   switch to insert mode with deleting the current character

# Select

    v       begin select, type "esc" or "v" to exit
    V       select a line
    vw      select a word with spaces on right
    viw     select a word
    vit     select "vim" in "<cool>vim</cool>"
    viwx    select a word and delete it
    viwc    select a word and delete it and switch to insert mode
    /* all the selection can use with hjkl */

# Copy & Paste

    y   after select, type "y" can copy the selection
    yy  copy the current line
    nyy copy n line
    p   paste the copied content

# Delete

    x   delete the current character
    dd  delete the current line
    ndd delete n line
    /* the content which is deleted by x/dd can be pasted */

# Undo & Redo

    u           undo
    ctrl + r    redo

# Search

    /search_string: type "n" to search next, "N" to search prev

# Replace

    :%s/onepiece/ONEPIECE/g     g means global
    :m,ns/onepiece/ONEPIECE/    replace oncepiece => ONEPIECE on line m to n

# Format Code

    ==  format code on the current line, u can use it after a selection
    >G  indent code to right
    <G  indent code to left
    /* this can use with selection like Vj> */

# Repeat

This is super cool

    press . can repeat yr last operation like V>. or V>j.

# Combination

All the stuff above can be combined, for example:

    vw  select a word from current cursor position
    dw  delete a word from current cursor position
    v$  select from current cursor position to the end of the line
    d$  delete from current cursor position to the end of the line

Enjoy.


