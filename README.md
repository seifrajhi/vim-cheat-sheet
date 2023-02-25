# vim-cheat-sheet
here are some commonly used Vim shortcuts grouped by category

## Navigation
| Shortcut | Description |
|----------|-------------|
| `h`      | Move left   |
| `j`      | Move down   |
| `k`      | Move up     |
| `l`      | Move right  |
| `w`      | Move forward to the start of next word |
| `W`      | Move forward to the start of next WORD |
| `e`      | Move to the end of the word |
| `E`      | Move to the end of the WORD |
| `b`      | Move backward to the start of previous word |
| `B`      | Move backward to the start of previous WORD |
| `0`      | Move to the start of the line |
| `$`      | Move to the end of the line |
| `gg`     | Move to the first line of the document |
| `G`      | Move to the last line of the document |
| `:n`     | Move to line number `n` |

## Editing
| Shortcut | Description |
|----------|-------------|
| `i`      | Insert mode - insert before the cursor |
| `I`      | Insert mode - insert at the beginning of the line |
| `a`      | Insert mode - insert after the cursor |
| `A`      | Insert mode - insert at the end of the line |
| `o`      | Insert mode - insert a new line below the current line |
| `O`      | Insert mode - insert a new line above the current line |
| `r`      | Replace the character under the cursor |
| `R`      | Overwrite mode - overwrite the characters under the cursor |
| `u`      | Undo the last command |
| `Ctrl`+`r` | Redo the last undo command |
| `.`      | Repeat the last command |

## Visual Mode
| Shortcut | Description |
|----------|-------------|
| `v`      | Start visual mode |
| `V`      | Start linewise visual mode |
| `Ctrl`+`v` | Start blockwise visual mode |
| `o`      | Move to the other end of the selection |
| `d`      | Delete the selected text |
| `y`      | Yank (copy) the selected text |
| `>`      | Indent the selected text |
| `<`      | Unindent the selected text |

## Search/Replace
| Shortcut | Description |
|----------|-------------|
| `/`      | Search forward |
| `?`      | Search backward |
| `n`      | Move to next search result |
| `N`      | Move to previous search result |
| `:s/old/new/g` | Replace all occurrences of 'old' with 'new' on the current line |
| `:%s/old/new/g` | Replace all occurrences of 'old' with 'new' in the entire file |
| `:s/old/new/gc` | Replace all occurrences of 'old' with 'new' on the current line with confirmation |
| `:%s/old/new/gc` | Replace all occurrences of 'old' with 'new' in the entire file with confirmation |

## File Management
| Shortcut | Description |
|----------|-------------|
| `:w`     | Save the current file |
| `:wq`    | Save the current file and quit |
| `:q`     | Quit the current window |
| `:q!`    | Quit the current window without saving changes |
| `:wq!`   | Save the current file and quit even if there are
