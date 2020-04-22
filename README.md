# Cheatsheet

> 'You saved my life with this!' - Snowden

> 'Fantastic' - The Wall Street Journal

> 'Astonishing!' - The LA Times

### Terminal

- cd back into previous directory
    - ``cd -``

### iTerm2

- New Terminal Vertical
    - ``CMD + d ``

- New Terminal Horizontal
    - ``CMD + SHIFT + d ``

- Switching between splits
    - ``CMD + [`` or ``CMD + ]``

### NERDTree

- Moving buffers (From nerd tree to the opened file / navigate through different buffers)
    - ``gt``

- Open new file into buffer
    - ``o``

- Switching Panes (Nerd tree/Different buffers)
    - ``CTRL-w-w``

- Renaming files in NERDTree
    - ``m-m (new name)``

- Refresh Tree
    - ``r`` ``CTRL-r``

- Bookmark directory
    - ``:Bookmark``

- Open Bookmark 
    - ``:OpenBookmark <name>``

### PdfLatex

- Compiling file to pdf with bibtex
    - ``pdflatex report.tex && bibtex report.aux && pdflatex report.tex && pdflatex report.tex`` 

### Git

- Unstage all
    - ``git reset``

- Check what the remote is
    - ``git remote -v``

- Unstaging a specific file
    - ``git reset -- <path>``

### NVIM

- [Search and Replace Full Deets](https://vim.fandom.com/wiki/Search_and_replace)

- Search and replace all
    - ``:%s/(foo)/(bar)`` 

- Terminal Mode 
    - ``:Terminal``

- Exit Terminal Mode 
    - Remapped to ``ESC``
    - Usually `` CTRL - \ + N ``

- Changing buffers
    - `` ARW KEYS `` 

- Closing buffers 
    - `` :buffers `` 

- Fast Fold allows you to fold
    - `` za `` to open and close folds

- Git inside NVIM
    - ``:!git <command>``

- Changing the pwd to current buffer
    - ``:cd %:p:h``

### Python

- Conda activate
    - ``conda config --set auto_activate_base False or True``
    - [More](https://docs.anaconda.com/anaconda/install/mac-os/)
