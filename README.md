#My own .vimrc Backup Repo
This repo is backup of my vim setting.
##For Python Development
###Tutorial Articles
+ [Turning Vim into a modern Python IDE](http://www.sontek.net/blog/2011/05/07/turning_vim_into_a_modern_python_ide.html#window-splits)
+ [Vim as a Python IDE](http://unlogic.co.uk/2013/02/08/vim-as-a-python-ide/)

###Collection of Libraries
+ [rkulla/pydiction](https://github.com/rkulla/pydiction)  
Python Tab-completion for Vim  
Put the dictionary file in the below dir and add this line.

     let g:pydiction_location = '/Users/<Username>/.vim/bundle/pydiction/complete-dict'

+ [davidhalter/jedi-vim](https://github.com/davidhalter/jedi-vim)  
Python autocompletion with VIM
+ [klen/python-mode](https://github.com/klen/python-mode)  
Syntax highlighting, Virtualenv support, Run python code, Linting..etc.  
Here is my pymode setting.  

     let g:pymode_rope = 0
     " Documentation
     let g:pymode_doc = 1
     let g:pymode_doc_key = 'K'
     let g:pymode_folding = 1

    " Linting
    let g:pymode_lint = 1
    let g:pymode_lint_checker = "pyflakes,pep8"

    " Auto check on save
    let g:pymode_lint_write = 1

    " Support virtualenv
    let g:pymode_virtualenv = 1

    " Syntax hightlighting.
    let g:pymode_syntax = 1
    let g:pymode_syntax_all = 1
    let g:pymode_syntax_indent_errors = g:pymode_syntax_all
    let g:pymode_syntax_space_errors = g:pymode_syntax_all

+ [Syntastic](https://github.com/scrooloose/syntastic)  
Syntastic is a syntax checking plugin for Vim  

##For JavaScript, CSS and HTML Development

###Tutorial Articles
[Vim Dev with Go and JS](http://blog.v-studios.com/2014/08/setting-up-vim-for-development-with-go.html)

###Collection of Libraries
+ [vim-javascript](https://github.com/pangloss/vim-javascript)  
JavaScript bundle for vim, this bundle provides syntax and indent plugins.
+ [html5.vim](https://github.com/othree/html5.vim)  
HTML5 + inline SVG omnicomplete function, indent and syntax for Vim. Based on the default htmlcomplete.vim.
+ [vim-css3-syntax](https://github.com/hail2u/vim-css3-syntax)  
Add CSS3 syntax support to Vim's built-in syntax/css.vim.
+ [vim-javascript-syntax](https://github.com/jelera/vim-javascript-syntax)
Enhanced JavaScript Syntax for Vim
+ [emmet-vim](https://github.com/mattn/emmet-vim)  
emmet-vim is a vim plug-in which provides support for expanding abbreviations similar to emmet.
+ [MatchTag](https://github.com/gregsexton/MatchTag)  
This plugin highlights the matching HTML tag when the cursor is positioned on a tag. It works in much the same way as the MatchParen plugin.


## Other convenient tools
+ [NerdTreeTab](https://github.com/jistr/vim-nerdtree-tabs)  
This plugin aims at making NERDTree feel like a true panel, independent of tabs.
NerdTree Setting  

      " ===== For Nerd Tree Setting =====
      map <F2> :NERDTreeToggle<CR>
      map <F1> :NERDTreeTabsToggle<CR>

      Press fn + F1 to open NERDTreeTabsToggle  
      Press fn + F2 to open NERDTreeToggle
            
## Start from...
Awesome the plug-in manager for Vim
+ [Vundle](https://github.com/gmarik/Vundle.vim)
