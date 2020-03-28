# Vim Language
* Vim is a terminal text editor
* This are only the basics of vim, but not the very basics.
* **VA** is viewable area.
## Motions
M, L, H: cursor on middle, low or high area of VA.
\>\> , << : controls indention of lines.
zt, zb, zz: shifts current line to top, bottom or middle of VA.
^, $: first or last non-blank character of the line.
0, g_ : first or last character of the line.
[number]$: moves [number] lines down, then to the last character. Ex: 20$.
:n == nG --> moves cursor to line n (relative if using relnumber)
), ( -> for sentences
}, { -> for paragraphs (paragraphs in vim are denoted by a blank line!)
fchar, tchar =  forwart, till char.
CTRL+u != CTRL+d: move 1/2 screen + cursor (up or down).
ctrl+F (forward), ctrl+B (backward) : 1 full screen.
ctrl+E moves screen up keeping cursor on line
ctrl+y moves screen down keeping cursor on line.
d$=D != d^ 
*,# next/prev ocurrence of the current word.
% matching ({[
Playing with some macros
qq g_ d$ : deletes trailing white space on a line.

## Marks

## Superb characters for search a/o replace
*,^ line starts with, $ ends w 
