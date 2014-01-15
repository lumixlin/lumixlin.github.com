Date: 2014-01-04
Title: Vim Commans And Shortcuts
Slug: shortcut_vim
Tags: note, linux

### Code Commentary (NERDCommenter)
- `\cc` = `// comment current line or seleted texts in visual mode`
- `\cm` = `/* comment with mutipart delimiter */`
- `\c$` = `int a = 0; // comment from cursor to the end of line`
- `\cu` = uncomment

---------

### Quick File, Tag, Line Access (Ctrlp)
- `\ff` = open promp window for searching(find file mode)
- `<c-c>` = close promp window

----------
- `\fl` = search line in buffer files.(file in vim buffer)
- `\ft` = search tag(ctag) in buffer files(file in vim buffer), based on ctags.
- `\fm` = search file on recent used file(the caches stored somewhere). 
- `\fc` = search comman.

----------
- `<c-j>, <c-k>` = move up and down in listed items.
- `<c-f>, <c-b>` = change search mode forward and backward.

---------

### Navigation
- `\bj, \bk` = switch to previous/next buffer
- `:b[n]` = switch to buffer n

---------

### Info Windows
- `\bt` = toggle buffer window(minibufexpl)

### Close
- `\bc` = close\delete current buffer
- `\bo` = close\delete all buffer but current one
- `Alt-a-x` = close current panel(tmux panel)
- `Alt-a-&` = close current window(tmux window)

---------


### Vim Internal

-----------
*verbs*

- `v` = visual
- `c` = change
- `d` = delete
- `y` = yank/copy

-----------
*modifier*

- `i` = inside
- `a` = around
- `t` = till..find a character(not include the char)
- `f` = find..like till except including tha char(include the char)
- `/` =	search..find a string/regx(encluded)

-----------
*text object*

- `w` = word
- `s` = sentence
- `p` = paragraph
- `b` = block/parenthese
- `t` = tag, work for html/xml

-----------
*operate*

- `diw` = delete inside word(delete the current word)
- `cis` = change inside sentence(change the current sentence)
- `ci"` = change inside quote(change a string inside quotes)
- `c/foo` = change search foo(change untile next occurrence	of 'foo')
- `ctX` = chage till X(change evering till X)
- `vap` = visual arround paragraph(visually select this paragraph)

--------

### Latex
- `F5` = insert an environment
- `F9` = insert a reference when you type `\ref` and `\cite`
- `<C-j>` = jump to next placeholder
- `\ll` = complile
- `\lv` = view
- `\ls` = view in current position
- `\rf` = folding


### Terminal (tmux)
- Server > Session > Window > Pane

----------------------------
- *Global control*
- `?` = list all shortcut
- `d` = detach from current session, you can attach by `tmux attach`
- `[` = start copy mode.Then press `space` start copy, press `Enter` to copy.
- `]` = paste
- `t` = show system time

---------------------------
- *Widows control*
- `w` = switch window by selecting form window list 
- `p, n` = switch to previous window or next window
- `,` = rename current window
- `.` = reindex current window
- `&` = close current window

-------------------------
- *Panel control*
- `%` = splict current panel into two, horizentolly
- `"` = splict current panel into two, vertically
- `!` = move current panel to a new window
- `x` = close current panel
