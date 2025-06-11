# VIM / NEOVIM Command

* Download configuration file for vim or neovim

[Configuration file for vim or neovim](https://github.com/arg0n3x/dotfiles/tree/master/vim.conf)

## Main Modes

1. NORMAL MODE: key `Esc`

   * Inserted keys are interpreted as commands for navigation, editing, and text manipulation.
     You can move, copy, paste, delete, search, replace, and execute actions.

2. INSERT MODE: key `i`

   * Text can be inserted and edited. The inserted text is interpreted as characters.

3. COMMAND MODE: character `:`

   * Used to execute specific commands by using the prefix `:` followed by the command.

**How to move in the editor**

* Key `h` moves left.
* Key `l` moves right.
* Key `k` moves up.
* Key `j` moves down.

**How to insert text**

* Key `i` inserts to the left of the cursor.
* Key `a` inserts to the right of the cursor.
* Key `I` inserts at the beginning of the line.
* Key `A` inserts at the end of the line.

**How to move between words**

* Key `w` moves forward by word, placing the cursor at the beginning of each word.
* Key `e` moves forward by word, placing the cursor at the end of each word.
* Key `b` moves backward by word, placing the cursor at the beginning of the word.

### *This is a list of commands used in vim / neovim text editors*

* Open a file with `vim` / `neovim`.

```bash
 vim file
```

```bash
 nvim file
```

* Save changes.

```bash
 :w
```

* Save changes forcefully.

```bash
 :w!
```

* Exit the editor.

```bash
 :q
```

* Exit the editor forcefully.

```bash
 :q!
```

* Save and exit.

```bash
 :wq
```

* Save and exit forcefully.

```bash
 :wq!
```

* Delete character by character.

```bash
 # use Esc (normal mode)
 # press `x`
```

* Delete everything after the cursor.

```bash
 # use Esc (normal mode)
 # press `D`
```

* Delete a complete line or X number of lines below.

```bash
 # use Esc (normal mode)
 # press `dd` or `d10d`
```

* Undo or Redo.

```bash
 # use Esc (normal mode)
 # undo press `u`
 # redo press `ctrl+r`
```

* Delete content from the current line to the last line.

```bash
 # use Esc (normal mode)
 # press `dG`
```

* Delete word by word.

```bash
 # use Esc (normal mode)
 # press `dw` or `db`
```

* Copy a line or several lines.

```bash
 # use Esc (normal mode)
 # press `yy` or `y10y`
```

* Move forward word by word.

```bash
 # use Esc (normal mode)
 # press `w` or `e`
```

* Move backward word by word.

```bash
 # use Esc (normal mode)
 # press `b`
```

* Go to the end of the file.

```bash
 # use Esc (normal mode)
 # press `G`
```

* Go to the beginning of the file.

```bash
 # use Esc (normal mode)
 # press `gg`
```

