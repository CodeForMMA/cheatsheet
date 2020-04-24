# Cheatsheet

> 'You saved my life with this!' - Snowden

> 'Fantastic' - The Wall Street Journal

> 'Astonishing!' - The LA Times

Table of Contents
=================

- [Terminal](#terminal)
- [ITerm2](#iterm2)
- [PdfLatex](#pdflatex)
- [Git](#git)
- [NVIM](#nvim)
    - [Plugins](#plugins)
        - [vim-snippets](#vim-snippets)
        - [NERDTree](#nerdtree)
- [Vagrant](#vagrant)

----------------

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

- [Splits](https://thoughtbot.com/blog/vim-splits-move-faster-and-more-naturally)

- [Mapping Keys for Vim](https://vim.fandom.com/wiki/Mapping_keys_in_Vim_-_Tutorial_(Part_1))

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

- Vertical Split (Inside NVIM)
    - ``:vsp``
    - ``<leader>v``

- Horizonal Split (Inside NVIM)
    - ``:sp``
    - ``<leader>p``

- Moving between Splits
    - ``<leader>h``
    - ``CTRL + W + W ``

- [Adjust the split](https://vi.stackexchange.com/questions/514/how-do-i-change-the-current-splits-width-and-height) 
    - ``CTRL + W + (+ or -)``
    - ``CTRL + W + =`` 
        - This will equalise the splits

#### Plugins ####
##### vim-snippets #####

- [Cheatsheet on Snippets for Markdown](https://jdhao.github.io/2019/01/15/markdown_edit_preview_nvim/)
    - Contains the snippets for writing markdown

- [How to use ultisnips](http://vimcasts.org/episodes/meet-ultisnips/)

- [Markdown Snippets Code](https://github.com/honza/vim-snippets/blob/master/snippets/markdown.snippets)

- [Python Snippets Code](https://github.com/honza/vim-snippets/blob/master/snippets/python.snippets)

##### NERDTree

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

### Vagrant

- [Changing the default shell](https://stackoverflow.com/questions/11913990/iterm2-keyboard-shortcut-for-moving-tabs-around)
    - `sudo chsh -s /bin/zsh vagrant`


