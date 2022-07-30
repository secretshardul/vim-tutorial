# Vim tutorial

1. Exit: `:q`
2. Exit and dismiss changes: `:q!`. Add ! mark

3. Insert mode:
  - `i`: Add text to file. Press Escape to exit to the normal mode.
  - `A`: Insert mode at end of line.
  - `O`: Insert above current line.
  - `o`: Insert below current line.
4. Write: `:w`. Write and quit using `:wq`.
5. Display lines: `:set number`, `:set relativenumber` for relative numbers.
6. Navigation
  - h, j, l, k for navigation
  - Number + up or down to move by X number of lines
7. Configuration commands are temporary. They must be saved in `~/.vimrc`
8. Undo: `u`. Multiple undos using `3u`
9. Redo: `Ctrl + r`. Multiple redos using `3ctrl+r`
10. Visual mode: `v`. Used to select text. `shift + v` for visual line mode to select multiple lines. `Ctrl + v` for visual block mode, where you can select columns.
  - Delete (cut) selected text using `d`. The text is copied to clipboard. `dd` to delete entire line. Delete two words using `d2w`.
  - Copy (yank) using `y`. `yy` to yank whole line.
  - Copy (yank) using `y`.
  - Paste with `p`. Paste multiple with `5p`. `P` to paste at start.
11. Next word: `w`
12. Last word: `b`
13. End of word: `e`
14. Line start: `0`. Use `I` to go at line start in insert mode.
15. End of line: `$`
16. Change in quotation marks: `ci"`. To delete in quotes use `di"`. Copy using `yi"`.This selects and operates upon text enclosed between two `"`.
17. Jump to start of page: `gg`.
18. Jump to end of page: `G`.
19. Go to a specific line: `10G`.
20. Indentation: `>>` to right, `<<` to left. `==` to fix indentation. To fix a bunch of lines, go into visual mode, select the lines and press `==`.
21. Search: `/myword`. Go to next instance with `*`, previous instance with `#`. Replace using `:%s/oldword/neword/g`. Replace in a selection using `:s/old/new/g`.
22. Waypoints: Mark a line using `msomething`. Navigate anytime to this line using `'something`.
23. Centre a line: `zz`
24. Macros- Keybind a bunch of commands. To record macro for `@a`, type `qa` to enter recording mode. Enter your commands, then exit using q.
