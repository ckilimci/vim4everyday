The Basic Vim Movements
=======================

In Vim, you can move around with "h, j, k, l" like an arrows, like this:
  k
h j l 

Obviously, it is inconvenient to move with many "l", so you can use "w" for one word forward and "b" for one word backward.

Editting Commands
-----------------
For copying line, you can "yy" - Yank line, and you can paste with "p" one line below. If you want to delete, you can "dd". You can always paste deleted line, too. In addition, you can undo with "u".

Virtual Mode
------------
With "Shift-v" (Capital v), you will highlight a line. You are in visual line mode. You can highlight with "j, k" and you can edit with editting commands. If you just simply press "v", you will be in virtual mode where the cursor it is. You can highlight with "h, j, k, l" and then command.

Insert Mode
-----------
"i" goes into insert mode. You can type now :)

If you want to leave this mode, three options you have:
1. "escape"
2. "ctrl-c"
3. "ctrl-["

Which Mode Am I In?
-------------------
You can see your mode at the bottom of the screen. If you do not see "INSERT, VISUAL, V-LINE", then you are in normal mode. In other word, if nothing written at the bottom, you are in the normal mode. You can move around and command.

Saving
------
You can save with ":w".
